
# Steps to Complete the YouTube Data Analysis Project

1. AWS Setup

	1.1. Create User with Admin Access
	* Log in to the AWS root account.
	* Create a new user with administrator access.
	* Download the following files for the new user:
		* credential.csv
		 access.csv
	
	1.2. Install AWS CLI
	* Install the AWS CLI using Homebrew: `brew install awscli`

	1.3. Configure AWS CLI

	* Run the configuration command:Bash / terminal --> `aws configure`
		* Provide the following information:
		* Access Key ID
		* Secret Access Key
		* Default region name: ap-south-1 (Mumbai)
		* Default output format: (Choose your preferred format)

	1.4. Verify S3 Bucket Access : List S3 buckets to confirm configuration: `aws s3 ls`
	
 	1.5. Switch to User Account
	* Log out of the root account.
	* Log in to the newly created user account with limited access.
