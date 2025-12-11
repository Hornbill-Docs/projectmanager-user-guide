# Project Overview
The Project Overview gives a stakeholder a quick view of the current state of the Project. At a glance, you are able to see the milestones and some key Project information. **Heads Up Display** \- If you are running a business process against your project, the heads up display lets you know where you are in the process. **Project Milestones** \- Key events over the course of the project's lifecycle. **Project Indicators** \- Widgets containing key information regarding overall project progress and RAG status. 

## Heads Up Display
A Heads Up Display represents a business process that is running against the project. 

* A business process can consist of multiple stages and can be configured in the Hornbill Admin Tool.
* Business processes can be applied to project templates which can in turn be applied to new projects.
* The project business process can be manually progressed using the green **Continue Business Process** button.

  
## Project Milestones
Milestones are key points in a project, they can be used to indicate if the project work is on track to meet the Completion date for the Project. 

* A project can have multiple Milestones, each with their own due dates.
* Project Tasks can be created and linked as **Counting towards** Milestones. As **linked** tasks are completed, the Milestones percentage progress will automatically be increased.

### Adding Milestones

Use the **+** Icon to add a new project milestone

* **Name** \- Display name for the Milestone
* **Description** \- Details of the Milestone
* **Due Date** \- The Date the Milestone should be completed
* **Progress** \- The percentage progress of the Milestone
* **Status**

* **To Do** \- Not Started
* **In Progress** \- Work towards the Milestone has started but is not yet complete
* **Completed** \- The Milestone has been Achieved

### Edit Milestone

Click on the edit icon for a Milestone to edit it's Percentage Progress, change it's Status or due date and if required delete it.

### Milestone List

Change the Display order of the Milestones on the **Overview** by using the **Arrows** to move the Milestones up and down the list, this is purely for appearance. 

### Notification

The **Project Manager** for the project will see an extra option when creating or editing a milestone, this is an option to receive a **Hornbill** notification when the milestone is marked as **completed**.

* By default this is set to **off**
* Project Manager Milestone completion notifications can also be set per milestone in project templates
* Manage the default value for this notification in the settings using the following app setting: **app.com.hornbill.projectmanager.milestones.notification.notifyProjectManagerOnCompletion**

### Administration

When Milestones are created, edited or completed all actions are audited and recorded in the **Audit History** tab on each Milestone view, as well as against the overall project Audit History.  

## Project Indicators

### Introduction

Project Indicators provide a visual status update at a glance.

* Project RAG Status - The overall project RAG Status. The Harry Hornbill image can be turned on/off using the application setting **app.com.hornbill.projectmanager.project.projectRagStatus.harryHornbill**.
* Project Progress - The overall project progress in terms of percentage (0-100).
