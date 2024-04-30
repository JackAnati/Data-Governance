# Data-Governance
Data governance is the set of policies, procedures, and controls that an organization develops to safeguard its information while making it useful for transactional and analytic purposes. As the name implies, data governance is primarily a business function. Governments have a method for creating, interpreting, and enforcing laws. 

# Data Governance Roles
- Data stewardship is the act of developing the policies and procedures for looking after an organization's data quality, security, privacy, and regulatory compliance. The data steward is responsible for leading an organization's data governance activities. As the link between the technical and non-technical divisions within an organization, a data steward works with many people, from senior leaders to individual technologists. To establish policies, a data steward works with various data owners.
- Data owner is a senior business leader with overall responsibility for a specific data domain. A data domain, or data subject area, contains data about a particular operational division within an organization. Data owners work with the data steward to establish policies and procedures for their data domain.
- Data custodian is a role given to someone who implements technical controls that execute data governance policies. Data custodians are frequently information technology employees who configure applications, dashboards, and databases.
- Data access requirements determine which people need access to what data. Access requirements differ by data subject area and can be as granular as a single.
- A data classification matrix defines categories, descriptions, and disclosure implications for data.

  # Access Permissions
It is a best practice to use role-based access to grant people permission to access data. Role-based access means that instead of giving access to individual people, you grant access to the role they occupy. When you define roles and then assign people to those roles, it simplifies how you manage permissions.

 # Group Permissions 
 When developing a role-based access strategy, it is common to implement user group-based permissions. 

  # Data Use Agreements
A data use agreement (DUA) is a contractual document for transferring private data between organizations. You should establish a DUA before sharing data with an outside party. It is essential to understand the classification for each piece of data when crafting a DUA. 
A DUA provides details governing the transfer, use, and disclosure of reporting protocols for the data. Some of these details are:

- Identifying who will receive the data
- Identifying how the data can be used
- Prohibiting the further distribution of the data
- Establishing the method of transfer
- Identifying how the recipient will protect the data

# Security Requirements
- Encryption
- Data in transit is data that is actively moving between one location and another.
- Data masking, or data obfuscation, replaces sensitive information with a synthetic version.
- Deidentifying data is the process of removing identifiers that can compromise individual privacy. How you deidentify depends on your use case. One way of deidentifying data is to share only aggregated or summarized data. Another way is to remove variables from the data.
- Reidentifying data happens when you take deidentified datasets and join them in a way that establishes the identity of individuals. For example, you can identify most Americans by combining their birth date, sex, and zip code.

  # Storage Environment Requirements
There are many environments where data at rest exists, including local storage, a shared drive, and the cloud. Regardless of the storage environment, you need to encrypt all data at rest. Local storage is the storage media on an individual device, such as a hard drive in a laptop. Encrypting local storage is straightforward, regardless of the operating system you use.

# Use Requirements

Use requirements specify how to collect, process, use, store, retain, and remove data. While understanding audience requirements is vital for creating impactful visualizations, understanding data use requirements is crucial to effective data governance. An *acceptable use policy* (AUP) defines an individual's responsibilities when accessing, using, sharing, and removing organizational data. While an AUP is a document with a broad scope, it has provisions for each type of data in an organization's data classification matrix. AUPs describe acceptable locations for storing proprietary information; what to do in the event of theft, loss, or unauthorized disclosure; and methods of disposal.
