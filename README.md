1. Work Completed This Week
GQJG Authorization Issue Analysis

Collaborated with Broadcom to investigate the authorization failure in the GQJG environment.

Compared logs from Colin’s and Neha’s environments.

Identified that the group GQJG_clients_qo is being returned from SiteMinder, but the role is not defined in the ibm-bnd.xmi file, which caused Liberty to deny authorization.

Provided recommendations to define the missing group in Liberty configuration and align the SiteMinder mapping.

Deployment of New SQCI Application on OpenShift

Deployed the updated SQCI application in the new OpenShift environment following the system upgrade.

Resolved compatibility issues due to OpenShift version changes.

Verified deployment through smoke testing to confirm service stability.

2. Plans for Next Week
Assist with validation testing after the group mapping fix in the GQJG environment.

Support integration of the new SQCI app into the CI/CD pipeline.

Begin drafting internal documentation on updated OpenShift deployment procedures.
