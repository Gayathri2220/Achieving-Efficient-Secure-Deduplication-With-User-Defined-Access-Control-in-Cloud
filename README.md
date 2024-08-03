# Achieving-Efficient-Secure-Deduplication-With-User-Defined-Access-Control-in-Cloud

# Introduction
Cloud storage has become an integral part of modern computing infrastructure, offering convenience, scalability, and cost-effectiveness. A key technique employed in cloud storage is data deduplication, which optimizes storage space and reduces data management costs. However, the use of deduplication raises concerns regarding data privacy and security, particularly when multiple users' data is stored in the same physical location. To address these concerns, various techniques, including encryption and access control, have been proposed. However, many existing solutions lack user-defined access control, which is crucial for safeguarding data privacy and security in multi-user environments. Data deduplication involves removing redundant data by storing only a single copy of each unique data segment. This approach effectively reduces storage costs and enhances the overall efficiency of cloud storage systems. Nevertheless, traditional deduplication methods often fall short in terms of security, as they fail to provide adequate protection for sensitive data. To tackle this challenge, our proposed system introduces a secure deduplication technique that combines encryption and user-defined access control to ensure the confidentiality and privacy of data. By integrating cryptographic techniques such as the MD5 algorithm and hash functions, our scheme achieves secure deduplication while maintaining data integrity. Access control, a critical component of cloud computing, has found widespread use in practical cloud products. However, existing schemes that address authorized secure deduplication by introducing an additional authorized server have been susceptible to duplicate faking attacks. To overcome this vulnerability, we present an efficient and secure cross-user deduplication scheme that incorporates user-defined access control, ensuring data confidentiality, tag consistency, access control, and resistance to duplicate faking attacks simultaneously. In our research, we propose a novel secure deduplication scheme with user-defined access control for cloud storage. Our scheme leverages a combination of cryptographic techniques, including the MD5 Algorithm and hash functions, to achieve secure deduplication and protect data privacy. By addressing the limitations of existing solutions, our approach provides an innovative solution for organizations seeking to ensure the confidentiality and security of their data in the cloud...
# EASE OF USE
When it comes to ease of use for a Secure Deduplication with User-Defined Access Control in Cloud Storage system, there are a few key considerations to keep in mind:

# User Interface: A well-designed user interface can make a complex system much easier to use. Consider using a simple, intuitive interface that allows users to easily navigate and interact with the system.
# Clear Instructions: Provide clear instructions on how to use the system, including how to set up access control and how to securely store and retrieve data. Make sure that these instructions are easily accessible and written in plain language that is easy for users to understand.
# Automate Where Possible: Automating certain tasks can help to reduce the burden on users and make the system easier to use. For example, you could automate the process of deduplicating files or managing access control permissions.
# Provide Support: Finally, it is important to provide support to users who may have questions or issues with the system. This could include providing a helpdesk or support forum where users can ask questions and get help when they need it.
# Overall, by focusing on user interface design, clear instructions, automation, existing tools, and providing support, you can make your Secure Deduplication with User-Defined Access Control in Cloud Storage project much easier for users to use.
#  LITERATURE SURVEY
In a recent study [1], an innovative and efficient secure deduplication scheme with user-defined access control is proposed. Unlike previous approaches, this scheme eliminates the need for an additional authorized server or hybrid cloud architecture, making it more streamlined and practical. The Content Security Policy (CSP) is leveraged to manage access rights without compromising data confidentiality. Moreover, the scheme incorporates the use of Bloom filters for efficient duplicate checks.

Thorough security analyses of the proposed scheme demonstrate its ability to achieve multiple security objectives simultaneously. It ensures data confidentiality, access control, tag consistency, and resistance against brute-force attacks.

