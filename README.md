# Gmail: Continuously Delete old emails automatically (Turn filters into automatic continuous scripts)

Automatically deletes old emails that are not marked important, and that are not chats. Also an option to ensure that
deleted emails must match specified labels.

If you have a more complicated query, you can try to use [gmail search operators](https://support.google.com/mail/answer/7190?hl=en), 
and replace the "search" variable in Line 60 with your query string. 

## Get started

- Create a new Google Apps Script at [https://script.google.com](https://script.google.com)
- Overwrite the placeholder with the javascript below
- Update the following constants:
  - `LABEL_TO_DELETE`: the label that should be have old messages deleted, uncomment if desired
  - `DELETE_AFTER_DAYS`: the age of messsages after which they will be moved to trash (default 1 year)
  - 
- Save the script, then run:
  - `Initialize`
  - `Install`

If you ever want to remove the script, run `Uninstall` to remove any left over triggers.
