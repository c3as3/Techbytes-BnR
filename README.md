# Techbytes-BnR
Backup and Restore Tool
Data Transfer


Funtion = Back up
Type WSID
Type Username
Tool will use the provided information to fill the paths of the pull Folders


>>Copy data from specified folders
>>Save it to a folder on your shared drive with username as the Parent Folder



***Have user log in to create user profile on new drive.***



Function = Restore
>>Fetch username Parent folder
>> Copy each child directory folder to the correct location on the new drive
>>Accept all conflicts
>>Check for errors
>>If errors > list errors
>>If successful > generate success message



Important paths to back up


\\WSID\c$\users\USERNAME\appdata\local\microsoft\office
\\WSID\c$\users\USERNAME\appdata\local\microsoft\Outlook

\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Office
\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Templates
\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Signatures
\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Word
\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Excel
\\WSID\c$\users\USERNAME\appdata\Roaming\Microsoft\Outlook

\\WSID\c$\users\USERNAME\Desktop
\\WSID\c$\users\USERNAME\Documnents
\\WSID\c$\users\USERNAME\Downloads
\\WSID\c$\users\USERNAME\Favorites
