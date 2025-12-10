---
url: https://wiki.hornbill.com/index.php?title=Policies
---

# GRC Policies
Policies are generally established by a board of directors of an organization to set boundaries under which the organization should operate to to keep the company on track and operating efficiently. 

## Creating a Policy

* **Policy**

Name of the policy

* **Type**

The type of policy. (This list can be modified by a user with the GRC Administrator Role under GRC Simple Lists)

* **Objective**

The objective of the policy

* **In-use Target**

The target date for when this policy becomes in-use

* **Next Review Date**

The date when this policy will be up for review

* **Life Cycle**

Life Cycles are a collection of automated workflows. This list contains life cycles that only relate to Policies. A life cycle can only be selected at the time of creation.

* **Owner**

The owner of this policy. This will default to the user that created the policy

* **Risk Register**

Select to automatically create a _Risk Register_ or select that a _Risk Register_ is not needed. Automatically created _Risk Registers_ are located in the Operational Risk Registers within Risk Management. A link between the two are maintained.

  
### Policy Document Management

* **Manage In**

* **_Maintain Document Here_**

Once the Policy is created an editor is provided to write and maintain the Policy Document within the policy record.

* **_Maintain Document in Document Manager_**

This option will require Hornbill Document Manager to be installed. A document will first need to be created in Document Manager and then linked from the Policy record

* **_Maintain Document with External Reference_**

A field is provided where a URL to an external document can be specified.

## Manage a Policy

### Activity

The Activity Stream is provides to allow discussions to take place about the policy. Users are able post notes, comments, discussions, and mention other users.

### Details

The majority of information within the Details is the information that was originally captured when the Policy was created. Two additional fields are available after a Policy is created 

* **Status**

The status field allows you to select the current state of the Policy. The default statuses include Implementing, In Place, In Use, Planning, Retired, and Under Review. These statuses can be managed within Administration within the Simple Lists configuration

* **Authorizing Users**

The users that can participate in authorizing changes or progress of this policy

### Document

This option is only visible if you have chosen to manage the Policy Document within the Document Record. The option for selecting where to manage the document is found under the Details section of the policy. An inbuilt editor is provided to allow you to document the Policy.

### Risks

This are the list of Risks that are associated to this policy.

### Statements

Policy Statements are a collection of plans and intentions that support the Policy. For example if there was a Password Policy, a Policy Statement might be created for Active Directory minimum password length or password complexity. From this view you can create a new Policy Statement which will be automatically linked to this policy.

### Tasks and Reviews

Here, tasks and reviews can be manually created or they will be automatically created as part of a Life Cycle workflow. 

* **Filter by Status**

This allows you to filter by the status of the task or review, using the statuses Open, Completed, Authorized, Rejected, Expired, or All.

* **Filter by Type**

This allows you to filter the list by Tasks, Reviews, or both.

* **Create New Review**

This option allows you to create a scheduled review for this policy

* **Create New Activity**

This option allows you to create a task for this policy

### Attachments

Files such as Word Docs, PDFs, and images can be attached to the Policy. This could include any documentation that supports the policy.

### Lifecycle History

If you are running a Life Cycle workflow on your Policy, this area will show the outcomes of the previously complete automations.