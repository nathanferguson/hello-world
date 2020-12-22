## 'Open in new window' button code

```<i class="fa fa-external-link" aria-hidden="true" title="opens in a new window"</i<span class="sr-only"opens in a new window</span```

## D2L Bugs

- Inserting proxy URLs via the WYSIWYG editor results in additional "%" characters added that break said URLs.
Example: Inserting the following functioning URL into a Discussion:
https://proxy.ccis.edu/login?url=https://fod.infobase.com/PortalPlaylists.aspx?wID=19180&xtid=111630&loid=405553

Is transformed into the following broken URL:
https://proxy.ccis.edu/login?url=https%3a%2f%2ffod.infobase.com%2fPortalPlaylists.aspx%3fwID%3d19180&amp;xtid=111630&amp;loid=405553

When selecting Question Library items from Copy Components, the interface no longer allows de-selecting said items. 

## Quiz Questions

### Pulling via Respondus

Respondus's Retrieval function cannot pull entire quizzes if they contain subfolders, e.g. a Midterm or Final Exam quiz that contains subfolders for each chapter or section.

Workaround: Import/copy the quizzes from the course into your sandbox and then manually add each section into folders in your Question Library. Then retrieve each section via Respondus.
1. In your sandbox: Edit Course (under More More Tools), then Import / Export / Copy Components Copy Components from another Org Unit (Search for offering) Search for the course Select Components Quizzes (Select the quizzes to copy)
2. Now from your sandbox's Question Library (in Quizzes Question Library), Import Browse Existing Questions then from Source menu (upper-right) select the desired Quiz select sections and click Add
3. Then from Respondus, use Retrieval to pull the question sections. If your sandbox doesn't appear in the list, go to Classlist (under More More Tools) Add Participants (Add existing users), search for `Respondus` and set its role as `Respondus`, then **Enroll**

Note: If Respondus fails when importing a quiz section, check that the questions are formatted properly, e.g.questions include s, T/F are not left blank, etc.

## Import/Copy Question Library Test Banks

D2L's import/copy function does not properly copy Question Library items when they are organized in folders/subfolders. Instead, D2L dumps all of the questions into the root folder of the Question Library (Quizzes Question Library).

Workaround: Import/copy each question library folder individually from your sandbox. Then move the questions from the Question Library root folder into the appropriate folders/subfolders.
1. In your sandbox, upload the test banks and organize them in folders/subfolders in your Question Library as desired.
2. Now from the course you are copying the Question Library to: Edit Course (under More More Tools) Import / Export / Copy Components Copy Components from another Org Unit (Search for offering) Select Components 

## Importing Questions with images (Word/.doc/.docx) in Respondus

If you are using Respondus to import a test bank in Word .doc/.docx format that contains questions with images (e.g. screenshots of tables), convert the images to .jpg format. Respondus can have issues recognizing other image formats, such as .png, which is the default format of screenshots on Windows.

## Importing Questions with identical/similar questions in Respondus

If you are using Respondus to import a test bank with questions that all start with similar or identical wording (e.g. If you have several questions that start with "Use the chart below to answer the following question..."), alter the wording slightly to import the questions successfully. E.g. "The below table shows..." or "The table shows ..." or "Below is a table showing."

## Respondus Brightspace Server Information Settings

- Leave Address field blank
- Server Domain: ccis.ucourses.com
- Server Port: 443
- Check the "Yes, HTTPS:// always" checkbox
- Description: respondus
- User name: respondus
- Password: respondus
- Check the "Remember my User Name and Password" checkbox

Click OK to lock in the server settings

# Automatic Grades and Auto-Export Grades

## Automatic Grade only enabled

- no grade in grade book (indicates there is an ungraded attempt but score is not displayed)
- Students can see attempt but score appears as "-/[Total Score]"
- grade displayed at end of assessment
- note: students who took quiz before Automatic Grade was enabled cannot see their grades if Automatic Grade is enabled after the fact. Automatic Grade must be enabled prior to students taking the quiz in order for them to view their grade upon submitting their quiz.

## Automatic Grade and Auto-Export enabled

- Grade is copied to Grade Book and given the score the student receieved upon submitting their quiz.
- Grades are visible to students in the Grade Book, as well as upon submission of their quiz.

Note: If the quiz includes or essay questions, these items are not graded and therefore the score will be partial.

Note: If students take the quiz before Automatic Grade is enabled, these scores will still require manual grading before appearing in Grade Book.

