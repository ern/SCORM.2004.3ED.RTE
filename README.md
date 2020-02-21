## Installation notes:

For Sakai 11+, the following sakai.property needs to be set (as a result of Sakai going frameless):

portal.iframesuppress=:all:sakai.scorm.singlepackage.tool:sakai.scorm.tool

## Oracle support:

There is a known issue with auto.ddl creating the SCORM tables. This issue is being tracked @ https://jira.sakaiproject.org/browse/SCO-84

The workaround is to either create all the SCORM tables manually (with a provided script), or manually change some datatypes on specific columns that cause the problem. Both workarounds are explained in Confluence @ https://confluence.sakaiproject.org/display/SCORMPLAYER/Sakai+SCORM+player+installation+guide#SakaiSCORMplayerinstallationguide-OracleSupport

## Historical Info

This project was originally developed and maintained by UC Davis and made available on an ECL 1 license.
Since the project was moved to GitHub, the license has been updated to ECL 2.

UC Davis never got around to finishing the project and never took deployed the tool to production.

EDIA saw a growing demand for a working SCORM player for Sakai. EDIA has been fixing bugs and working
on the code base at several points in time to improve the stability. Furthermore, the ability to
synchronize results to the gradebook has been implemented.

We at EDIA are dedicated to committing our work and fixes back to the community. We've made our work available 
at the Sakai contrib repository.

Bugs and issues can be reported to:

https://jira.sakaiproject.org/browse/SCO