In a separate paper [2], the focus is on Attribute-Based Encryption (ABE) as a suitable solution for fine-grained cryptographic access control. The challenge of user revocation is addressed through the implementation of a cipher text policy attribute-based scheme, specifically designed for cloud-enabled user revocation. This scheme provides comparable granularity to ABE while minimizing computation and communication overhead at the user's end. Another paper [3] proposes a scheme based on attribute-based encryption (ABE) for secure data deduplication and data access control in the cloud. The scheme supports digital rights management based on the data owner's expectations, saving storage space by storing only one copy of duplicate data. The scheme is scalable, enabling support for multiple duplication instances and large volumes of duplicated data. Identity-based cryptography is the topic of discussion in a comprehensive paper [4]. This cryptographic technique, related to public key cryptography, is explored for its feasibility and potential benefits in current and future environments. The paper highlights the advantages and limitations of identity-based cryptography and discusses its role in secure communication. It distinguishes between symmetric key cryptography, where a single key is used for encryption and decryption, and asymmetric key cryptography, where a public-private key pair is employed. Lastly, an enhanced MD5 algorithm with dynamic variable length and high efficiency is proposed in  [5]. This method aims to simulate the highest level of security by generating different fragment sizes to thwart hostile attacks. The paper emphasizes the significance of the improved MD5 algorithm in maintaining data integrity, reliability, and authenticity. Various modifications, including the use of key technology, have been implemented to enhance the algorithm's collision resistance and resilience against penetration attempts.

Cloud Service Provider (CSP): The CSP provides storage services for user. In the authorized deduplication system, without violating access control, the CSP would like to eliminate the redundant data and keep only one copy to reduce the overhead associated with data storage...
# Which is an efficient technique for cloud storage using secured de duplication algorithm?
Tag consistency: After data deduplication, only one copy is stored in the CSP, and if this copy is inconsistent with the related tag, i.e., a malicious user (corrupted by an adversary) launches duplicate faking attacks during data upload, then the subsequent data owner together with authorized users cannot obtain the...
# What is cloud deduplication techniques?
The framework for the secured de-duplication system functions for scaling down the number of repeated copies or files. It performs a comparison for two documents using cosine similarity. It further uses NLTK algorithms for checking and detecting the meanings of both the files...
# What is secure deduplication?
Deduplication eliminates these extra copies which are the same, just to save a copy of the data. Data privacy, security, confidentiality and integrity are few main concerns of storing data on cloud and to address these concerns, Convergent Encryption is used along with deduplication technique...
# What is the algorithm used in deduplication?
Dedup Algorithms - Using a Flow Control to Remove Duplicates for a Document Cache. Summary: A flow control that runs a single document at a time before a cache with a decision shape to check if a document with a similiar index key is in the cache. Advantage: This method is easy to understand and design...
# How the deduplication role improves the storage efficiency of the storage infrastructure?
Data deduplication is a vital technique that significantly enhances storage efficiency by eliminating redundant copies of data. It works by storing only a single copy of data, regardless of how often it appears...
# Which of the following encryption techniques is used for securing cloud?
The two types of cloud encryption are symmetric and asymmetric encryption. Enterprises often use a combination of these two encryption methods to build a more comprehensive approach to cloud security...
# What are the different methods of securing data in cloud?
Authentication
We can do digital authentication using credentials, which is usually a password. Other tools here are captcha, patterns, audio recognition, etc. The aim of these is to ensure that an authorised person gets access to critical information in the cloud...
# What is backup optimization deduplication in cloud computing?
Backup deduplication minimizes storage space by detecting data repetition and storing the identical data only once. Deduplication also reduces network load, because duplicates of data previously backed up is not even transferred over the network to storage...
# What is the purpose of deduplication?
Data deduplication is a process that eliminates excessive copies of data and significantly decreases storage capacity requirements. Deduplication can be run as an inline process as the data is being written into the storage system and/or as a background process to eliminate duplicates after the data is written to disk...

