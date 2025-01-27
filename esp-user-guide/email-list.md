# Email List
View, Sort, Order and Action emails in each folder.

All unread emails in a email folder list are indicated by a blue line to their left hand edge.

Use the Arrow options at the bottom of the emails list to minimize or maximize the preview pane, and to include or exclude the sender / receiver icon from the email details

## Ordering and Sorting Emails
By default the emails in each folder will be ordered by date.

Click on the Date text to open up a menu to change the order the emails are listed in and choose from:
* Date
* Flagged (Marked)
* Status (Read / Unread)

Use the Arrow to decide if the list should be sorted ascending or descending based on the chosen order attribute

## Email View Actions
Hovering over an email in the list will expose several action options:

* **Flagged**. Select the Star to mark the email as flagged. You may want to revisit these later or order the email list by those which are Flagged
* **Multi-Select**. Select the Empty Box icon to expose a number of actions which ca be performed against all emails which are selected, see Multi-Select Actions section for more details
* **Delete**. Select the Trash Can icon to delete and move the email into the Deleted email folder
* **View**. Select the Arrow in Box icon to open and view the email in a full window

## Multi-Select Actions
Selecting the Empty Box icon on one or more emails in the list will expose a multi-select menu in the toolbar at the top of the list, the available actions are:

* **Move Emails to Another Folder**. Select the folder icon and from the drop down choose which folder to move the emails too.
* **Read**. Select the eye icon to mark the emails as Read
* **Unread**. Select the eye with line icon to the emails as Unread
* **Delete**. Select the trash can icon to delete the emails and move them to the deleted folder

## Email Preview and Actions
With an email highlighted in the list, the body of the email will be shown in the preview pane to the right of the list. Multiple actions are available to you from the preview pane.

* **Reply**. Select the left directed arrow icon to open the email composer with the 'From email address from the email added to the To email address for the reply
* **Forward**. Select the right directed arrow icon to open the email composer
* **Delete**. Select the trash can icon to delete the email and move it to the deleted folder
* **Move**. Select the folder icon and drop down to choose a folder to move the email too
* **HTML View**. Select the A icon to toggle between a plain text view and an HTML preview of the email content
* **Mark as Read**. - Select the eye icon to mark the email as read

Use the Sideways Arrows icon to expand the More information panel in the preview pane

Showing:
The To email address
Any Related Media of the email

## Failed Delivery on Email
An email that failed to be delivered is shown as a red triangle and count of unread messages in sent items. Note that this will show on all previously failed deliveries, not just new items.

* If an email is successfully sent to all recipients it is moved into the Sent Items folder and Marked as Read.
* If an email is not sent to any of the specified recipients Hornbill will attempt to retry (this happens upto 9 times with retry period getting longer each time, Starts at 1 minute , 5 minutes, 30 minutes, 60 minutes, 120 minutes, 240 minutes, 480 minutes, 960 minutes, 1440 minutes). The email at this point will remain in the outbox.
* If email is still not sent to any of the specified recipients after all 9 tries it is moved into the Sent Items, marked as Failed and Unread. The counter against the Sent Items is increased by 1 and the red triangle shown.
* The failed message can be found by going into the Sent Items, clicking the order by and choosing Status. Then the arrow to get all unread at the top.
* The failed delivery recipient is shown as a red mail icon (If your email had multiple recipients several may be green with 1 or more red.)
* If you click on the Red Mail Icon and choose Delivery Status you will be able to see the full audit trail of the attempts to deliver the message.
* There may be many reasons why an email has failed to deliver (From misconfiguration to non existent sender.) However once you have reviewed the failed email and decided the root cause you can highlight the email and choose Mark As Read, removing the item from the count of failures.

<!-- https://wiki.hornbill.com/index.php?title=Emails_List -->