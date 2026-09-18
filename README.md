# rustdeskdb
Standalone Rustdesk user database
For those standalone self-hosted Rustdesk server users, having a Rustdesk desktop app saving, searching and retrieving user information and user ID is very handy. This app is created in APMS in the Lua language.

Updated September 2026

The Rustdesk User Database is for standalone, self-hosted Rustdesk solutions, where an accessible list of client connection information can be easily located, added to, and updated.

This app should preferentially be extracted to a root drive such as, for example, C:\RustdeskID\ or F:\RustdeskID\
 
When entering new user information, use only alphabetical letters. Do not use symbols or apostrophes as the SQLite database cannot accept these.

After having searched and selected a client from the database, you may then click on the selected user information field (username or Rustdesk ID) and the data in that field is automatically copied to the clipboard. This then enables easier pasting into the Rustdesk client when initiating a remote connection.

When closing the app using the EXIT button, the database is automatically backed-up to a backup folder. The database is also backed up to the user's document folder.

The database is in SQLite3 format. After exiting the app, the database can then also be accessed by third-party utilities, such as Letos, for conversion to CSV format. The CSV format can then be saved/converted into other formats such as Excel XLSX formats, or imported into another application/program.

Please note that the Rustdesk User Database app is self-signed, indicating that it was not tampered with from when originally compiled and downloaded. Please note that self-signed certificates may not be recognised by your Windows computer; however, the certificate can be added to the appropriate local certificate store on your PC to avoid false alerts.

There is no need for installation of the Rustdesk User Database public version of this software which is downloaded within a ZIP archive. Please extract all files into a clean folder/directory. To mitigate or prevent data loss, consider backing up this entire folder structure to another location from time to time.

There is no malware, spyware, phone-home, or data exfiltration of any sort in this application. This software app remains the property of Classic IT Support, and may not be on-sold, decompiled or reverse engineered. You are licensed to use this one one main computer.

This software was created by Classic IT Support. Copyright, Classic IT Support, 2024-2026

Email: support@classicit.net
Web: https://www.classicit.net

