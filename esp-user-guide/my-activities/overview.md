# My Activities
Activities are your to-do list. Activities can be created manually from your activities views and from entity views in installed line-of-business applications; they can also be created automatically by the workflow in a business process.

## Viewing activities
Activities can be viewed and completed in many different locations.

* **List view**. View your activities in a traditional view, see progress, choose displayed columns and sort the order of activities by the different columns.
* **Board view**. View your activities on boards. Create and configure multiple board views, setting custom lists and criteria that dynamically show activities matching the list criteria.
* **Calendar view**. View your activities in a calendar view, with options to view daily, weekly, or monthly.
* **My Activities Sidebar**. Get quick access to all of your activities by clicking My Activities (the circled checkmark) in the right hand sidebar.

## Activity types
Activities can come in various forms but are summarized as follows:

* **Manually created activities**. Each user can create their own activites or assign activites to other users.
* **Workflow Human Tasks**. Users can be assigned a task as part of an automated workflow.  
* **Authorizations**. Authorizations can be assigned to users as part of an automated workflow. Authorizations can't be manually created.

## Activity attributes
* **Title**. The Activity name which is prominantely displayed in the different views to indentify the activity.
* **Description**. Details relating to what need to be completed in the activity.
* **Personal**. Option to mark the activity as private. Users that have the right to view your activities will not see these in their list.
* **Schedule**. Option to set a schedule for the reoccurrence for the activity.
* **Category**. Select the Category for the Activity, and in turn it's defined outcomes - you can create your own Activity Categories and custom outcomes from the Manage Activity Categories link in the related articles section.
* **Priority**. Set a priority for the activity.
* **Assign To**. Select if the activity should be assigned to a named user, role or group and select the relevant user, role or group accordingly:
    * **Me**. Assign the activity to yourself. Optionally choose which of the groups you are a member of, you would also like this activity assigned too.
    * **User**. Assign the activity to a user. Optionally choose which of the groups the user is a member of, you would also like this activity assigned too.
    * **Group**. Assign the activity to a group. Optionally choose a user in the group, to assign the activity to.
    * **Role**. Choose the role to assign the activity too, all users with that role will be assigned the activity.
* **Starts On**. Select when the activity is required to start - select a date and time or choose the All Day option.
* **Due On**. Select when the activity should be completed by. With a Due Date and time selected, an option to set reminders for the assignee and owner will be presented.
* **Add Checklist**. Create a checklist and checklist items which need to be completed as part of the activity.
* **Enforce Completion**. Mark if the checklist must be complete before the activity can be completed.
* **Attach File**. Optionally attach files relevant to the activity you are creating.

## Scheduled activities
This list displays all of the user's scheduled activities. A scheduled activity is an activity that has been scheduled to be automatically added to the activity list using a defined recurrence pattern.

* Delete a scheduled activity.
* Edit the recurrence pattern.
* Stop or start the recurrence of an activity.
    :::tip
    If a scheduled activity has been stopped for some time, and the Next Run displays a time in the past, the activity will be run as soon as it is re-started. By clicking on the scheduled activity, the next run date can be modified before re-starting the activity.
    :::
* Edit the scheduled activity.

## Manage categories
Each activity has the option to set a category to help with grouping similar activities which can be used to help organize views, lists, and reports.

### How to access
The Manage Categories view is only available to users with specific roles or rights.
* The Admin Role.
* A custom role that includes the Core application admin right `Manage Task Categories`.

## Manage templates
Activity Templates can be set up to provide users with selectable, pre-defined templates that are used for common activities. This ensures that all users that perform a particular activity are using the same configuration. Templates are only available to use when manually creating an activity.

### How to access
The Manage Templates view is only available to users with specific roles or rights.  
* The Admin role.
* The Activities Template Manager role.  
* A custom role with the Core Application right `canManageTaskTemplates`