# ![User1](https://github.com/user-attachments/assets/e3ad3f11-0808-4ead-8dca-90b60dabe6dd)
# ![User](https://github.com/user-attachments/assets/08bedc6a-69fe-4ce2-8676-9ca50f9da441)
# ![teplatemo_content](https://github.com/user-attachments/assets/842a47da-77c8-41f8-af6b-aa97f560cc69)
# ![templatemo_site_title](https://github.com/user-attachments/assets/b8a3eea0-ae9e-4dfa-b4bf-01d4ce071c21)
# ![templatemo_menu_hover](https://github.com/user-attachments/assets/c7568198-dbe2-4042-9d5d-9d142566b377)
# ![templatemo_menu](https://github.com/user-attachments/assets/55951e79-77fb-45f0-8600-118381900e6c)
# ![templatemo_logo](https://github.com/user-attachments/assets/fcdb2593-5049-4582-a776-a96d22189eb8)
# ![templatemo_list](https://github.com/user-attachments/assets/50feabee-22b9-42aa-a3a1-2c9b0d8ad6fa)
# ![templatemo_image_06](https://github.com/user-attachments/assets/b1fe8c93-025b-4bb4-83a8-7602bd3e26fb)
# ![templatemo_image_05](https://github.com/user-attachments/assets/0bbe399a-8a9e-4e79-83b2-f17f002f692a)
# ![templatemo_image_04](https://github.com/user-attachments/assets/d99c5e54-4bca-45fc-9ec6-f63d3f756795)
# ![templatemo_image_03](https://github.com/user-attachments/assets/b35d9746-922b-4c45-9607-8952f028b5ad)
# ![templatemo_image_02](https://github.com/user-attachments/assets/92f73ec1-8cc0-45cb-b666-bf79f4e646f4)
# ![templatemo_image_01](https://github.com/user-attachments/assets/23184073-91e2-4d1f-b2f5-32449a8640cd)
# ![templatemo_footer](https://github.com/user-attachments/assets/fd847383-32f3-48e1-9730-390f7028a907)
# ![templatemo_content_top](https://github.com/user-attachments/assets/b57433e7-2285-4981-bb26-0999ac87bf6f)
# ![templatemo_content_bottom](https://github.com/user-attachments/assets/3e7b3059-ea47-447a-ba4e-bad98d96216c)
# ![templatemo_button_hover](https://github.com/user-attachments/assets/ef2005f4-2ffe-41e6-9b1a-2f1e3ea32959)
# ![templatemo_button](https://github.com/user-attachments/assets/2754d8e8-4304-4e38-a265-fe2fb5ab5b4e)
# ![templatemo_body](https://github.com/user-attachments/assets/c2e07c09-4ab0-4ef6-947f-7be69bb54f14)
# ![manju](https://github.com/user-attachments/assets/69cd80fa-9699-4c1d-a84a-d7f72a0069e4)
# ![KGC](https://github.com/user-attachments/assets/6d43d8ec-24bd-428a-be32-6b1a7824c108)
# ![images (4)](https://github.com/user-attachments/assets/21d0a801-41c2-4695-a51e-b12660618f9d)
# ![images (4)](https://github.com/user-attachments/assets/4b36382a-d5d4-49d7-bdd4-177cfdb92ace)
# ![images (2)](https://github.com/user-attachments/assets/6b3637b1-9d35-4766-9d78-6a6015770758)
# ![images (1)](https://github.com/user-attachments/assets/6a574aeb-abce-41cb-ae93-4ec8c613bd7c)
# ![images (1)](https://github.com/user-attachments/assets/4cf8c173-060e-478c-89a6-af0c640ba759)
# ![EU](https://github.com/user-attachments/assets/f8caf212-8eb7-4e2c-8ac1-1ff61c507ba5)
# ![download](https://github.com/user-attachments/assets/b879fa43-09be-48bb-b131-3456d02ec33f)
# ![download](https://github.com/user-attachments/assets/afdddf0c-6612-427c-bc8a-1e4f41e37efb)
# ![DO](https://github.com/user-attachments/assets/a4ba17de-dddd-4cae-a2a1-88ff6929ac91)
# ![CSP](https://github.com/user-attachments/assets/1c04c008-db99-4e61-bb7b-e37a084c5889)

