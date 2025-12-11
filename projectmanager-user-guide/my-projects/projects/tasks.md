# Project Tasks
Both Tasks and Summary Tasks are available for each project within Hornbill Project Manager. Tasks represent the individual units of work whilst summary tasks allow tasks to be grouped together in phases of work. Within any project, it is always desirable to be able to visualize the tasks and the included phases of work. Hornbill Project Manager achieves this by providing two default gantt charts for tasks/summary tasks. 

## Tasks

### Introduction

Tasks are a key aspect of all projects. They can be created as placeholders with only a name required, or they can be created as full tasks and assigned accordingly.

* Plan, schedule and assign tasks that are required to fulfill your project.
* Link tasks to project milestones to count towards their completion.
* Associate tasks to project risks to better manage each risk.
* Group tasks under Summary Tasks to create phases of work.
* Record resource time and effort (Requires access to Hornbill Timesheet Manager).
* By Default Project Manager's are added as task **owners**, allowing them to complete or reassign project tasks alongside the **assigned** task Stakeholder.
* Project Tasks can only be assigned to Project Stakeholders

### Creating Project Tasks

Use the **+** icon to add a new Project Task

* **Task Name** \- The name for the task, which will be displayed in project views.
* **Description** \- The details for the task.
* **Start Date** \- The date the task is due to start (defaults to today).
* **Owned By** \- The Project Stakeholder who owns the task.
* **Assigned To** \- The Project Stakeholder who the task is assigned to.
* **Counts Towards Milestone** \- Optionally decide if the task contributes to the achievement of a specific project milestone.
* **Depends on Task** \- Notionally specify another task that this task will depend on (more functionality in this area to follow).
* **Part of Summary Task** \- Optionally link the task to a summary task (task phase).
* **Related to Project Risk** \- Optionally link the task to a project risk.
* **Due Date** \- The date the task is due to be completed.

* If the task has been linked to a project milestone, the due date will automatically be set to the due date for the chosen milestone

* **Notify Project Manager on Completion**

* The **Project Manager** for the project will see an extra option when creating or editing a task, this is an option to receive a **Hornbill** notification when the task is marked as **completed**.

* By default this is set to **off**
* Project Manager Task completion notifications can also be set per task in project templates
* Manage the default value for this notification in the settings using the following app setting: **app.com.hornbill.projectmanager.projectTasks.notification.notifyProjectManagerOnCompletion**
* Select to notify the Project Manager once the task is completed

### Updating & Completing Project Tasks

* **Progress** \- Manually slide the progress indicate, so show in percentage terms how near to completion the task is
* **Timeline** \- Post and or Comment on the task

* **Follow** \- Select the **\+ Follow** button receive updates posted to the task timeline on your News Feed

* **Dates and Ownership** \- Edit the start, due dates assignee and or owner attributes for the task
* **Counts Towards Milestone** \- Optionally decide if the task contributes to the achievement of a specific project milestone, adding a task to an existing Milestone will automatically re-calculate the milestones progress %.
* **Part of Summary Task** \- Optionally link the task to a summary task (task phase).
* **Related to Project Risk** \- Optionally link the task to a project risk.
* **Update** \- Select **Update** to commit the changes to the task (Only Task Owner, or Task Assignees can update their tasks)
* **Complete** \- Select this option to mark the task as complete

### Administration

The creation, updating, editing and completion of project tasks will be recorded in the task audit history tab for review and searching, as well as being written to the overall project audit history.

  
## Summary Tasks

### Introduction

Summary tasks allow multiple tasks to be grouped together as phases of work

* Group multiple tasks under a single summary tasks
* Visualize summary tasks on the provided gantt charts.

### Creating Summary Tasks

Use the **+** icon to add a new Summary Task

* **Name** \- The name for the summary task, which will be displayed in project views and on gantt charts.
* **Description** \- The details for the summary task.

### Updating Summary Tasks

* **Name & Description**.
* **Update** \- Select **Update** to commit the changes to the summary task.

The creation and editing of summary tasks will be recorded in the summary task audit history tab for review and searching, as well as being written to the overall project audit history.

  
## Gantt Chart (Tasks)

This view allows the project tasks and summary tasks to be visualized in a gantt chart.
* Add and remove summary tasks with a simple toggle switch.
* Change the theme of the chart using the drop down menu on the top right hand side of the screen.
* 'Snapshot' the gantt chart. This allows you to create a visual historical timeline of task progress and activity.
    
## Gantt Chart (Tasks by Assignee)

This view allows the project tasks to be grouped by assignee and visualized in a gantt chart.
* Change the theme of the chart using the drop down menu on the top right hand side of the screen.
* 'Snapshot' the gantt chart. This allows you to create a visual historical timeline of task progress and activity.