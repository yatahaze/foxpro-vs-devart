I can't run UPDATE queries to the ARCUST01 database.

- The code is demonstrated in the `index.php` file.
- It outputs to `results.txt`.
- The database in question is under the `/db` folder.

The problem lies with the connection settings. We can't run updates to this table with "Native" IndexOnReading, but most other tables won't let us use "Local".

- "VisualFoxPro" and "Native" doesn't work.
- "VisualFoxPro" and "Local" works.
- "FoxPro2" and "Native" doesn't work.
- "FoxPro2" and "Local" works.