# Abstract—Data deduplication is a technique for eliminating duplicate copies of data, and has been widely used in cloud storage
to reduce storage space and upload bandwidth. Promising as it is, an arising challenge is to perform secure deduplication in cloud
storage. Although convergent encryption has been extensively adopted for secure deduplication, a critical issue of making
convergent encryption practical is to efficiently and reliably manage a huge number of convergent keys. This paper makes the
first attempt to formally address the problem of achieving efficient and reliable key management in secure deduplication. We first
introduce a baseline approach in which each user holds an independent master key for encrypting the convergent keys and
outsourcing them to the cloud. However, such a baseline key management scheme generates an enormous number of keys with the
increasing number of users and requires users to dedicatedly protect the master keys. To this end, we propose Dekey, a new
construction in which users do not need to manage any keys on their own but instead securely distribute the convergent key
shares across multiple servers. Security analysis demonstrates that Dekey is secure in terms of the definitions specified in the
proposed security model. As a proof of concept, we implement Dekey using the Ramp secret sharing scheme and demonstrate
that Dekey incurs limited overhead in realistic environments...

#  Convergent Encryption
Convergent encryption [5], [8] provides data confidentiality in deduplication. A user (or data owner) derives a
convergent key from each original data copy and encrypts
the data copy with the convergent key. In addition, the user
derives a tag for the data copy, such that the tag will be
used to detect duplicates. Here, we assume that the tag
correctness property [5] holds, i.e., if two data copies are
the same, then their tags are the same. To detect duplicates,
the user first sends the tag to the server side to check if the
identical copy has been already stored. Note that both the
convergent key and the tag are independently derived, and
the tag cannot be used to deduce the convergent key and
compromise data confidentiality. Both the encrypted data
copy and its corresponding tag will be stored on the server
side. Formally, a convergent encryption scheme can be
defined with four primitive functions..

#  Security Analysis
Dekey is designed to solve the key management problem in
secure deduplication where the files have been encrypted
by utilizing convergent encryption. Some basic tools have
been used to construct the secure deduplication and key
management protocols. Thus, we assume that the underlying building blocks are secure, which include the convergent encryption scheme, symmetric encryption scheme,
and the PoW scheme. Based on this assumption, we show
that Dekey is secure with respect to the security of keys and
data, as detailed below...

# Confidentiality of Outsourced Data at S-CSP
The files have been encoded by the convergent encryption
scheme before being outsourced to the S-CSP. Thus, the
confidentiality of data can be achieved if the adversary
cannot get the secret keys in convergent encryption or
break the security of convergent encryption. Several
security notions, for example, privacy against chosen
distribution attack, have been defined for the confidentiality. Thus, our construction can also achieve the security
for data based on a secure convergent encryption scheme
if the encryption key is securely kept by the user...
# Conclusion
The Secure Deduplication with User-Defined Access Control in Cloud Storage system aims to provide a secure and efficient deduplication technique that allows users to have control over their data access in the cloud. The system proposes an access control mechanism that leverages the attribute encryption standard (AES) and MD5 (Message Digest) algorithms to ensure data deduplication. The proposed solution has been thoroughly evaluated through simulations and experiments, and the results demonstrate its effectiveness in reducing storage overhead and enhancing data privacy while maintaining authorized access to users\' data. These outcomes have significant implications for cloud storage security, offering a promising solution for secure and efficient data deduplication in cloud storage environments. Overall, the Secure Deduplication with User-Defined Access Control in Cloud Storage system makes a valuable contribution to the field of cloud storage security. It provides a practical solution for users who seek to securely store their data and exercise control over its access...

