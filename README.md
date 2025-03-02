1. Application Security Role Mapping

• Investigated and modified ibm-application-bnd.xml and server.xml to correctly map user groups to security roles.

• Verified group mappings using Liberty logs.

2. Maven Configuration

• Adjusted pom.xml to prevent auto-generation of application.xml.

• Ensured custom security role settings were retained during the build.

3. SiteMinder & Authentication Debugging

• Checked SiteMinder logs for group bindings and authentication issues.

• Ensured Liberty ASA login module correctly fetched group names.

4. Liberty Server Deployment & Troubleshooting

• Debugged expanded/ folder containing multiple .ear files.

• Restarted the Liberty server multiple times for testing changes.

5. Log Analysis & Search Optimization

• Used less and grep commands to efficiently search logs.

• Applied case-insensitive search to debug security mappings.

6. JS Authorization Issue

• Investigated failed access to browsercheck.js.

• Confirmed the user was not granted access to required roles.

