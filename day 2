1] Authoritative Source - Main trusted system from which SailPoint pulls the most accurate and official identity data

2] Different types of HR tools - Workday , SAP , peoplesoft , Oracle HCM.

3] Oracle OOTB connector is deprecated -> Due to this organisations are using file based approach (Excel sheet - similar to import export)

4] Mandatory Attributes for successful Identity Creation- UserName(UID) , Email ,LastName. (Without these identity can be created but that will be in error state).

5] Aggregation in SailPoint means importing data from a connected system (like AD, HRMS, SAP, etc.) into SailPoint IdentityNow or IdentityIQ to build or update the identity repository.

 Aggregation in SailPoint

**Full Aggregation:**  
- Imports **all identity data** from a connected system.  
- Used for **initial setup or full resync**.  
- Slower and resource-intensive.  

**Delta Aggregation:**  
- Imports **only changes** since the last aggregation (new, modified, or deleted users).  
- Used for **daily or scheduled updates**.  
- Faster and more efficient.  

**Summary:**  
> Full = all data, Delta = only changes.


By default the aggregation is delta aggregation only. For running the Full aggregation we can do using the VSCODE or Postman.
