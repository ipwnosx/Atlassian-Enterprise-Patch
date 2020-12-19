## Atlassian Enterprise-Patch

Installation guide
Install the software first. After the installation, stop running the software.
Copy the following files from the Files folder and replace them in the specified paths
	
	Atlassian-extras-3.2.jar file:
Windows: C: \ Program Files \ Atlassian \ JIRA \ atlassian-jira \ WEB-INF \ lib \
Linux: /opt/atlassian/jira/atlassian-jira/WEB-INF/lib /

	Atlassian-universal-plugin-manager-plugin-4.0.4.jar file:
WINDOWS: C:\Program Files\Atlassian\JIRA\atlassian-jira\WEB-INF\atlassian-bundled-plugins\
LINUX: /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/

Start the Jira software service.
In Windows, start the Jira service through the Task Manager

•IN LINUX, use the following command to run the Jira service
/etc/init.d/jira start


Jira software runs on port 8080 by default. In the browser, enter the JIRA server address and port 8080 to display the JIRA installation environment.
Make the settings for the database to get to the software license entry step.
Copy the Jira Software license text from the License.txt file and paste it into the software.
After finishing the work and making the initial settings, enter the software through the admin user and select the Application section from the settings section.
In the Versions and Licenses section, copy the Jira Core license text from the License.txt file and enter it into the software.

Important Points:
• Do not update the software. Software updates will result in the licenses being disabled and you will need to perform the steps again.
Add-on updates do not cause a license issue. Do not update only the add-on‌ called Universal Plugin Manager.
• This license is for Jira Software 8.3.0 only. Therefore, to get a license for other versions and software


Heres where to get installers for other software:
https://www.atlassian.com/software



Heres a GUI example of running the .JAR file:
https://i.ibb.co/t4WtpbJ/download-1.png

The License:
https://i.ibb.co/qJTcpkr/download.png