Note: If Auto-Export is enabled after students have taken the quiz, grades will appear in the Grade Book. However, if Auto-Export is disabled after students take the quiz, their grades will still be visible in Grade Book.

## Auto Export is Enabled but Automatic Grade is Disabled

- Grade is not scored in grade book, requires manual grading
- Student cannot see score in Grades nor upon submitting their quiz

## Submission Views

- Our standard practice is to NOT provide the correct answer to cut down on cheating
- 

## Course number ids

- 0: **Day**
- 5: **Online**
- 1: **CCG**
- 3: **Evening**

## Where are LOR (Learing Object Repository) pages located?

LOR pages are located in the Courseware Master, in the Content area:
https://ccis.ucourses.com/d2l/home/836689

## How to Update / Publish an LOR page

1. Go to the Courseware Master course - https://ccis.ucourses.com/d2l/home/836689
2. Go to the Content area and find the specific LOR page
3. Edit the page and then click Save and Close
4. Open the page's dropdown menu (via the (down carret) next to the title) and click Publish to LOR
5. Select "Overwrite an existing object" and click Search
6. Type the full title of the LOR page into the Search For field (you can ignore the abbreviated search suggestions)
7. Find the LOR page in the search results, select it, and click Select
8. Click Next at the bottom of the screen, and click Next on the Detected Files that follows
9. Leave the fields on the Metadata screen as is, click Publish to LOR. Wait a moment for it to complete the process. When you see Publishing Complete, you are done.

## Shared Files

"You are attempting to overwrite a file in the Shared Files area that may be in use by other people in your organization." "Save a copy of this file in Course Offering Files"

## Connect SAR Time Extensions

