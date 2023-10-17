# LuminescenceWorkshop
1. Login to your github account

2. Enter AbbyKremer/LuminescenceWorkshop in the search box

3. Click on the down arrow on the Fork button (right hand side of the website) <br>

4. Create a new fork or clone. The next set of instructions assumes that created a new fork. Save it as a new repository in your github account

5. Go to command prompt

6. type git clone HTTPS address. You can get the HTTPs address by clicking on Code and copying
the address from the HTTPS tab

7. type cd foldername to go to the folder

8. type git init

9. type git branch branchName

10. type git checkout branchName

11. Use a text editor of your choice to add the line "My name is {Your Name}" to the last line in the file workshopAttendees.txt.
Name should be entered in the format FirstName_LastName

12. type git add .

13. type git commit -m "Commit message"
14. type git push --set-upstream origin branchName

15. You will be asked to enter your login id and personal access token.
See https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
for more information

16. Go to your github account and create a pull request to request that the change from your forked repo
be merged to the parent repo (AbbyKremer/LuminescenceWorkshop)

17. I will then receive a notification to merge your change into the parent repo

Adapted from: https://github.com/abhaysamantni/PythonReview/blob/master/InClass%20Git%20Exercise.html
