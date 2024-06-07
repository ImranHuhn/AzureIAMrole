<h1 align="center">Creating an IAM role</h1>

<h2>TLDR: Create IAM role for user</h2>

- <b>Introduction: </b>Navigating and adding IAM roles ensures a secure access environment.

- <b>Navigating and adding an IAM role: </b>Select resource group, navigate to "Access control (IAM)" section.

- <b>Assigning a role: </b>Enter "desktop virtualization contributor" in the search bar.

- <b>Adding members: </b>Go to the "Member" section, select user(s).

- <b>Review: </b>Verify all details and configurations before proceeding.

- <b>Complete and verify: </b>After role assignment, verify IAM user existence in access control settings.
 
- <b>Conclusion: </b>Role assignment ensures secure access.

<h2>How to read each section (in this order)</h2>

<b>Section-Intro</b> 
- <b>Title: </b>Name of the section.
- <b>Description: </b>Describe what the section entails. Some sections won’t have descriptions. 

<b>Image</b> 
- <b>Numbering: </b>Within the images are sequential numbers, with corresponding text explanations directly below each image.
- <b>Yellow highlights: </b>Yellow highlights are navigation aids to help identify your current section in the Azure portal.

<b>Text numbers</b> 
- <b>Numbers: </b>Each number provides a brief explanation of the image directly above it.

<b>Side notes</b> 
- <b>Notes: </b>Any extra details you should be aware of.

<h2>Introduction</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Navigating and adding an IAM role within a resource group is essential for maintaining a controlled and secure access environment. This process involves reviewing existing roles, assigning specific permissions, and ensuring users' responsibilities are appropriately limited. By following structured steps, we can effectively manage access within the resource group, enhancing security and operational efficiency.

<h2>Navigating and adding an IAM role</h2>

<b>Description: </b>We need to navigate to the "Access control (IAM)" section within the chosen resource group. Here, you have the option to explore the "Role assignments" tab to review all existing roles and their current assignments. After familiarizing yourself with the current setup, we will proceed to add a new user and assign them a specific role, ensuring their permissions are appropriately limited to their responsibilities. This process allows for a controlled and secure access environment within the resource group.

![01_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/53f4e086-7aea-438c-a0ca-1fb44edcd56b)

1.  Once you are in the resource groups section, select the specific resource group where you want to delegate the IAM user.
2.  Within the specific resource group, navigate to the "Access control (IAM)" section.
3.  (Optional) Click here to explore the current roles and permissions that have already been assigned.
4.  Click "Add" to start the process of assigning roles to a user.

<h2>Assigning a role</h2>

<b>Description: </b>We have now entered the "Role" section of the process. This section displays a comprehensive list of all preconfigured roles available for assignment. While you have the option to browse through the various roles, for the purpose of this task, we will concentrate on assigning the "desktop virtualization contributor" role. This specific role grants the necessary permissions for desktop virtualization tasks.

![02_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/f621b17e-5584-4f96-a176-9b21e37e8911)

1.  Ensure you are in the "Role" section.
2.  Enter "desktop virtualization contributor" in the search bar.
3.  Find the role in the list and highlight it by clicking on it.
4.  When you are ready, click on "Next."

<h2>Adding members</h2>

<b>Description: </b>We are now in the "Member" section of the process, where you have the ability to select multiple users, to assign the designated role. For this specific task, our focus will be on assigning the role to a single user, specifically the one we created in the previous lab. This section allows for a streamlined selection process, ensuring that each chosen user receives the appropriate role assignment. By concentrating on the user from our earlier setup, we can maintain consistency and accuracy in our role assignment workflow.

![03_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/c33f5a67-61ba-479e-8c74-41d4ee52b84e)

1.  Note that we are now in the "member" section.
2.  A panel on the right will appear, displaying the users you can select, when you click on this section.
3.  Select a user by clicking on their name. For this lab, we will choose the previously created user, "labuser2".
4.  Click on "select" to confirm and designate the user as a member. If desired, you can repeat steps 2 and 3 to add additional users.
5.  Please proceed to the next step once you are content with the members selected for this role.

<h2>Review</h2>

<b>Description: </b>This step is simple and involves reviewing your entries to ensure accuracy and satisfaction with your selections. Carefully verify all the details you have filled in to confirm that they are correct. Make sure that the chosen roles and assigned users align with your intended configurations. This final review ensures that everything is set up properly before completing the process.

![04_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/09b02899-cc02-4751-b6f0-cac7bd92e1d9)

1.  When you're ready, click on "Review + assign" to initiate the construction.

<h2>Complete and verify</h2>

<b>Description: </b>In this final step, we will complete the process of assigning a role to a user, effectively converting them into an IAM user with the specified permissions. After completing the role assignment, we will verify the existence of the newly assigned IAM user. This involves checking the access control settings to ensure that the user appears in the list of role assignments, confirming that the permissions have been correctly applied.

![04_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/09b02899-cc02-4751-b6f0-cac7bd92e1d9)

1.  Select the bell notification icon to reveal a panel on the right side.
2.  Once the status bar fills up, it should display the message "Role assignment added" accompanied by a green check mark.
3.  To confirm, navigate to the "access control" section within the particular resource group we employed.
4.  Select the "Role assignments" tab found within this section.
5.  This space should display a roster of users, including the one you've just assigned.

Note: Please be advised that if the assigned user does not appear, kindly click on the "refresh" button located at the top.

<h2>Conclusion</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Completing the process of assigning a role to a user is vital for establishing a robust access control mechanism. Through careful navigation and selection, we ensure that each user receives the necessary permissions aligned with their responsibilities. Verifying the role assignment and user inclusion in the access control settings confirms the accuracy of the process, promoting a secure and organized environment for resource management.
