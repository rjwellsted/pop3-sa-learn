# pop3-sa-learn
Train spamassassin from a pop3 mailbox

This is designed to overcome the removal from Microsoft Exchange (2007 and more recent)
to access Public Folders via IMAP.

To use:
setup a user in the organisation with a mailbox and email address
e.g. user Spam Mailbox spam@organisation.com  and instruct users to forward any
spam emails to this user/address.  The system administrator should then regularly run this program
e.g. hourly in order to train spamassassin.
