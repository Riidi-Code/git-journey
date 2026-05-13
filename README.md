Im learning how Git and GitHub works. Here is the clear picture of what is going on as of right now.

<img width="1019" height="435" alt="Git Local and Cloud" src="https://github.com/user-attachments/assets/6fa44c26-f07d-44fd-a19d-ba3ba67dcc32" />

If u want to clone GitHub Project: use git clone and then the HTTPS Url, that is given at the project.

If u want to find out, whether any of the files (that u cloned) have been changed/updated,, just simply write (within that folder): git status

PS: creating a new folder in Terminal (whether inside another folder or just "Downloads") is "mkdir"  and creating new txt file is simply done through "touch [name].txt"
with "cd.." you can move backwards (back to the beginning) from Folder to Folder and with "cd ../" you can move back to the beggining fully like Desktop/Downloads etc areas

PPS: When you would do a git status after adding the new files/folders within that folder, you will see that git tells that these are untracked files (since they were not created within github, but manually/automatically by us within a folder/computer) that means we would have to now also upload/add all of our newly made files/folders into the GitHub repository, so theyre recognized as One. For that (in order to upload all of these files/folders) just write "git add --all" and all of them are uploaded. (but not commited!)

!!! if u wanna reverse that "git add -all" action just write "git reset" after it, and everything will be reset.!!!

!!!! if u wanna just add a single file (and not the whole project/directory with the folder) then just go into the folder itself and write "git add ." this will add just the files that are within that sub-folder but without including the other Files that are also in the Main folder itself!!!

Writing "git add *" also uploads just the newly/modified files but not the deleted ones.

commit = is confirming and saving the changes permanently.

git commit -m "[write whatever u want]" lets u commit the changes and comment as well.
git reset HEAD~ will make it possible that u reset the changes and savings of the last commit.
git reset --hard will revert all of the changed/deleted files if you have deleted them.
git rm -r [Folder name] will delete the folder but not its content within it.

git log lets you view the full commit history.
