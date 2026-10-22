# Trip Receipts data (private)

The Trip Receipts iPhone app writes `transactions.json` here after every change
(Setup → Website). The website reads it with a read-only token.

Keep this repo **private**: the file holds the original bank SMS for each payment.
Every sync is a commit, so the history keeps older snapshots too — including
personal payments the phone has since deleted. Delete the repo to wipe it all.
