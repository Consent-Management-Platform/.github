# Consent Management Platform

Note: This is an experimental side-project in early design/development.

## Project proposal
<i>
<p>The Consent Management Platform provides scalable, open-source services designed to empower companies to efficiently manage and enforce customer data privacy preferences.</p>

<p>In today’s regulatory landscape, compliance with strict privacy regulations such as the EU’s General Data Protection Regulation (GDPR) has become an imperative.  By embedding privacy protections across business processes, organizations can stay ahead of evolving regulations and build customer trust.</p>

The Consent Management Platform offers a suite of tools tailored to meet evolving business needs:
* **Customizable Consent Management**: Manage and customize consent agreements between users and services, ensuring compliance with regulatory requirements and company policies.
* **Querying Capabilities**: Query service- and user-specific consents to enforce individual preferences, enhancing data privacy governance.
* **Comprehensive Audit Trail**: Maintain a detailed audit history of all consent-related actions, including creation, updates, expiry, and revocations. This provides transparency and accountability for both businesses and their customers.

Benefits:
* **Scalability**: Our platform offers scalable solutions suitable for businesses of all sizes, accommodating growth and evolving needs.
* **Security**: All data is encrypted in transit and at rest, and stored using zero-access encryption so that we cannot read any of your data or share it with third parties.
* **Transparency**: All our service and infrastructure code is open-source and publicly hosted on GitHub for customers to view and suggest improvements to.
</i>

## Project resources

Consent Management Platform design:
* High-level design doc: https://docs.google.com/document/d/1z-e3ybppuJMujcLjY8FOCvQ2yB4HrFdymSMctr17kBY/edit?usp=sharing
* Design artifacts: https://github.com/Consent-Management-Platform/consent-management-design

AWS infrastructure resources:
* CDK package defining infrastructure as code: https://github.com/Consent-Management-Platform/consent-management-api-cdk

Consent Management API resources:
* API documentation: https://consent-management-platform.github.io/consent-management-api-models/v1/docs.html
* API models: https://github.com/Consent-Management-Platform/consent-management-api-models
* API service code: https://github.com/Consent-Management-Platform/consent-management-api

Consent History resources:
* API documentation: https://consent-management-platform.github.io/consent-history-api-models/v1/docs.html
* API models: https://github.com/Consent-Management-Platform/consent-history-api-models
* API service code: https://github.com/Consent-Management-Platform/consent-history-api
* Consent history ingestor service code (automatically syncs consent changes to consent history DB): https://github.com/Consent-Management-Platform/consent-history-ingestor

Consent Auto Expiry resources:
* Consent expiry processor service code: https://github.com/Consent-Management-Platform/consent-expiry-processor
