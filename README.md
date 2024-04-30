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

 # Data Classification Requirements
IData classification is the process of analyzing data and organizing it into risk-based categories. Classifying data is appropriate for both structured and unstructured data. 
- Personally Identifiable Information (PII) is any data that can uniquely identify a person and the information below can be applied to other countries. PII is any information about an individual maintained by an agency, including (1) any information that can be used to distinguish or trace an individual's identity, such as name, social security number, date and place of birth, mother's maiden name, or biometric records; and (2) any other information that is linked or linkable to an individual, such as medical, educational, financial, and employment
- Protected Health Information Under HIPAA, Protected Health Information (PHI) is the broad category of data elements identifying an individual's health information. This information can be about the individual's past, current, or future health status and covers providing healthcare, processing healthcare payments, or processing insurance claims. Alternatively, Electronic Protected Health Information, or e-PHI, is any PHI you store or transmit digitally.

  # Payment Card Information
The Payment Card Industry (PCI) is a non-governmental body that governs card-based financial payments. To protect the integrity of card-based financial transactions and prevent fraud, leading financial service companies, including MasterCard, Visa, Discover, American Express, and the Japan Credit Bureau, created the PCI Security Standards Council (PCI SSC). The PCI SSC develops policies to govern the processing, transmission, and storage of electronic payments.

The PCI Data Security Standard (PCI DSS) is the industry's core information security standard. The following six principles encompass the objectives set out by the PCI DSS:

- Building and maintaining a secure network
- Protecting cardholder data
- Maintaining a vulnerability management program
- Implementing strong access controls
- Regularly monitoring and testing networks
- Maintaining an information security policy
The second category is Sensitive Authentication Data (SAD). SAD includes complete track data from the magnetic stripe or embedded chip, Personal Identification Number (PIN), and the Card Verification Value (typically three digits on the back of a card).

# Jurisdiction Requirements
These categories include criminal law, civil law, administrative law, and private regulations.
- The goal of *criminal law* is to discourage people from acting in a way that negatively impacts society.
- The goal of civil law is to resolve disputes between individuals, organizations, and government agencies.
- The goal of administrative law is to enable the effective operation of government by allowing government administrative agencies to propagate regulations.
- The goal of private industry regulations is to govern the activities of individuals and organizations without the force of law. 

# Understanding Master Data Management
Master data management (MDM) is a data governance discipline that uses processes, tools, and technologies to ensure that data assets across an organization have a single source of truth. Successfully implementing MDM is a challenge regardless of industry or organizational size. As organizational complexity increases, identifying and maintaining an accurate, consistent, well-governed single source of truth becomes more challenging.

# Processes
The discipline of MDM is process-centric. For an organization with multiple separate operational systems, the consolidation of multiple data fields is part of a comprehensive duplicate resolution process. Maintaining a data dictionary is an essential component of effective MDM. A data dictionary is a document that contains metadata about your data structures.
In addition to the details about each column in the table, a data dictionary includes other metadata, including

Purpose of the table
Primary/foreign keys
Column index definitions
References by internal systems
References by external systems
Maintaining a data dictionary takes a significant effort. Fortunately, tools exist that can extract most of the metadata about tables from a database. It is crucial to instill procedural discipline for maintaining column-level comments since they help orient new analysts to your systems.

# Circumstances

Many circumstances lead an organization to pursue MDM. Typically, leadership identifies a difficulty that relates to having consistent information. To improve internal efficiency and reduce data quality issues, leadership recognizes the benefits of enhancing consistency across systems. 

Another reason for adopting MDM is compliance with policies and regulations that require consistent handling of data. When the same data has different definitions in different systems, the cost of compliance increases. Using MDM to drive accurate and consistent data definitions leads to better data stewardship, which drives down the cost of compliance.
