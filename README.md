# Sitecore-Security-Rights-Reporting Module
View all the Access right set on Sitecore roles or users. You can make a list of all users and roles. It can be used to do audits.

![Example](https://raw.githubusercontent.com/jbluemink/Sitecore-Security-Rights-Reporting/master/Sitecore-Security-Rights-Reporting-Module.PNG)

##Download
See the Sitecore marketplace, or pick up the latest release build here ![/Package](https://github.com/jbluemink/Sitecore-Security-Rights-Reporting/tree/master/Package)

##Detail right
You can click on a user or role, and then you see all rights specific to that user or role put on sitecore items. Or click on all to see all rights. 
![Example detail rights](https://raw.githubusercontent.com/jbluemink/Sitecore-Security-Rights-Reporting/master/Sitecore-Security-Rights-Module-Detail.PNG)

##Using
Go to the Sitecore Desktop (/sitecore/shell/)
And push the left-bottom start button in the right menu there is inside the Security Tools menu a new Security Reporting menu item

This tool is for Sitecore Domain users, if there too many (extranet) users it is skipping other domain users, this tool works for max 200 users in the Sitecore Domain.

##Version
- 1.0 Initial version
- 1.2 Bug fixes
- 1.5 Add download and extra columns and descriptions and default roles/users
- 2.0 Now you can compare all the Sitecore rights with the default Sitecore rights and easy see you own or missing rights.
- 2.1 Bugfixing And Support for Everyone roles, Anonymous users, $currentuser token and check account exists on the item rights. Support for Sitecore 8.1 update-1 and Sitecore 8 update-6
- 2.2 Uninstaller, user count info, support for Sitecore 8 update 7, Bugfixing

##Upgading

- Install a new package and overwrite.

##Uninstall
Version 2.2 or higher
- Click on the uninstall link on the bottom right or use url: /sitecore%20modules/Shell/Security-Rights-Reporting/UserInfo.aspx?mode=uninstall

##To Build:
Add Sitecore.Kernel.dll to External folder

##Deploy:
- Copy the builded Security.Rights.Reporting.dll to the Sitecore bin directory (CMS server)
- Copy the UserInfo.aspx to \sitecore modules\Shell\Security-Rights-Reporting of your Sitecore (CMS server)
- Create the application in the core database and create a link in the menu, see the Serialization folder

![Example user](https://raw.githubusercontent.com/jbluemink/Sitecore-Security-Rights-Reporting/master/user-rights.PNG)