1. Impersonate the instructor and on the course homepage click "Go to my Connect section" in the sidebar on the right
2. In connect, click on a quiz/exam. Now on the following screen, open the "assignment options" menu in the upper right and click "manage extensions." (If you don't see the "manage extensions" option, it is probably because course access is locked until the start of the next session. To enable the option, see ... basically you have to edit the course start end dates and then impersonate the instructor and enroll the student(s) to enable the option.)
3. On the following screen, select the student from the list on the right and then click "edit" next to time limit, and enter the new time limit in the field.
4. Click save to enter the changes.

## Connect Course Calendar Items

With Connect courses, calendar items are created in Connect and then imported into D2L in the section shells only; Connect course masters do not link to Connect, so they do not include calendar dates for Connect items.

## How to Redeploy / Resync Connect Calendar Dates

1. Unlink and delete Connect* Reset Connect section pairing in sidebar in course section* Manually delete Connect items in Content area of the course section, but do not delete other non-Connect items* Manually delete Connect items in Grades; do not delete non-Connect items
2. Relink Connect* Impersonate instructor, "Pair..." in sidebar
3. Relink / redeploy / resync* In Connect, in top right 'stack of papers' icon, click Redeploy

## Update / Change File Linked from Shared Files Folder

1. 

Check in D2L course section to confirm that items resynced successfully.

## Connect Error: "The assignment you are trying to access can't be found"

Usually, this issue can be resolved by:

1. Impersonating the instructor
2. On the homepage, navigate to the Connect widget in the sidebar
3. Click "Synch with my Connect section" link
4. Deploy the module back to the content section

## Rubric Overall Score

Each column's Overall Score is calculated as the lowest possible point value necessary to get into the particular column.

## Student Quiz Attempt in Progress Does Not Submit

- Go to the quiz in Quizzes and from the quiz menu choose Grade
- Click Show Search Options and select "All users" and click the search button
- Now find the student quiz attempt in progress and click the person icon.
- You should now be in the quiz as the student. Scroll down and click Submit to submit their quiz attempt.
- Check in Grades that the quiz attempt was successfully submitted.

## Sapling Courseware

Contact Joe Horton at Macmillan (joe.horton@macmillan.com) for quick answers.

If the student continues to have issues, there are alternative assignment Microsoft Word versions of each of the Sapling assignments they can complete instead, should tech support not be useful and they continue to have issues accessing the software. 
(Joe Horton's email is for CourseHelp, not students. Students would report it using the tech support option within the Sapling program itself, which will lead them to the Client Success Team.) credit: Andi K.

## Student Has Trouble Viewing eText

Forward the issue to truition@ccis.edu and explain the issue.

## Student Told to Purchase Access or Free Trial for Connect Course

Steps to resolve
- Impersonate student
- Go to Start Here > Getting Started with Connect module in the content area
- Go to Connect through the Connect widget on the homepage and click "Confirm"

credit: Anne Johnson

## Restore Deleted Grade Items / Scores in Gradebook

In the Grades area, click the More Actions menu, then View Event Log. Click "Restore" to restore the deleted items.

## ADA Student Not Showing Up in Connect Manage Extensions List

If a student receives ADA accommodations in a Connect course, but the student does not show up in the Manage Extensions list under the Connect quiz or exam, it may be because the course has just started and/or the student has not accessed the Connect course yet.

To make the student show up in the Connect quiz / exam Manage Extensions list:
1. Impersonate the student in D2L (if the student isn't in the Classlist, enroll them via the Add Participants dropdown menu)
2. From the course homepage, click on "Go to my Connect section" in the Connect widget
3. Now close the Connect tab and stop impersonating the student

To confirm the student is now in the Connect Manage Extensions list, impersonate the instructor, click on "Go to my Connect section" in the homepage widget, and go into a quiz or exam's Manage Extensions list.

If the student still does not show up in the Manage Extensions list, it is possible that SAR changed the student's ADA elegibility status since the ADA spreadsheet was last updated.

## Student Not Showing Up in Connect Course

If you are adding ADA extensions in a Connect course and a student is not showing up in the list in Connect, it is usually because the student has not clicked the initial Confirm button when accessing Connect via the homepage widget.

To resolve this, simply impersonate the student, open Connect through the homepage widget, and click the Confirm button.

The student should now appear in the extensions list screen in Connect when you impersonate the instructor and access Connect.

## [Broken Topic] Links in Content Area

To fix [Broken Topic] links in the Content area of a course, go to Table of Contents > Related Tools dropdown menu > Course Builder.

Next, expand the Content modules (e.g. Week 1, Week 2, ... etc) in the middle section (using the "+" button).

Now, in the left rail, under Browse Tools, drille into the item type of the [Broken Topic] (e.g. Discussions, Quizzes, etc), and click-and-drag the items directly onto the broken item and let go.

This process retains the due dates for each item (as opposed to the Existing Activities dropdown in the Content area, which does not).

## Stop Notification Texts to Students from D2L

1. Impersonate student
2. Go to user 

## MyLabsPlus Extend Course End Date


Via Anne Johnson:
edit the entire 19SUMR1 MATH Courses term end date in MLP because they don't have individual open/close dates. It's determined by the term. In MLP admin account, go to the gear icon then "administrative pages"
under "term creation" choose term mangement
then you can select the term, click next, and you can edit the close/end date

## How to Set Up Intelligent Agents

Go to import/export and copy the intelligent agents from the INTELLIGENT_NEWS shell (the one in the environmental studies department - make sure only the IAs are selected

## Change User Role Status in D2L

1. Click Users from the Admin Tools (gear icon) menu in D2L
2. Search for the user
3. From the user's actions dropdown menu click Manage User Enrollments
4. Go to the Enrollments tab
5. Search for "Columbia College"
6. Click the Role edit (pencil icon) button next to the "Columbia College of Missouri" entry
7. Select the new role from the list, click Apply

To check that the role change was successful, click the Cancel button (lower-left). The user's new role should be displayed under the Role column.

## MyProgrammingLab Set Up

1. Impersonate the instructor and click through the "Access MyLab Programming" link in the MyLab Programming widget on the homepage
2. Click on the "+ Add A Course" button. In the Your Sections tab click on the courses to expand the details and find the last session that the course ran. E.g. if you are copying for SUMR1, find the last SPRG2 course, etc.
3. Check the master tracking sheet for the CourseID to confirm you have the most recent session [add a CourseID column to tracking sheet]
4. Click the Clone button and then OK
5. A "Cloning Successful!" screen should appear.
6. Fill in the fields for the course:
- Course Title is the name of the course e.g. "Visual Basic"
- Course Term should be the current period, e.g. Summer 2020
- Course Number is the course department? and number, e.g. "CISS 234"
- Section Number is the course section, e.g. DEA
- Expected Enrollment is 0-30
- University is Columbia College
- Location is US MO

You can leave the other fields blank.

7. Click the Save button, then click Reload at the top of the Clone Section screen
8. Expand the course period you are working in (Spring, Summer, etc). You should see your newly created course section in the list
9. Copy the CourseID from MyProgrammingLab and paste it into the master tracking sheet
10. Now, go back to the course in D2L.
11. From the homepage, go to Annoucements and find the "Setting Up Your Courseware Access" announcement (if the Annoucement has not been copied to the course, go to Edit Course and copy the annoucement from the Courseware Master via Import/Export courses)
12. Now copy/paste the MyProgrammingLab Access Code and the CourseID (from step 9) from the master tracking sheet into the "Setting Up Your Courseware Access" annoucement. Click the Update button to save the announcement.

If you want to test that the access code works: Enroll a dummy student (Daffy Duck, Angelica Pickles, etc) into the course (do not use an actual student); impersonate them; click the Access MyLab Programming link in the MPL homepage widget; use your Pearson Education dummy account log in (if you don't have a Pearson Education account, you can create one through the setup screen (be sure to save your username/password somewhere); use the access code and CourseID, and follow the setup prompts.

You will know that the course was set up correctly if you are able to successfully access the MyLab Programming course successfully (it will look similar to instructor view). If you are not able to access the course, make sure you entered your Pearson Education account login/password correctly and try again.

If you are still unable to access the course, you likely need a new access code from Pearson. Contact Heather Racine-Vogt at mailto:heather.racine-vogt@pearson.com and request a new multi-redemption access code, noting the CourseID, the current access code, as well as the session and full D2L Course ID (found in D2L under Edit Course > Course Offering Information.

## Change Question Wording in Pearson MyLabs Statistics Master

1. From the MyLabs master course (via https://www.pearsonmylabandmastering.com/northamerica/), go to Instructor Tools (in the left sidebar), then Assignment Manager.
2. Open the Select menu on the question you are editing and choose Edit...
3. Click the Select Media and Questions tab at the top.
4. Find the specific question you are editing in the My Selections list on the right, click on the question title.
5. You should now see a preview of the question (if not click the Previous or Next button to move through the questions until you find it). With the question preview visible, click on the Copy and Edit button at the bottom of the screen.
6. Currently Pearson MyLabs requires Flash to be enabled in order to edit questions. If so, enable Flash in your browser (to enable in Chrome, click the SSL lock icon in the address/search bar, then Site settings, find Flash in the list, then choose Allow from the menu). You may need to reload the page before the Flash editing screen is available.
7. Click the Copy and Edit button again if you had to reload. You should now see an editing screen. Change the question wording as needed.
8. Click the Save and Exit button at the bottom to save the changes. Change the Name to something different; it won't let you use the same name. Click OK.
9. You should now be back at the screen with the My Selection list of questions. At the top of this screen should be a list of Question Source options with checkboxes. Check the "Show other custom questions" option. Now, the Available Questions list (to the left of the My Selections list, at the bottom of the screen) should have expanded with more questions.
10. Find the question that you changed in the Available Questions list. You can click the questions to see a preview. Once you find it, check the box next to the question and click the Add button on the right. The question should now appear in the My Selections list on the right.
11. Check that the Points value (on the right) is the same as the original question (if not, change the value). Next, check the box next to the original version of the question, then click the Remove button.
12. You can try to sort the questions back into the original order by selecting all of the assignments in the My Selections list and clicking on the Question ID/Media link above the list, but it does not always correctly resort them. If it doesn't, don't worry about it.
13. Finally, click the Save & Assign button at the bottom of the screen (you may need to scroll down if you don't see it) to lock in the new question wording.

## Student Cannot Send Email to Instructor in Classlist "address of 1 user can not be added" error

Ask the System Admin to check the 'show email address in classlist' checkbox in D2L for that instructor/course.

## Find and Replace True False text question answers with multiple lines in Word for Respondus

1. Copy the True False answer text. E.g. "Answer: TRUE", then hit **Ctrl H**
2. Paste the answer text into the Find What field
3. In the Replace With field, type out both answers on one line, e.g. ```*a. True b. False```
4. Next, place the cursor at the start of the Replace With field. Next, mouse over to the bottom of the Find/Replace window and click the Special menu. Now select "Manual Line Break"
5. You should now see "^l" has been inserted at the start of the Replace With field, like so: ^l*a. True ...
6. Now, place your cursor in front of the second answer (before the "b." in this example) and  select "Manual Line Break" from the Special menu again, as you did in Step 4.

The end result should look like this: ```^l*a. True^lb. False```
7. To test your work, click the Replace button. If you formatted it right, the unformatted ("raw") answer text should now be replaced with:
```*a. True
b. False```
8. Go back to the the Find and Replace window if the result doesn't look how you wanted.
9. Finally, if everything looks right, hit **Ctrl H** and click the Replace All button. Repeat for the other formulation. I.e. the questions with False answers in this example; spoiler:
```^la. True^l*b. False```

Always visually double-check that Find/Replace removed all of the correct answer text before uploading to a course.