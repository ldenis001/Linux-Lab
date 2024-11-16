# Project: Managing File Permissions in Linux

Project Overview:
This project demonstrates how Linux file and directory permissions were analyzed and updated to align with organizational security policies. By checking existing permissions and using appropriate commands, access control was improved to protect sensitive data.

# Key Features:
	1.	Checking File and Directory Permissions:
	•	Used ls -la to list detailed file permissions, including hidden files, in the projects directory.
	•	Interpreted the 10-character permissions string to understand user, group, and other access levels.
	2.	Updating Permissions:
	•	Removed unauthorized write access for “other” on specific files using chmod.
	•	Modified permissions on a hidden file (.project_x.txt) to restrict write access while ensuring read access for the group.
	•	Adjusted directory permissions to ensure only a specific user (researcher2) could execute and access the contents of the drafts directory.
	3.	Practical Examples:
	•	Removed write access for “other” on project_k.txt.
	•	Adjusted permissions for the archived hidden file .project_x.txt using combinations of u-w, g-w, and g+r.
	•	Ensured least privilege access for the drafts directory.

 Summary:
This project emphasizes the importance of proper file and directory permission management in Linux to ensure system security. It showcases practical use cases of the chmod command to implement least privilege access while adhering to organizational policies.

Keywords: #Linux #FilePermissions #chmod #AccessControl #Cybersecurity
