1. Work Summary
This week, I studied and implemented form-based login in the IBM WebSphere Liberty server. I reviewed the IBM support documentation and understood the login flow defined by the Jakarta EE specification, as well as Liberty-specific configurations.

Main tasks completed:

Configured web.xml to define login-config, security constraints, and roles

Created custom login.html and error.html pages

Implemented and tested the j_security_check form submission

Set up a simple user registry and mapped roles using ibm-application-bnd.xml

Verified correct handling of the WASReqURL cookie during redirection

2. Key Learnings
Gained hands-on experience with Java EE security standards

Learned how Liberty handles form-based login and session management

Understood the difference between standard Java EE behavior and Liberty-specific features (e.g., WASReqURL)

3. Issues Encountered
Encountered issues with incorrect form action URL (missing j_security_check)

Error page redirection failed due to a missing path in the web.xml configuration

4. Next Week Plan
Explore integration with LDAP or federated user registries

Add logout functionality and session timeout handling

Research options for single sign-on (SSO) and token-based authentication
