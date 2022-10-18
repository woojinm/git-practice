### ChangingPermissions

777: (rwxrwxrwx) No restrictions on permissions. Anybody may do anything. Generally not a desirable setting.

755: (rwxr-xr-x) The file's owner may read, write, and execute the file. All others may read and execute the file. This setting is common for programs that are used by all users.

700: (rwx------) The file's owner may read, write, and execute the file. Nobody else has any rights. This setting is useful for programs that only the owner may use and must be kept private from others.

666: (rw-rw-rw-) All users may read and write the file.

644: (rw-r--r--) The owner may read and write a file, while all others may only read the file. A common setting for data files that everybody may read, but only the owner may change.

600: (rw-------) The owner may read and write a file. All others have no rights. A common setting for data files that the owner wants to keep private.


-------------

### Text Editors

vi, vim:	The granddaddy of Unix text editors, vi, is infamous for its obtuse user interface. On the bright side, vi is powerful, lightweight, and fast. Learning vi is a Unix rite of passage, since it is universally available on Unix-like systems. On most Linux distributions, an enhanced version of vi called vim is provided in place of vi. vim is a remarkable editor and well worth taking the time to learn it.

Emacs:	The true giant in the world of text editors is Emacs originally written by Richard Stallman. Emacs contains (or can be made to contain) every feature ever conceived of for a text editor. It should be noted that vi and Emacs fans fight bitter religious wars over which is better.

nano:	nano is a free clone of the text editor supplied with the pine email program. nano is very easy to use but is very short on features compared to vim and emacs. nano is recommended for first-time users who need a command line editor.

gedit:	gedit is the editor supplied with the GNOME desktop environment. gedit is easy to use and contains enough features to be a good beginners-level editor.

kwrite:	kwrite is the "advanced editor" supplied with KDE. It has syntax highlighting, a helpful feature for programmers and script writers.	

-----------------------------
### ChangingPermissions
Changethepermissionofafile“word.txt”thatonlytheowner(you)canreadandwrite,  butalltheothers(includingothersinthegroup)canonlyreadit.Noexecutionisneeded  forallusers

----------------------------
### Superuser
•Asuperuserhasallsystemadministationauthority.  
•Somecommandsneedsuperuser’sprivilleges.  
•Put“sudo”beforethecommandifyouareasuperuser.