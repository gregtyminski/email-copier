# email-copier

Jupyter script that copies all emails from source IMAP mailbox to destination IMAP mailbox.

## Known limitations

* IMAP protocol supported only
* all emails are transfered (no delta); if destination mailbox contains the same messages, they will be duplicated.
* all emails in destination mailbox are marked as "unread"

## Known issues

* unknown at the moment