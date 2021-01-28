Method PUT not allowed:
Add on web.config (
<system.webServer>
	<modules runAllManagedModulesForAllRequests="true">
    <remove name="WebDAVModule"/> 
  </modules>
</system.webServer>
