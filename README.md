# AWS-IAM-SECURITY-TOOLS
Walkthrough on how to use Credential Report and Access Advisor

Starting with Credential report sign in to the AWS Management Console and search for or select IAM

<img width="962" height="1040" alt="image" src="https://github.com/user-attachments/assets/fa0f162c-72f1-40b5-9b54-769fb12ff7a6" />

In the left navigation pane, under Access management, choose Credential report

<img width="347" height="929" alt="image" src="https://github.com/user-attachments/assets/a4e68fdd-96bd-4496-ba35-8d775bbdf863" />

Click Download report

<img width="962" height="559" alt="image" src="https://github.com/user-attachments/assets/e0aed0cb-7130-4826-b9a5-709786c55c27" />

<img width="966" height="307" alt="image" src="https://github.com/user-attachments/assets/9f31baff-dd43-4adf-943e-b2efa97a93c0" />

This CSV file inventories all AWS identities (IAM users and root) and details their credential status, compliance, and activity

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/55f3323b-3214-41c8-b374-e82adaf13e20" />

Next, we also have Access advisor

Once your in the AWS Management Console

In the left navigation pane, choose the entity type you want to audit: Users, Roles, User groups, and Policies. For this example, I chose users

<img width="963" height="798" alt="image" src="https://github.com/user-attachments/assets/919ea87c-825d-4190-b293-5561f63f6c8d" />

Click on the name of the specific user, role, group, or policy: Robert

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a52b7ca0-9ba8-4b52-bae5-2d2c705fabea" />

Select the Last Accessed tab next to the Security credentials tab

<img width="1913" height="738" alt="image" src="https://github.com/user-attachments/assets/03a0bd06-220f-472c-95a3-bb873f3e0daa" />

Here you can review the list of services and their Last accessed timestamps. The primary benefit of IAM Access Advisor is achieving least privilege by identifying and removing unused AWS permissions

<img width="1567" height="810" alt="image" src="https://github.com/user-attachments/assets/c7e24de9-5e8f-4cb7-ba6b-470bd62637dc" />
