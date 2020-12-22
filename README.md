1. Unpack & install.
2. Stop corresponding atlassian service(s).
3. Patch application with provided KeyMaker - with admin rights (just apply patch in Atlassian installation directory).
4. Restart corresponding Atlassian service(s).
5. Generate a valid serial number for the application.
6. Enjoy!

Use "AtlassianKeyMaker-mod" for Service Desk

Note:
    open an elevated command prompt
    go to where the keygen is
    type java -jar AtlassianKeyMaker.jar

that way it can patch the required jar files which are

atlassian-universal-plugin-manager-plugin-2.22.9.jar under X:\Program Files\Atlassian\JIRA\atlassian-jira\WEB-INF\atlassian-bundled-plugins
atlassian-extras-3.2.jar under X:\Program Files\Atlassian\JIRA\atlassian-jira\WEB-INF\lib

for Jira Software and Jira Core.
=====================+