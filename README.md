## Project

This SSM document can be used to archive images (taken from an EC2 instance) on S3 bucket. You could run it manually or use it as a post-launch SSM document in AWS Application Migration Service (AWS MGN) when migrating on-prem servers/applications to AWS cloud. You could use this SSM document as a way to archive your applications or data and maintain regulatory compliance or framework requirement.

How to run:


1. Create the SSM document in AWS Systems Manager SSM and then click on "Execute automation" to run the document:
https://docs.aws.amazon.com/systems-manager/latest/userguide/documents.html


2. Create a custom post launch action in AWS Application Migration Service to run this SSM document:
https://docs.aws.amazon.com/mgn/latest/ug/post-launch-settings-custom-actions-add.html

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

