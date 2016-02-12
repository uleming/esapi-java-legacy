Сборка для PID (http://community.pentaho.com/projects/data-integration/)

При выводе данных в XML Output все кирилические символы преобразутся в escape последовательности.
Баг отмечен здесь http://jira.pentaho.com/browse/PDI-11184

для сборки добавить 
mvn package -Dmaven.test.skip=true 
т.к. тест на проверку espace последовательностей проваливается.

для других проектов использовать оригинальный репозиторий https://github.com/ESAPI/esapi-java-legacy 


Enterprise Security API for Java (Legacy)
=================
<table border=0>
<tr>
<td>
OWASP ESAPI (The OWASP Enterprise Security API) is a free, open source, web application security control library that makes it easier for programmers to write lower-risk applications. The ESAPI for Java library is designed to make it easier for programmers to retrofit security into existing applications. ESAPI for Java also serves as a solid foundation for new development.
</td>
</tr>
</table>

<b>What does Legacy mean?</b><br/>
<p>This is the legacy branch of ESAPI which means it is an actively maintained branch of the project, however feature development for this branch will not be done. Features that have already been scheduled for the 2.x branch will move forward, but the main focus will be working on the ESAPI 3.x branch.

<b>IMPORTANT NOTE:</b>
The default branch for ESAPI legacy is now the 'develop' branch (rather than the 'master' branch), where future development, bug fixes, etc. will now be done. The 'master' branch is now marked as "protected"; it reflects the latest stable ESAPI release (2.1.0.1 as of this date). Note that this change of making the 'develop' branch the default may affect any pull requests that you were intending to make.

<b>Where can I find ESAPI 3.x</b><br/>
https://github.com/ESAPI/esapi-java

<b>How can I contribute or fix bugs?</b><br/>
Fork and submit a pull request! Simple as pi!

<b>What happened to Google code?</b><br/>
In mid-2014 ESAPI Migrated all code to GitHub, in November we started using JIRA/Confluence. 

<b>What about the issues still located on Google Code</b><br/>
We will be migrating the issues from Google Code to JIRA as time allows, in the meantime - if you would like to work on a Google Code issue, please create a new issue in JIRA and reference the Google Code issue in the issue Description.

Wiki: https://www.owasp.org/index.php/Category:OWASP_Enterprise_Security_API

Nightly Build: https://esapi.ci.cloudbees.com

~~JIRA: https://owasp-esapi.atlassian.net/browse/ESAPILEG~~<br />Issues: Until further notice, use the GitHub issues for reporting bugs and enhancement requests.


Documentation: https://owasp-esapi.atlassian.net/wiki/display/ESAPILEG/ESAPI+Legacy (Coming Soon)

Realtime Support available on our IRC Channel:<br/>
Server: irc.freenode.net<br/>
Channel: #esapi<br/>
Webchat http://webchat.freenode.net/

