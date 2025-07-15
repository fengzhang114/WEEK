Weekly Status – July 7 – July 12
	1.	Liberty/SiteMinder Upgrade Use Case Validation
	•	Task: Continue support and validation of application flows for the upgraded Liberty/SiteMinder solution.
	•	Progress: Final validation work completed ahead of the RDL cutover scheduled on Wednesday, July 16. All pre-cutover test cases have been executed successfully.
	•	Next Steps: Provide post-cutover support and assist in resolving any potential issues after production cutover.
	2.	CSS Redirect Issue during Logout (Liberty + SiteMinder)
	•	Task: Investigate CSS files not loading correctly during logout due to potential SiteMinder redirection.
	•	Progress: Observed that .css files are being redirected (302 status) while images load correctly. Suspected SiteMinder is intercepting CSS requests during logout.
	•	Action Taken: Reported to SSC team with network trace and requested confirmation whether SiteMinder is blocking or modifying the request.
	•	Next Steps: Await feedback from SSC team and implement potential mitigation/workaround if necessary
