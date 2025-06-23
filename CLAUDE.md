
##Notification

**Condition**: When Claude Code completes a task, or returning regular messages.

**Action**: To display a notification, execute the following command:

\bash
osascript -e "display notification \"${message}\" with title \"Claude Code\" sound name \"Glass\""
 ￤Execute the command to display the notification.

Here, \"${message}"\ is determined based on the content that Claude Code needs to notify the user about.

