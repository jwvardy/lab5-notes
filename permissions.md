CHMOD: short for "Change Mode" changes a file's permissions. 
This changes a user's permissions to either: read, write, or execute a certain file.
A certain example of this is the format of: "drwx..."
"d" - means is it a directory
"r" - means it has the permission to Read
"w" - means it has the permissions to Write
"x" - means it has the permission to eXecute
If no permissions is allowed the corresponding letter would be replaced by a "-".
It typically follows a pattern, the first "rwx" is for the Owner of the file, followed by a second set of
"rwx" which gives group permissions. Lastly followed by a third "rwx" which gives permissions to everyone
else outside of the owner and group.
 A full example: "drwxr-xr--"
Also, it can look like this: "644"
"6" - means it has the permissions to Read and Write.
"4" - means it has the permissions only to Read.
The second 4 means the same thing as the first.
Following the same pattern as before, the first number is meant to represent the permissions of the owner,
followed by the group and then everyone else.
Another example: "755"
"7" - means it has the permissions to Read, Write, and Execute.
"5" - means it has the permissions to Read and Execute the file.
