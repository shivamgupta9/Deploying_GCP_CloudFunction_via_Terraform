# Deploying_GCP_CloudFunction_via_Terraform
Deploy a Cloud Function via terraform that will triggered each time a file is uploaded to a bucket and store source code of cloud function in the another bucket.

## Prerequisites
• Terraform installed on your local machine. <br>
• GCP project set up and attached to a billing account. Make sure the Cloud Functions API is Enabled. <br>
• Create a service account and create a key on that account and add it into terraform folder as credentials.json. <br>

## Steps to deploy
• cd terraform/ <br>
• terraform init <br>
• terraform plan <br>
• terraform apply <br>
