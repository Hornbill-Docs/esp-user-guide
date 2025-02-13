# Email list
View, sort, order, and action emails in each folder.

Unread emails in an email folder list are indicated by a blue line at their left-hand edge.

Use the arrow options at the bottom of the email list to minimize or maximize the preview pane, and to include or exclude the sender/receiver icon from the email details.

## Ordering and sorting emails
By default, the emails in each folder are ordered by date.

Click on the date text to open a menu; you can change the order the emails are listed in. Choose from:
* Date
* Flagged (Marked)
* Status (Read/Unread)

Use the arrow to sort the list in ascending or descending order based on the chosen order attribute.

## Email view actions
You can hover over an email in the list to expose several action options:

* **Flagged.** Select the star to mark the email as flagged. You may want to revisit a flagged email later, or order the email list by those which are flagged.
* **Multi-Select.** Select the Empty Box icon to expose a number of actions that can be performed against all selected emails. See [Multi-select actions](/esp-user-guide/email-list#multi-select-actions)  for more details.
* **Delete.** Click **Delete** to move the email to the Deleted email folder.
* **View.** Click the Arrow in Box icon to open and view the email in a full window.

## Multi-select actions
Clicking the Empty Box icon on one or more emails in the list exposes a multi-select menu in the toolbar at the top of the list. The available actions are:

* **Move Emails to Another Folder.** Click the folder icon, then from the dropdown choose which folder to move the emails to.
* **Read.** Click the eye icon to mark the emails as read.
* **Unread.**. Click the eye-with-line icon to the mark the emails as unread.
* **Delete.** Click the trash can icon to delete the emails and move them to the Deleted folder.

## Email preview and actions
With an email highlighted in the list, the body of the email will be shown in the preview pane to the right of the list. Multiple actions are available to you from the preview pane.

* **Reply.** Click the left-directed arrow icon to open the email composer with the From email address from the email added to the To email address for the reply.
* **Forward.** Click the right-directed arrow icon to open the email composer.
* **Delete.** Click the trash can icon to delete the email and move it to the Deleted folder.
* **Move.** Click the folder icon, then from the dropdown choose a folder to move the email to.
* **HTML View.** Select the A icon to toggle between a plain-text view and an HTML preview of the email content.
* **Mark as Read.** Select the eye icon to mark the email as read.

Use the sideways-arrows icon to expand the More Information panel in the preview pane.

Showing:
* The To email address
* Any related media of the email

## Failed delivery on email
An email that failed to be delivered is shown as a red triangle and count of unread messages in sent items. Note that this will show on all previously failed deliveries, not just new items.

* If an email is successfully sent to all recipients it is moved into the Sent Items folder and Marked as Read.
* If an email is not sent to any of the specified recipients Hornbill will attempt to retry (this happens upto 9 times with retry period getting longer each time, Starts at 1 minute , 5 minutes, 30 minutes, 60 minutes, 120 minutes, 240 minutes, 480 minutes, 960 minutes, 1440 minutes). The email at this point will remain in the outbox.
* If email is still not sent to any of the specified recipients after all 9 tries it is moved into the Sent Items, marked as Failed and Unread. The counter against the Sent Items is increased by 1 and the red triangle shown.
* The failed message can be found by going into the Sent Items, clicking the order by and choosing Status. Then the arrow to get all unread at the top.
* The failed delivery recipient is shown as a red mail icon (If your email had multiple recipients several may be green with 1 or more red.)
* If you click on the Red Mail Icon and choose Delivery Status you will be able to see the full audit trail of the attempts to deliver the message.
* There may be many reasons why an email has failed to deliver (From misconfiguration to non existent sender.) However once you have reviewed the failed email and decided the root cause you can highlight the email and choose Mark As Read, removing the item from the count of failures.

<!-- https://wiki.hornbill.com/index.php?title=Emails_List -->