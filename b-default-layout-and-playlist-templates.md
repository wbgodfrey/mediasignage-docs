# Appendix B — Default Layout & Playlist Templates



<!-- Page 006 -->

6 Contents
1042412 -0001 Revision G

## Tags ................................ ................................ ................................ ..........  156
Adding a Tag .................................................................................................  156
Editing (Renaming) a Tag  .............................................................................. 158
Deleting a Tag  ............................................................................................... 158
## Fonts ................................ ................................ ................................ ..........  159
Adding a Font  ................................................................................................ 159
Deleting Fonts  ............................................................................................... 160
## Layouts  ................................ ................................ ................................ ...... 161
Uploading an Existing Layout ........................................................................ 161
Creating a New Layout .................................................................................. 163
Modifying a Layout  ....................................................................................... 163
Deleting a Layout  .......................................................................................... 164
Layout Des igns and Specifications  ................................................................ 164
## Settings  ................................ ................................ ................................ ...... 164
Appendix A
# Additional Custom Player Settings ................................ ................................  167
Appendix B
# Default Layout & Playlist Templates ................................ .............................  171
Design and Spec Reference  ................................ ................................ .........  171
Layout L1  ................................ ................................ ................................ ... 172
Layout L2  ................................ ................................ ................................ ... 172
Layout L3  ................................ ................................ ................................ ... 173
Layout L4  ................................ ................................ ................................ ... 173
Layout P1  ................................ ................................ ................................ ... 174
Layout P2  ................................ ................................ ................................ ... 174
# Playlists for L1 & L2  ................................ ................................ ....................  175
# Playlists for L3 & L4  ................................ ................................ ....................  175
# Playlists for P1  ................................ ................................ ............................  176
# Playlists for P2  ................................ ................................ ............................  176
Time & Date ................................ ................................ ...............................  177
RSS Feed  ................................ ................................ ................................ .... 177
Weather  ................................ ................................ ................................ ..... 178




<!-- Page 007 -->

# Welcome to MediaSignage Server
1042412 -0001 Revision G  7
# Welcome to MediaSignage Server
Introduction
MediaSignage Server  is a combined hardware and software solution designed to
deliver, manage, and display digital signage content in environments ranging from
single -display installations to corporate enterprises with hundreds of sites.
The MediaSignage Server is a Web- based interface for managing content, playlists,
schedules, and MediaSignage hardware player s. Each MediaSignage Player
communicates with the MediaSignage Server to download media files and to get
correct information on when and how to display the files.
IMPORTANT:  For best performance, the preferred browser  for MediaSignage Server
is Chrome .
What’s Inside
MediaSignage Server allows for four user roles :
- Organization Administrator  role allows the individual to manage the
organization as well as all accounts within it. An Org Admin can do everything an Account Admin  can do…and more.
- Account Administrator  role gives the individual access to manage everything
within only the assigned account.
- L ocation Administrator  role allows the individual —who is assigned to one or
more locations or gro ups—to create content, upload it to the system, and add
it to a playlist. This role  can also view and edit the profiles of users in their
location.
- C ontent Contributor  role allows the individual —who is assigned to one or
more  groups —to create content and upload it to the system (but not add it to
a playlist).
- E mployee  role has no rights or system access. The main purpose of this role is
to store information for employees who do  not have any of the other roles in
this list .
This Administrator Guide  is for all Organization, Account, and Location
Admin istrators  as well as Content Contributors  using Media Signage Server . It is
presented in a task -oriented manner, giving you detailed procedural steps to help
you administer your company’s digital signage system.
Not included in this guide is installation, setup, and maintenance information for your player devices. See your player’s documentation for t hat information .
NOTE : All screenshots in this manual reflect an imaginary company and its users,
groups, classes, courses, etc., and they are included for example purposes
only. Your screens will contain different content to reflect your actual
company and employees and your MSS setup.


<!-- Page 008 -->

8 Welcome to MediaSignage Server
1042412 -0001 Revision G

## Information Organization
Following this introductory information, t his manual is divided into two parts, one
containing information and task procedures for the Organization Admin and one for
the Account Admin.
NOTE : All screenshots in this manual reflect an imaginary company and its accounts,
users, players , content, etc., and they are included for example purposes
only. Your screens will contain different content to reflect your actual
company and employees and its Media Signage Server  setup.
## Activating Your Account
## SSO Users
If your company uses single sign -on, your admin will send an email with the URL to
the MediaSignage login page. When you enter your email address, you are taken to your company’s SSO. Once you log in there, your MediaSignage account is
automatically activated.
Non- SSO Users
When your admin initially creates your user account, using  your name and email
address , the system sends you an email saying you are invited to join MediaSignage.
To join a nd officially activate your account , do the following:
1. Click the Accept Invitation  link in the email.
A browser (or new tab in an open browser) will open to the Set Your Password
dialog  in MediaSignage.

Figure 1: Set Password
![Figure 1: Set Password](/images/page008_Im0.jpg)



<!-- Page 009 -->

# Welcome to MediaSignage Server
1042412 -0001 Revision G  9
2. Specify a password (at least 6 characters of any kind ).
IMPORTANT:  Passwords are case sensitive!
3. Re-enter the password in the Password Confirmation field.
4. Click Set My Password.
To decline the invitation, simply do nothing. Your MediaSignage account will not be
activated.
## Logging In/Out
To log in to MediaSignage, enter your email address and password on the login page
(https://www.hughessignage.com/users/sign_in ) and t hen click Log In .
If you  can’t remember  your password , you can reset it :
1. Click the Forgot Password?  link just above the Password field.
2. Type in  your email address  and click Send Password Reset .
3. Log in using the temporary password sent to your email and then immediately
change it  to a new password of your choosing (see “Changing Your Password ”
below) .
To log out of the system, click your name in the top -r ight corner of any page and
then click Sign Out .

Figure 2: Sign Out  Location
![Figure 2: Sign Out  Location](/images/page009_Im0.jpg)
## Managing Your Profile Information
On the Edit Profile page, you can view your general information (name and email) as
well as change your username. You can also change your password here.
## Changing Your Password
1. Click your name in the top- right co rner of any page and then click Edit Profile.
2. On the Edit Profile page, make sure Password is selected  (1).



<!-- Page 010 -->

10 Welcome to MediaSignage Server
1042412 -0001 Revision G


Figure 3: Change Password Dialog
![Figure 3: Change Password Dialog](/images/page010_Im0.jpg)
3. Type in  your current password and a new password  (2).
It must be at least 6 characters of any kind.
IMPORTANT:  Passwords are case sensitive .
4. Retype  the new password in the Confirm Password field ( 3).
5. Click Change Password ( 4).
## Changing Your Username
An account is tied to a person’s email address, not their username. Consequently,
you may change your name to whatever you like , whenever you like.
1. Click your name in the top- right corner of any page and then click Edit Profile.
2. On the Edit Profile page, make sure General Information  is selected.
3. In the Name  field, type in a new name.
4. Click Save Profile.
You can also change the name of anyone in your organization or account. See
“Editing User Settings ” for more information.




<!-- Page 011 -->

# Welcome to MediaSignage Server
1042412 -0001 Revision G  11
## Searching
On any page that has searchable information, a Magnifying Glass  icon is  located in
the upper  right just above the searchable info  (1). For example:

Figure 4: Search  & Cog  Icon s Location
![Figure 4: Search  & Cog  Icon s Location](/images/page011_Im0.jpg)
## Customizing Table Headings
Most tables are customizable by changing what headings (and related info) are
displayed. If this is possible, a Cog  icon appears in the upper right just above the
table ( 2, above).
When you click the icon, a dialog appears where you can select the device you’re
using and select/deselect the head ings you want to display/hide:

Figure 5: Table Customization Dialog
![Figure 5: Table Customization Dialog](/images/page011_Im1.jpg)



<!-- Page 012 -->

12 Welcome to MediaSignage Server
1042412 -0001 Revision G




<!-- Page 013 -->

# Welcome to MediaSignage Server
1042412 -0001 Revisi on G 13




PART 1 :
ORGANIZATION ADMINISTRATOR












<!-- Page 014 -->

14 Welcome to MediaSignage Server
1042412 -0001 Revision G




<!-- Page 015 -->

# Chapter 1  • Accounts
1042412 -0001 Revision G  15
# Chapter 1
# Accounts
When an Organization Admin logs in to MediaSignage, the default page that opens
is the All Accounts page for the organization, as shown in the following example.

Figure 6: All Accounts Page
![Figure 6: All Accounts Page](/images/page015_Im0.png)
This part of the guide covers the following information and p rocedures for the
Organization Administrator:
- Accounts
- Adding
- Setting Up/Editing
- Deleting
- Users
- Adding
- Editing
- Deleting
- Impersonating
- Players
- Moving
- Deleting
- Content Hosts
- Adding
- Importing



<!-- Page 016 -->

16 Chapter 1  • Accounts
1042412 -0001 Revision G

Adding Accounts
To add a new account, do the following:
1. On the All Accounts page, click Accounts > Add Account  in the left -side
menus.

Figure 7: Add Account Menu Option
![Figure 7: Add Account Menu Option](/images/page016_Im0.png)
2. On the Add Account page that open s, specify the account details and settings
using the following fields.

Figure 8: Add Account Settings  Page
![Figure 8: Add Account Settings  Page](/images/page016_Im1.jpg)




<!-- Page 017 -->

# Chapter 1  • Accounts
1042412 -0001 Revision G  17
3. Specify details under the Account Details column :
- Name  (1): Name of the account (required setting)
- Description ( 2): Description of the account, such as location, type of
business, etc.
4. Specify time -related settings under the Time Settings c olumn :
- Player Offline after Seconds  (3): Amount of time that players have not
“checked in” after which they are officially considered as being offline
- Content Duration Default  (4): Default amount of time that content is
displayed (required setting)
- Publish  Schedules Daily At  (5): Time at which schedules are published
every day (required setting)
5. Specify the SAML setting s (6) as appropriate.
6. Click Save  (or Cancel  to back out).
Modifying  Account s
You can modify an account  by managing it, editing its settings,  moving it, or deleting
it.
Find the account in the All Accounts list and click the Ellipses  icon at the far right of
that row ( 1) to open a drop -down list of options:

Figure  9: Modify Account  Options
![Figure  9: Modify Account  Options](/images/page017_Im0.png)
Managing Accounts
1. Go to the account’s line entry on the All Accounts page and select ing Manage
from the drop -down list  at the far right ( 2).
Alternately, you can also simply click the account name in the list (also 2 ).
Both actions open the account’s summary  page by default.




<!-- Page 018 -->

18 Chapt er 1 • Accounts
1042412 -0001 Revision G

2. To exit the Account area and return to the Organization area, do any of the
following from any Account page:
- On the far -left side of the top banner, click the MediaSignage  logo ( 1,
below ).
- In the center of the top banner, click the name of the account ( 2) and
then cli ck the Manage Account  button ( 3).
Note that clicking on the account name here also lets you switch to a
different account by selecting its name from the drop -down Accounts list
(4).
- On the far -right side of the top banner, click your name ( 5) and then click
Organization Management  (6).

Figure  10: Return to Organization from Account
![Figure  10: Return to Organization from Account](/images/page018_Im0.jpg)
For details about managing an account, see Part 2: Account Administration .
Editing Account Settings
1. To change the account’s settin gs, go to the account’s line entry on the All
# Accounts page and  select Edit from the drop -down list ( 3).
The account ’s settings page opens.



<!-- Page 019 -->

# Chapter 1  • Accounts
1042412 -0001 Revision G  19

Figure  11: Change Account Settings
![Figure  11: Change Account Settings](/images/page019_Im0.jpg)
2. Make the desired changes and then click Save  (or Cancel  to back out).
Deleting Accounts
IMPORTANT: When you delete an account, you can never retrieve it or its data
again. The best you can do is re -create it.
1. To delete an account, go to the account’s line entry on the All Accounts page
and select Delete  from the drop -down list ( 6, Figure 9 ).
2. In the Confirmation Required pop -up message that appears, select Yes to
delete  it (or No to back out and keep the account ).









<!-- Page 020 -->

20 Chapter 1  • Accounts
1042412 -0001 Revision G























<!-- Page 021 -->

# Chapter 2  • Users: Org
1042412 -0001 Revision G  21
# Chapter 2
## Users : Org
Adding Users
To add a new user  to the organization, do the following:
1. On the All Users page, click Accounts > Add User  in the left -side menus.

Figure 12: Add User Menu Option
![Figure 12: Add User Menu Option](/images/page021_Im0.jpg)
The Org name  > Add User page opens .



<!-- Page 022 -->

22 Chapter 2  • Users: Org
1042412-0001 Revision G


Figure 13: Add User Dialog
![Figure 13: Add User Dialog](/images/page022_Im0.png)
2. Specify the user’s first and last name s and email address in the respective
fields.
3. From the Role drop -down list, select a role to assign to the user.
4. From the Account  drop -down list, select an account to assign the user to.
Organization Administrators are not assigned to accounts, and the re will be
no Account  field if the new user is given the Org Ad min role .
5. You can ignore the Invitation URL. The system automatically generates it
when you save the new user if they are a non -SSO user.
6. Click Save  (or Cancel  to back out).
NOTE:  Creating and modifying more detailed user settings is the responsibility of
Account Administrators for their specific users (for that information, see
## Users ).
Modifying  Users
You can modify users by deleting them or editing their  basic settings
shown in Figure 1 3.
Find the user in the All Users list and click the Ellipses  icon at the far right
of that row ( 1) to open a drop -down list of options:



<!-- Page 023 -->

# Chapter 2  • Users: Org
1042412 -0001 Revision G  23

Figure 14: Modify User Options
![Figure 14: Modify User Options](/images/page023_Im0.png)
Editing User Settings
1. To change a user’s  settings, go  to the user’s  line entry on the All Users  page
and select Edit  from the drop -down list ( 2).
The user’s  settings dialog  opens .

Figure  15: User Settings  Dialog
![Figure  15: User Settings  Dialog](/images/page023_Im1.jpg)
2. Make the desired changes and then click Save  (or Cancel  to back out).




<!-- Page 024 -->

24 Chapter 2  • Users: Org
1042412 -0001 Revision G

Deleting Users
IMPORTANT: When you delete a  user , you can never retrieve it or its data again.
The most you can do is re -create it.
1. To delete a  user , go to the user ’s line entry on the All Users  page and select
Delete  from the drop -down list ( 3, Figure 14 ).
![Delete  from the drop -down list ( 3, Figure 14 ).](/images/page024_Im0.jpg)
2. In the Confirmation Required pop -up message that appears, select Yes to
delete it (or No to back out and keep the account).
Impersonating a nother User
If an A ccount or Location Admin is having an issue that the ir Organization Admin
does not also see, the Org Admin can log  in as that admin  to better understand
what they’re experiencing .
To do this, the Org Admin “impersonates” the other a dmin by doing the following:
1. Go to the admin’s  line entry on the All Users  page and select Impersonate
from the drop -down list ( 4, Figure 1 4).
The summary page of the admin you selected,  and a notice appears o n the
right side  of the top banner indicating that you are now impersonating the
admin you selected and what their role is ( 1, below ).

Figure  16: Impersonating Users
IMPORTANT:  While you’re impersonating the admin , they are still logged in
and can continue to work in the system as usual.  But they don’t
see any indication that someone is impersonating them, so if
they need to know for some reason, then they must be told.
2. When you no longer need to impersonate the admin , click STOP  (2).
The impersonation notice disappear s from your  top banner  and you’re
returned to the All Accounts page .







<!-- Page 025 -->

# Chapter 3  • Players: Org
1042412 -0001 Revision G  25

# Chapter  3
Players: Org
Account Admins typically have responsibility for the tasks concerning media players.
An Organization Admin usually only needs to view a list of the players in their
organization and see the information and status of each one.  They can also move
and delete players.
1. To view the player list  and basic info about them , click Players  in the left -side
menu to open the All Players page:


Figure  17: All Players Page
![Figure  17: All Players Page](/images/page025_Im0.png)
2. To move a player from one account to another, do the following:
a. Click the Ellipses  button at the far right of the row for the player you
want to move.



<!-- Page 026 -->

26 Chapter 3  • Players: Org
1042412 -0001 Revision G


Figure 18: Move Option
![Figure 18: Move Option](/images/page026_Im0.png)
b. In the dialog that opens, select the account to move the player  to from
the drop -down list .
c. Click Save  (or Cancel  to back out).
3. To delete a player , do the following.
a. Click the checkbox next to the player name  (1).
You can select more than one player to delete at the same time.

Figure 1 9: Delete Players
![Figure 1 9: Delete Players](/images/page026_Im1.png)
b. Click the Delete  button that appears at the very top of the page  (2).
c. Click Yes in the confirmation dialog that opens (or Cancel  to back out).
To see additional details about players in a specific account and/or perform tasks
concerning them, go to Chapter 8 “Players: Admin .”






<!-- Page 027 -->

# Chapter 4  • Content Hosts
1042412 -0001 Revision G  27
# Chapter  4
# Content Hosts
Content hosts provide a way for MediaSignage (MS) players to receive content via
an EPD server rather than from an MediaSignage server. This configuration is most helpful in instances such as when a single content item/ file needs to be distributed
a large number of MS players in a company.
Rather than these players having to get the downloaded file from the MS server (in the Cloud), the file can be downloaded from the MS server to an EPD server at the company’s NOC (network operations center) and sent out  via satellite to all branch
servers (HS3500/3600s) , which become “content hosts” that then download the file
to all MS players i n the company.
Adding a Content Host
1. Click Content Host > Add Content Host .

Figure 20: Add Content Host Option
![Figure 20: Add Content Host Option](/images/page027_Im0.png)
2. In the Conte nt Host dialog that opens, do  the following:
- Name : Specify a name for  the host
- Host: Enter an IP address or domain name
3. Click Save  (or Close to back out).




<!-- Page 028 -->

28 Chapter 4  • Content Hosts
1042412 -0001 Revision G

Importing Content Hosts (with a CSV)
You can add a large number of Content Hosts at the same time by creating a CSV file
and importing it.
1. Create a CSV file that includes a column of Host names and a column of Host
IP addresses or domain names,  following these requirements  (which are listed
when you click Content Hosts > Import CSV ):

Figure 21: Import Content Hosts CVS Dialog
![Figure 21: Import Content Hosts CVS Dialog](/images/page028_Im0.png)
2. After creating (or updating) the file and clicking Content Hosts > Import CSV ,
click the Browse  button in the dialog to select the CSV file to import.
3. Click Import  (or Cancel  to back out).
The content host information you import ed should now populate the table on
the Content Hosts page.







<!-- Page 029 -->

# Content Hosts
1042412 -0001 Revision G  29


PART  2:
ACCOUNT ADMINISTRATOR


<!-- Page 030 -->

30 Chapter 4  • Content Hosts
1042412 -0001 Revision G














<!-- Page 031 -->

# Content Library
1042412 -0001 Revision G  31
# Chapter  5
# Content Library
The Content Library  is where you can add and manage  your account’s content  a nd
data feeds .
## Accessing the Content Library
The Content Library option is located at the top of the  blue  left-side menu .
Organization Admin
If you are an Org Admin, click Account s in the left -side menu of your  Manage
Organizations window and then click the name of the account you want to access in
the All Accounts page list. This opens to the account’s summary  page . To access the
# Content Library and its Content and Data Feeds subm enus, simply click that option
at the top of the left- side menu ( Figure 2 3 below) .
![at the top of the left- side menu ( Figure 2 3 below) .](/images/page031_Im0.jpg)
Location Admin
When you log in to MediaSignage as a Location Admin, your account opens by default to the Locations page with the Employees option selected in the left -side
menu.
You don’t have access to the Content Library, only to the Content page for your location. Simply click that option at the top of the left -side menu:

Figure  22: Location Admin Content Menu Option
Account Admin
When you log in to MediaSignage as an Account Admin, your account opens by default to your account’s summary page .
To access the Content Library  and its Content and Data Feeds submenus, simply
click that option at the top of the left -side menu:



<!-- Page 032 -->

32 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure  23: Org/Account Admin Content Library Menu Option
![Figure  23: Org/Account Admin Content Library Menu Option](/images/page032_Im0.jpg)
## Managing Account Content
To manage your account’s content, go to Content Library > Content .

Figure 24: Content Main Page
![Figure 24: Content Main Page](/images/page032_Im1.jpg)
The main Content page contains the following information and options:
- Total number of content items ( 1)
- Image files ( 2)
- Video files ( 3)
- HTML  (URL)  files ( 4)
- Word files ( 5)
- Audio files ( 6)
- Content Template  Content  (7)
- Folders ( 8)
- Name column listing toggle, A –Z or Z –A (9)
- Drop -down to open (folders), edit, share,  delete item  or add it to playlist  (10)
- Filter  (11), Search  (12), and Modify Table Heading s (13) option s
You can perform these  tasks from  the main Content page:
- Add folders
- Create content
- Upload content
- Edit content
- Move content



<!-- Page 033 -->

# Content Library
1042412 -0001 Revision G  33
- Add content to playlist
- Share content
- Delete content
## Adding a Folder
Folders are used to group content items to be used for teams, projects, types of
people (e.g., new hires or night shift), special events (e.g., Mother’s Day sale or store grand opening), and so on.
To create a folder, do the following:
1. Click Content Library > Content > Add Folder.
2. In the Folder pop -up that opens, type a name for the fo lder.
3. Click Save  (or Cancel  to back out).
## Creating Content
You can create five types of content:
- URL content
- Local  content  placeholder
- Template  content
- TV input
- Live stream
While on the main Content page or in the folder where you want to create content,
click either of these:
- Create Content  option (in the gray side menu)
- The Plus Sign  icon at the top right of the page and then Create



The Create Content window appears. Either click Cancel  to back out or click one of
the content type icons and then go to that type’s section below for the steps to follow.

![Page 33 image](/images/page033_Im0.jpg)
![Page 33 image](/images/page033_Im1.jpg)


<!-- Page 034 -->

34 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure 25: Create Content Options
![Figure 25: Create Content Options](/images/page034_Im0.jpg)
Creating URL Content
When you click the URL Content icon, the URL Content page  opens:

Figure 26: URL Content Page
![Figure 26: URL Content Page](/images/page034_Im1.jpg)
1. Fill in the following required info and any optional info you desire:
- Name:  Specify a name for this content item (required) ( 1)
- URL:  Specify the URL address (required) ( 2)
- Description: Add a description of the content ( 3)
- Duration: Click in the field to select the length of time (hours, minutes,
and/or seconds) that the content is displayed (default is 20 seconds) ( 4)
- Start time:  Click in this field to open a calendar where you can set the
day and time when this content starts being displayed (required) ( 5)



<!-- Page 035 -->

# Content Library
1042412 -0001 Revision G  35
- End time: Click in this field to open a calendar where you can set the day
and time when this content stops being displayed  (6)
- Settings:  Check the box if you want the content to fill  the entire screen,
no matter what the layout settings may be ( 7)
- Tags:  Add (assign) any tags you’d like by selecting them from the
scrollable  Tags list (8)
2. Click Save  (or Cancel  to back out).
Creating  a Local  Content  Placeholder
NOTE : When you use this option, you are not actually creating any content. Local
content is created or uploaded  to a location by users. What this option lets
you do is create a placeholder for that content.
When you click the Local Content  icon, the Local Content page opens:

Figure 27: Local Content Page
![Figure 27: Local Content Page](/images/page035_Im0.jpg)
1. Fill in the following required info and any optional info you desire:
- Name:  Specify a name for this content item (required) ( 1)
- Description: Add a description of the content ( 2)
- Duration: Click in the field to select the length of time (hours, minutes,
and/or seconds) that the content is displayed (default is 10 seconds) ( 3)
- Start time:  Click in this field to open a calendar where you can set the
day and time when this content starts being displayed (required) ( 4)
- End time: Click in this field to open a calendar where you can set the day and time when this content stops being displayed  (5)



<!-- Page 036 -->

36 Chapter 5  • Content Library
1042412 -0001 Revision G

- Settings:  Using the toggle arrows, set the Placeholder Limit  (how many
local content items are allowed on screen  when the placeholder plays in
a playlist ) and check the Full Screen option if you want the content to fill
the entire screen, no matter what the layout settings may be (6)
If you do not set a placeh older limit, then when the local content is
displayed in the playlist, all l ocal content assigned to that TV is display ed.
If you do  set a placeholder limit, then only that number of local content
items  is displayed (from first to last)  each time the local content is
displayed on screen .
- Tags:  Add (assign) any tags you’d like by selecting them from the
scrollable list  (7)
2. Click Save  (or Cancel  to back out).
## Creating Content from a Template
When you click the From Te mplate  icon, you are taken to the Available Content
Templates page :

Figure 28: Available Content Templates Page
![Figure 28: Available Content Templates Page](/images/page036_Im0.jpg)
1. Select a template to use by clicking either the template image or its name.
TIP: If there is a long list of templates, you can narrow the listing by using the
Filter  icon ( 1) to find only those templates that have certain tags or the
Search icon ( 2) to bring up a template with a specific name or keyword.




<!-- Page 037 -->

# Content Library
1042412 -0001 Revision G  37
The template opens:

Figure 29: New Content Template
![Figure 29: New Content Template](/images/page037_Im0.jpg)
Note that at any point in this procedure of creating content, you can save the
content and then come back to it later to complete it.
2. To include an image, do the following :
a. Click inside the Image Placeholder area ( 1).
This outlines the image area, showing that it’s “active,” and also opens
the Image Placeholder settings in the left panel.

Figure 30: Image Placeholder
![Figure 30: Image Placeholder](/images/page037_Im1.jpg)
b. In the Image  field in the left panel, click Choose File ( 2).
c. Browse your directories to locate the image you  want, then click Open.



<!-- Page 038 -->

38 Chapter 5  • Content Library
1042412 -0001 Revision G

d. Use the Zoom (%)  toggle arrows (3) (or enter a number in the field) to
increase/decrease the photo size.
Note that you can’t decrease the original image size (which is the 100%
value); you can only increase it.
e. Click -and-drag the photo to reposition it within the image window.
If you don’t change the photo size in Step 2d, then you are not able to reposition the image.
f. To change the image, double -click it and then select another one.
g. To remove the image, click Clear Image  in the Cle ar field ( 4).
3. To include text, do the following:
IMPORTANT:  As you read these steps, note that an Admin has the ability to
lock any of the text placeholder fields, preventing others from
changing what they have already set for that option. If an
option has been locked, you won’t even see it in the panel.
a. Click in any variable text area ( 1, below ).
This outlines the text area and darkens its background color, showing that it’s “active,” and also opens the Text Placeholder settings in the left
panel.

Figure 31: Text Placeholders
![Figure 31: Text Placeholders](/images/page038_Im0.jpg)
b. In the Text  field in the left panel ( 7), replace the placeholder text with
your desired text.
You will see the text change accordingly on the template ( 1).
c. In the Text Placeholder settings in the left panel, do the following as
desired to change the look and placemen t of the text:
- Click in the Font  field ( 2) and select the font family for this text from
the drop -down list.



<!-- Page 039 -->

# Content Library
1042412 -0001 Revision G  39
- In the Color  field ( 3), type in the hex code for the color you want the
text to be.
Note that you must backspace in the field to delete the current  hex
code and then type in the new code. You cannot highlight the current
code and paste a copied code over it.
TIP: If you’re unfamiliar with HTML color hex codes, here is a good
reference site: https://htmlcolor codes.com .
- In the Size  field ( 4), type in or toggle to the font size you want the text
to be.
- From the horizontal alignment options ( 5), select whether the text is
flush left, centered, or flush right within the variable box area.
- From the vertical alig nment options ( 6), select whether the text sits at
the top, center, or bottom of the variable box area.
d. Repeat Steps 4a –4c for all other text placeholders you want to use in the
template.
If there is a text placeholder that you don’t want to include in you r
content, simply delete the placeholder text in the left panel Text  field.
But note that you cannot delete the placeholder itself.
4. Click  the Save button in the upper -right of the window .
A Content Preview window opens showing how the content will display  as
well as the image dimensions and size .

Figure 32: New Content Preview
![Figure 32: New Content Preview](/images/page039_Im0.jpg)



<!-- Page 040 -->

40 Chapter 5  • Content Library
1042412 -0001 Revision G

5. Add a Folder Name ( 1) and Content Name ( 2).
6. Click one of the following:
- Save Content  to simply save the content ( 3)
- Save & Add to Playlist  to save  this content and also add it to a playlist ( 4)
- Cancel  to back out to the template  (5)
The new content now appears in the table on the main Content page.
Creating TV Input Content
When you click the TV Input  icon, the TV Input Content page opens:

Figur e 33: TV Input Content Page
1. Fill in the following required info and any optional info you desire :
- Name:  Specify a name for this content item (required) ( 1)
- TV Input : Select the appropriate HDMI from the drop -down list
(required) (2 )
- Description: Add a description of the content ( 3)
- Duration: Click in the field to select the length of time (hours, minutes,
and/or seconds) that the content is displayed (default is 20 seconds) ( 4)
- Start time:  Click in this field to open a calendar where you can set the
day and time when this content starts being displayed (required) ( 5)
- End time: Click in this field to open a calendar where you can set the day
and time when this content stops being displayed  (6)


![Page 40 image](/images/page040_Im0.jpg)


<!-- Page 041 -->

# Content Library
1042412 -0001 Revision G  41
- Settings:  Check the box if you want the content to fill the entire screen,
no matter what the layout settings may be ( 7)
- Tags:  Add (assign) any tags you’d like by selecting them from the
scrollable tag list  (8)
2. Click Save  (or Cancel  to back out).
Creating Live Stream Content
When you click the Live Stream  icon, the TV Input page opens:

Figure 34: Live Stream Content Page
![Figure 34: Live Stream Content Page](/images/page041_Im0.jpg)
1. Fill in the following required info and any optional info you desire :
- Name:  Specify a name for this content item (required) ( 1)
- Address/URL : Specify  the a ppropriate address or URL  (required) ( 2)
- UDP Port : Using the toggle arrows , select the appropriate UDP port
(required) (3 )
- Description: Add a description of the content ( 4)
- Duration: Click in the field to select the length of time (hours, minutes,
and/or seconds) that the content is displayed (default is 20 seconds) ( 5)
- Start time:  Click in this field to open a calendar where you can set the
day and time when this content starts being displayed (required) ( 6)
- End time: Click in this field to open a calendar where you can set the day
and time when this content stops being displayed  (7)




<!-- Page 042 -->

42 Chapter 5  • Content Library
1042412 -0001 Revision G

- Settings:  Check the box if you want the content to fill the entire screen,
no matter what the layout settings may be ( 8)
- Tags:  Add (assign) any tags you’d like by selecting them from the
scrollable tag list  (9)
2. Click Save  (or Cancel  to back out).
## Uploading Content
To upload already existing  content, do the following:
1. While on the main Content page or in the folder where you want to upload
content, click either of these:
- Create Content  option (in the gray side menu)
- The Plus Sign  icon at the top rig ht of the page and then Upload



2. Find and select the content you want to upload, then click Open.
3. In the Content > Uploading window that opens, fill in the following required
info and any optional info you desire .

![Page 42 image](/images/page042_Im0.jpg)
![Page 42 image](/images/page042_Im1.jpg)


<!-- Page 043 -->

# Content Library
1042412 -0001 Revision G  43

Figure 35: Uploading Content  Settings  Page
![Figure 35: Uploading Content  Settings  Page](/images/page043_Im0.jpg)
- Content Image: Displays image of the uploaded content ( 1)
- Name:  Specify a name for this content item (required)  (2)
- Description: Add a description of the content  (3)
- Duration: Click in the field to select  the length of time (hours, minutes,
and/or seconds)  that the content is displayed  (default is 10 seconds)  (4)
- Start time:  Click in this field to open a calendar where you can set the
day and time when this content starts being displayed (required)  (5)
- End time: Click in this field to open a calendar where you can set the day
and time when this content stops being displayed  (6)
- Settings:  Check the Full Screen option if you want the content displayed
in full screen ( 7)
- Tags:  Add (assign) any tags you’d like to this content  by selecting them
from the scrollable tag list  (8)
4. Click Save .
## Editing Content
To edit any content  (uploaded or created) , do the following:
1. In the main Content list (or in a folder’s Content list) click the  Ellipsis  icon at
the far right of the content item’s line and then select Edit .



<!-- Page 044 -->

44 Chapter 5 • Content Library
1042412 -0001 Revision G


Figure 36: Edit Content  Option
![Figure 36: Edit Content  Option](/images/page044_Im0.png)
The content item’s Edit page opens, showing the same settings as when the item
was first uploaded,  with the addition of the option to replace the image, video, or
audio file if that’s the type of content it is .

Figure 37: Edit Content – Replace Option
![Figure 37: Edit Content – Replace Option](/images/page044_Im1.jpg)
2. Make your desired changes and then click Save  (or Cancel  to back out).



<!-- Page 045 -->

# Content Library
1042412 -0001 Revision G  45
## Moving Content
To move conten t within the organization, do the following:
1. Select the content you want to move by clicking it in the Name column.

Figure 38: Content List – Name Column
![Figure 38: Content List – Name Column](/images/page045_Im0.jpg)
2. On the content item’s details page, select Move  in the left -side gray menu.

Figure 39: Content Move Option
![Figure 39: Content Move Option](/images/page045_Im1.jpg)



<!-- Page 046 -->

46 Chapter 5  • Content Library
1042412 -0001 Revision G

3. In the Move Content dialog that opens, select a folder to move the content
item to.
4. Click Move  (or Cancel  to back out).
## Adding Content to Playlist s
To add content to one or more  playlist s, do the following:
1. In the main Content list (or in a folder’s Content list) click the Ellipsis  icon at
the far right of the content item’s line and then select Add to Playlist .

Figure 40: Content Add to Playlist  Option
![Figure 40: Content Add to Playlist  Option](/images/page046_Im0.png)
2. In the dialog that open s, select the playlists (which might be within a folder)
to add the content to.
3. Click Add (or Cancel  to back out).
## Sharing Content
You can share content with your entire organization (all accounts) or with just
specific accounts . You will not be able to unshare it , so it is actually more like a
copy/send.
The following happens when you share content:
- The content/folder is copied to the organization or selected accounts
- The end time/date are deleted and the start time/date are set to the past
(identical to  when a new piece of content is uploaded)
- Tags are removed
Basically, it is as if the user reuploaded the same piece of content multiple times for each account the user selected it to be shared with.
To share content, do the following:
1. In the main Content list (or in a folder’s Content list) click the Ellipsis  icon at
the far right of the content item’s line and then select Share .



<!-- Page 047 -->

# Content Library
1042412 -0001 Revision G  47

Figure 41: Content Share Option
![Figure 41: Content Share Option](/images/page047_Im0.png)
2. In the dialog that opens, do either of the following:
- Click My Organization .
- Click Specific A ccounts  and then from the list, select the accounts to
share with.
3. Click Share  (or Cancel  to back out).
## Deleting Content
IMPORTANT:  Be sure that you really want to delete the content item  because once
deleted, it can’t be retrieved. You would have to re -create it.
To delete any content, in the main Content list (or in a folder’s Content list) click the
Ellipsis  icon at the far right of the content item’s line and then select Delete .

Figure 42: Content Delete  Option
![Figure 42: Content Delete  Option](/images/page047_Im1.png)



<!-- Page 048 -->

48 Chapter 5  • Content Library
1042412 -0001 Revision G

## Data Feeds
Data feeds supply and update external data —such as news, stock quotes, weather,
and traffic information— within a digital signage display. MediaSignage  Server (MSS)
supports RSS 2.0 and other data feeds. Displaying data feeds requires selecting a
program template with data feed support .
For more detailed information on data feeds, see  Appendix  B.
## Creating Data Feeds
1. Click  Content Library > Data Feeds > New Data Feed.

Figure 43: New Data Feed Dialog
![Figure 43: New Data Feed Dialog](/images/page048_Im0.jpg)
2. In the New Data Feed dialog, specify the following required and any  desired
optional settings:
- Name:  Name for the data feed (required) ( 1)
- Key: Unique name to call the data feed (required) ( 2)
- URL: Source location of the data feed  (3)
Click Validate  (4) to check that it’s a valid URL .
If the URL is valid, the URL Validation Successful notification displays the
data  feed code.




<!-- Page 049 -->

# Content Library
1042412 -0001 Revision G  49
If validation fails, check for the following possible problems:
- External network connection is not working
- URL is not entered correctly
- RSS feed no longer exists
- Proxy server or a firewall is preventing external connectivity
- Refresh/Day: Number of times the feed  refresh es (5) each  hour or day
(6)
3. Click Save  (or Cancel  to back out).
## Content Templates
Content templates allow users to customize and display content at their locations.
Adding (Creating) a Content Template
1. Click Content Library > Content Templates > New Template.

Figure 44: New Content Template
![Figure 44: New Content Template](/images/page049_Im0.jpg)




<!-- Page 050 -->

50 Chapter 5  • Conten t Library
1042412 -0001 Revision G

2. In the New Template dialog that opens, n ame the template ( 1).

Figure 4 5: New Template  Name and Background Image
![Figure 4 5: New Template  Name and Background Image](/images/page050_Im0.jpg)
3. Select an image from the scrollable Select Background Image list ( 2) (or first
add a new image by clicking Upload Image  (3), and then select it from the
list).
4. Click Add (or Cancel  to back out).




<!-- Page 051 -->

# Content Library
1042412 -0001 Revision G  51
5. In the Document section of the template workspace that opens, start by doing
the following:

Figure 46: Building the Template – Document Settings
![Figure 46: Building the Template – Document Settings](/images/page051_Im0.jpg)
a. To resize the document ( 1), change the numbers in the fields. Note that
if you see a Padlock  icon between the field s, this means the size for this
template has been locked and the fields are not editable
b. To change the background image  you chose in Step 2 ( 2), click the Trash
Can icon and confirm your deletion, then select  another background
image  from the scrollable list in the New Template dialog that opens .
c. To associate tags with this template, c lick in the Tags  (3) field to open a
scrollable  list and select the desired tags . Or you can simply search for a
tag to jump right to it. ( Remove a tag by clicking the checkmark  by its
name .)
d. To manage permissions for the template , toggle Yes or No (4) to lock all
properties.
6. Now add image  and text  placeholders by doing the following :



<!-- Page 052 -->

52 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure 47: Building the Template – Placeholder Profile Setting s
![Figure 47: Building the Template – Placeholder Profile Setting s](/images/page052_Im0.jpg)
a. Click the Add  button at the top of the template to select from a drop -
down list of preset placeholder profiles and open its  parameters.
Note that at the bottom of the list there is an option to create a custom
placeholder profile. If you click th is option, a dialog opens where you can
name the profile and select the employee attributes to include. When
you do this and click Add , the placeholder appears i n the template and it
is also added to the Placeholders sidebar settings the same as any
selected preset profiles.
IMPORTANT:  Custom placeholder profile s you add to the template are
NOT  added to the placeholder profile list (that opens when
you click Add  at the top of the page ). If you want to use the
same placeholder profile in another template, you must re -
create it for that template.
b. If you have more than one placeholder in your template, select the one
you want to work with by clicking on  it in the Placeholders list and its
settings panel will open.


![Page 52 image](/images/page052_Im1.jpg)


<!-- Page 053 -->

# Content Library
1042412 -0001 Revision G  53
The different types of placeholders will naturally not include all of the
same settings. The various settings should be easy to figure out and work
with. But here are a few worth mentioning specifically:
- With any of the profile placeholders, there will be an Image
Placeholder and Text Placeholder . You can add more Text
Placeholders by clicking the blue plus sign in the Attribute Data field and then selecting the employee info to include from the
drop -down list (that info will be pulled from the employee’s
profile) . If you change your mind about including any of them, just
delete them by clicking their Trash Can  icon.

- Once you insert text into a Text Placeholder, that text will then appear in the Placeholders list rather than “Text Placeholder.” For example:

- If you like how you’ve set up a particular placeholder and want to use it again in your template (either exactly or with just a change or two), save a lot of time by clicking the Duplicate Pages  icon ( 1).
Likewise, if you’re completely unhappy with any placeholder, just click its Trash C an icon ( 2).

c. Save your template often while working on it! Don’t wait to save it until
you leave for lunch or log in to your next Zoom meeting. A ssuming you’d
even remember to save it before either of those two (or similar) events,

![Page 53 image](/images/page053_Im0.jpg)
![Page 53 image](/images/page053_Im1.jpg)
![Page 53 image](/images/page053_Im2.jpg)


<!-- Page 054 -->

54 Chapter 5  • Content Library
1042412 -0001 Revision G

a lot can happen “between now and then” …most of which is not good
where your template and your sanity  are concerned. Save! Save! Save!
7. Finally,  designate the attributes to use in order to select the intended
employees to include in the template  by doing the following:
a. Initially, no attributes settings are showing until you click the blue plus
sign in the Attributes  field:

Figure 48: Building the Template – Opening Attribute  Setting s
![Figure 48: Building the Template – Opening Attribute  Setting s](/images/page054_Im0.jpg)
b. Select the attributes to use as the criteria for which employees are included in this template. All possible attributes that might be found in an employee’s profile are listed here:

Figure 49: Building the Template – Attribute Settings
![Figure 49: Building the Template – Attribute Settings](/images/page054_Im1.jpg)
c. In this template example, which will be used to honor military service employees on Veterans Day, just the Military attribute is selected . Only
employees who have this attribute selected in their profiles— and who
have not opted out from being included in a template —will be included,
with whatever images and info from the placeholder profiles you used in the template being pulled in from their employee profiles.



<!-- Page 055 -->

# Content Library
1042412 -0001 Revision G  55
8. Once you’re done with the Document, Placehold ers, and Attributes settings,
save the template one last time! (Of course, you can always come back and
“tweak it” some more later.)
Adding (Creating) a Simpler Content Template
If you manage a small group or location, or need a template for a singular occ asion
every now and then, it may be easier to create a simpler template that will serve
you just as well.
For example, if you want a template that you will use just once a month to honor just one  person —such as the Associate of the Month —you could create a  template
with the desired design elements (fonts, etc.) that concentrates mostly on Text and Custom Placeholders, and they could be ones that you replace with the specific info/image “by hand” each month (though it’d be easier to pull the employee image from their profile).


Figure 50: Simpler Content Template Example
![Figure 50: Simpler Content Template Example](/images/page055_Im0.jpg)
Viewing the Content Templates Main Page
You have two options for the main page view. Both contain the image, name, and
size of each template  in your account .
The table view  is the usual layout as seen throughout MediaSignage Server : a table
with an alphabetical listing of all the templates . In this view, the Table  icon at the
top right of the table, next to the Search icon, will be blue.



<!-- Page 056 -->

56 Chapter 5  • Content Libra ry
1042412 -0001 Revision G


Figure 51: Content  Template s Page – Table View
![Figure 51: Content  Template s Page – Table View](/images/page056_Im0.jpg)
The thumbnail view  of the Content Templates page looks like this, with its icon at
the top right in blue:

Figure 52: Content Templates Page – Thumbnail View
![Figure 52: Content Templates Page – Thumbnail View](/images/page056_Im1.jpg)
Editing a Content Template
1. On the main Content Templates page, do either of the following:
- If using the table view, click the name of the template you want to edit in
the table row.
- If using the thumbnail view, hover over the thumbnail of the template
you want to edit and then click the Pencil  icon that appears.
The template opens  in its familiar workspace view .



<!-- Page 057 -->

# Content Library
1042412 -0001 Revision G  57
2. Make the desired changes using the same tools used when creating the
template ( see “Adding (Creating) a Content Template ” above) .
3. Click Save  (or Cancel  to back out).
Deleting a Single Content Template
1. On the main Content Templates page, do either of the following:
- If using the table view, at the far right of the row of the template you
want to delete, click the Ellipses  icon.
- If using the thumbnail view, hover over the thumbnail of the tem plate
you want to delete and then click the Ellipses  icon that appears  in the
top-right corner .
2. From the drop -down list, select Delete .

Figure 53: Delete Single Message Template - Thumbnail
![Figure 53: Delete Single Message Template - Thumbnail](/images/page057_Im0.jpg)
3. On the confirmation prompt, click Yes  (or No to back out).
Deleting Multiple  Content Templates at Once
1. On the main Content Templates page, do either of the following:
- If using the table view, hover to the left of the image of the template you
want to delete, and click the checkbox that appears. Then do the same
for all templates in the table that you want to delete.
- If using the thumbnail view, hover over the thumbnail of the template you want to delete and then click the c heckbox  that appears  in the
lower -left corner ( 1). Then do the same for all templates in the table that
you want to delete.
2. Click the Delete  button ( 2) that has descended at the very top of the page.



<!-- Page 058 -->

58 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure 54: Deleting Multiple Templates
![Figure 54: Deleting Multiple Templates](/images/page058_Im0.jpg)
3. On the confirma tion prompt, click Yes  (or No to back out).
## Message Templates
Message templates allow users to customize and display messages at their
locations.
Adding ( Creating) a Message  Template
1. Click Content Library  > Message  Template s.
2. (Conditional) If a topic category that you want to place the message in does
not exist  (is not in the table list) , do the following:
a. Click the Add Topic  option  in the gray menu .


Figure 55: Add Message Template Topic
![Figure 55: Add Message Template Topic](/images/page058_Im1.jpg)




<!-- Page 059 -->

# Content Library
1042412 -0001 Revision G  59
b. In the New Topic dialog, specify the following:


Figure 56: New Topic Example
![Figure 56: New Topic Example](/images/page059_Im0.jpg)
- A name for the topic (required) ( 1)
- Whether to allow (Yes) or deny (No) ( 2) users to enter unlimited
optional messages; if No, use the scrolling field that appears to set
the number of messages allowed (3 )
- (Optional) A time of day to auto archive messages (4 )
c. Click Save  (or Cancel  to back out).
The new topic now appears alphabetically in the main Message
Templates table.
d. To modify a topic, click the Ellipses  icon at the far right of the topic’s row
in the Message Templates t able, click Edit , and then make and save the
desired changes .




<!-- Page 060 -->

60 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure 57: Edit Topic  Option
![Figure 57: Edit Topic  Option](/images/page060_Im0.png)
3. Click a topic  in the table on the main Message Templates page  to place the
new message in .
4. On the Topics > topic name  page, c lick the Add Message Template  option  in
the gray menu .

Figure 58: Add Message Template Option
![Figure 58: Add Message Template Option](/images/page060_Im1.jpg)




<!-- Page 061 -->

# Content Library
1042412 -0001 Revision G  61
The new  template dialog opens:


Figure 59: New Message Template Example
![Figure 59: New Message Template Example](/images/page061_Im0.jpg)
5. In the template dialog that opens, specify the following:
- Text  (1): Message content that is “ permanent ” (not a variable)
- Placeholder Text  (2): Message content that is variable (a person’s name,
etc.)
- # of Characters  (3): Number of characters allowed in the message
- Character Type ( 4): Allow numbers only or any characters
To add more text to the message, click Add More Text  (5) and repeat the
first four bullet items; to delete added text, click the Trash Can  icon ( 6)
- Message Template Preview  (7): Shows a preview of the message
- Message Required ( 8): If set to Yes, this messa ge must be run before any
nonrequired messages
- Default Message  (9): If set to Yes, this message is used if the site has no
other message set/running.
- Auto Archive  (10): Set to Yes to have  the message stop displaying after a
prescribed number of days that you choose from the drop -down  (it will
also then be archived, or deleted)
- Tags  (11): Type a tag name in the Search  field or scroll and select tags
from the list  to add to the message  (click a tag again to deselect it)
6. Click Save  (or Cancel  to back out) .



<!-- Page 062 -->

62 Chapter 5  • Content Library
10424 12-0001 Revision G

Editing a Message Template
You can change any of the options for an existing message template by doing the
following:
1. On the main Message Templates page, click the topic name in the table that
the message template you want to edit is under.
2. On the Topics > topic name  page, click the name of the message  template  you
want to edit  in the list .
3. On the Edit page, make your desire d changes.
4. Click Save  (or Cancel  to back out).
Copying a Message Template
If you want a  new  message template that is very similar to an existing message
template, you can save time by copying the  template and then modify ing it to
create the new one :
1. On th e main Message Templates page, click the topic name in the table that
the message you want to copy is under.
2. On the Topics > topic name  page, click the Ellipses  icon at the far right of the
row for the template you want to copy.

Figure 60: Copy Message Template Option
![Figure 60: Copy Message Template Option](/images/page062_Im0.jpg)
An exact duplicate of the message template appears in the list (with the
current date/time in the Date Created column).
2. Click the name of the template copy to open its Edit page.
3. Make the necessary changes to create the new template you want.
4. Click Save  (or Cancel  to back out).




<!-- Page 063 -->

# Content Library
1042412 -0001 Revision G  63
Archiving (Deleting) a Message  Template  Topic
IMPORTANT:  Archiving a message  template topic is virtually the same as
deleting it in that you cannot retrieve again from anywhere within
the MediaSignag e system . Also, be aware that deleting a topic will
delete all of its message templates and associated messages as
well.
1. On the main Message  Templates  page, click the Ellipses  icon at the far right of
the row for the message template you want to archive (d elete).

Figure 61: Archive  Message Template Topic
![Figure 61: Archive  Message Template Topic](/images/page063_Im0.png)
2. On the confirmation dialog, click Yes  (or No to back out) .
Archiving (Deleting) a Message Template
IMPORTANT:  Archiving a message template is virtually the same as deleting it in
that you cannot retrieve it again from anywhere within the
MediaSignage system.
When you add (create) a message template, you can set it to archive after a
specified number of days. But  if you didn’t set that option  (10, in Figure 59 above)
or, for some reason, you want to archive (delete) it before it’s scheduled to archive, do the following:
1. On the main Message Templates page, click the topic name in the table that
the message you want  to archive is under.
2. On the Topics > topic name  page, click the Ellipses  icon at the far right of the
row of the message  template  you want to archive, then click Archive .



<!-- Page 064 -->

64 Chapter 5  • Content Library
1042412 -0001 Revision G


Figure 62: Archive Message Template
![Figure 62: Archive Message Template](/images/page064_Im0.jpg)
3. On the confirmation dialog, click Yes  (or No to back out).







<!-- Page 065 -->

# Playlists
1042412 -0001 Revision G  65
# Chapter  6
# Playlists
## Creating Playlists
For an overview of how the playlist default templates are designed and work, see
Appendix B .
1. Click Playlists > New Playlist .

Figure 63: New Playlist Option
![Figure 63: New Playlist Option](/images/page065_Im0.jpg)
The New Playlist dialog opens.



<!-- Page 066 -->

66 Chapter 6  • Playlists
1042412 -0001 Revision G


Figure 64: New Playlist Dialog
![Figure 64: New Playlist Dialog](/images/page066_Im0.jpg)
2. Specify the following required and any optional details:
- Name:  (Required) Name for the new playlist  (1)
- Description: Short description of this playlist’s function/contents  (2)
- Tag:  Type a tag name in the Search field or scroll and select tags from the
list to add to the playlist  (click a tag again to deselect it)  ( 3)
3. To make this playlist a “smart ” playlist , add start and e nd play times  by doing
the following .
NOTE:  A “smart ” playlist is one that is run only at a designated time of day.
The program that contains the smart playlist will skip over it if it arrives
at the playlist before the time it is set to run and then will come back
and run it at the designated time. If the program is currently running a piece of content or a “regular” playlist at the time when a smart playlist is set to run, the program interrupts the regular playlist/content, runs the smart playlist, and then resumes what it was previously running.
a. Click the Add Start and End Time button  (4).
b. Select a start time ( 5).



<!-- Page 067 -->

# Playlists
1042412 -0001 Revision G  67
c. To specify when  to stop running  the playlist ( 6), do either of the
following:
- Select Time  option  and s pecify the end time  (7), which will cause
the playlist to keep running in a loop until the specified end time
occurs (even if the playlist in the middle of a  run).
- Select the After Playing  option , which will change the End Time
field ( 7) to the Number of Times  field ; then in this field,  specify
how many times in a row to run the playlist before it stops running.
d. To run the playlist in full screen, check the Full Screen option under
## Settings ( 8).
e. To set additional times for this playlist to run, repeat Steps 3a–3 d.
f. Click Save  (or Cancel  to back out).
After saving the playlist, the Playlists > playlist name  page opens. From
here, you can manage the playlist, as described in the next section.
## Managing Playlists
You can manage a playlist by going to its main page (Playlists > playl ist name ). This
page opens after you initially create and save the playlist (see the previous section,
“Creating Playlists ”). You can also access this page by clicking the playlist name from
the main Playlists list.
The management tasks you can perform are listed in the gray menu panel of the
playlist main page. Click a  menu  option link to open its dialog and complete the
task.


<!-- Page 068 -->

68 Chapter 6  • Playlists
1042412 -0001 Revision G


Figure 65: Playlist Main Page
![Figure 65: Playlist Main Page](/images/page068_Im0.jpg)
## Adding Content
1. Click the Add Content  option.
2. In the Add Content window that opens, select the checkboxes of the content
items you want to include in this playlist.



<!-- Page 069 -->

# Playlists
10424 12-0001 Revision G  69

Figure 66: Add Content  to Playlist  Dialog
![Figure 66: Add Content  to Playlist  Dialog](/images/page069_Im0.jpg)
3. Click Add (or Cancel  to back out).
Adding a Playlist  to another Playlist
This task lets you include  a playlist with in another  playlist . It does not move a
playlist from where it resides (to do that, see “ Moving a Playlist ”). It als o  does not
create a new playlist  (to do that, see “ Creating Playlists ”).
1. Click the Add Playlist  option .
2. In the Add Playlist window that opens, select  the checkboxes of the playlists
you want to include in this playlist.



<!-- Page 070 -->

70 Chapter 6  • Playlists
1042412 -0001 Revision G


Figure 67: Add Playlist to  a Playlist  Dialog
![Figure 67: Add Playlist to  a Playlist  Dialog](/images/page070_Im0.jpg)
3. Click Add (or Cancel  to back out).
## Editing a Playlist
1. Click  the Edit option.
This opens a window that contains the same dialog boxes as when you create
a new playlist  (see Creating Playlists ).
2. Make your desired changes.
3. Click Save  (or Cancel  to back out).
## Managing Tags
1. Click  the Tags  option .
2. In the Edit Tags window that opens, select the checkboxes of new tags to add
and deselect the checkboxes of any tags you want to remove .
3. Click Save  (or Canc el to back out).
## Moving a Playlist
You can move a playlist from the  folder it currently resides in to any other folder.
1. Click  the Move option .



<!-- Page 071 -->

# Playlists
1042412 -0001 Revision G  71

Figure 68: Move Playlist  Dialog
![Figure 68: Move Playlist  Dialog](/images/page071_Im0.jpg)
2. In the Move Playlist  dialog , select the folder you want to move this playlist to.
3. Click Move  (or Cancel  to back out).
## Copying a Playlist
If for some reason you want two identical playlists but with different names or you
simply want a new playlist without creating one from scratch, you can make a copy
of a playlist and the n rename it and then make any other changes to it that you
want .
1. Click  the Copy  option .
2. Go to the main Playlists list and see that the copied playlist is in the list and is
named “ Playlist name  COPY.”

Figure 69: Copy Playlist
![Figure 69: Copy Playlist](/images/page071_Im1.jpg)



<!-- Page 072 -->

72  • Playlists
1042412 -0001 Revision G

3. To change the copied playlist’s name and any other details, click the Ellipses
icon at the far right of the playlist’s row and select Edit .
4. Make your desired changes in the Edit Playlist window.
5. Click Save  (or Close to back out).
## Deleting a Playlist
1. Click  the Delete  option .
2. Click Yes to confirm the deletion (or No  to back out).
## Adding Folders
Folders help you organize playlists.  To add a folder, do the following:
1. Click Playlists > Add Folder.

Figure 70: Add Folder Option
![Figure 70: Add Folder Option](/images/page072_Im0.jpg)
2. In the Folder dialog that opens, specify a name for the folder.
3. Click Save  (or Cancel  to back out).








<!-- Page 073 -->

# Programs
1042412 -0001 Revision G  73
# Chapter  7
# Programs
## Adding (Creating) a Program
1. Click Programs  > Add Program .

Figure 71: Add Program Option
![Figure 71: Add Program Option](/images/page073_Im0.jpg)
2. In the Add Program dialog , specify a name for the program and select a layout
for it.
For info about creating and uploading layouts , see “Layouts .”



<!-- Page 074 -->

74 Chapter 7  • Programs
1042412 -0001 Revision G


Figure 72: Add Program D ialog
![Figure 72: Add Program D ialog](/images/page074_Im0.jpg)
3. Click Save  (or Cancel  to back out).
The Programs > Program  name  window opens.
Set up the program  by continuing with the next section.
## Setting Up/Editing a Program
The Programs > Program  name  window  is where you initially set up or later edit a
program. When you create a new program and save it, this window  automatically
opens. To open this window to edit an existing program, go to the main Programs
page and in the list  click the name of the program that you want to edit.




<!-- Page 075 -->

# Programs
1042412 -0001 Revision G  75

Figure 73: Set Up/Edit Program
![Figure 73: Set Up/Edit Program](/images/page075_Im0.jpg)
1. To simply change the program name, click Rename Program  (1) and then click
Save  (or Cancel  to back out).
2. To delete the program, click Delete Program  (2) and then click Yes  (or No to
back out).
IMPORTANT : Be sure that you really want to delete the program b ecause
once deleted, it can’t be retrieved. You would have to re -create
it.
3. To set this as a favorite playlist, click the star in the upper -right ( 3) so it turns
solid  blue. To deselect it as a favorite, click the star again so it’s just a blue
outline.
4. Do either of the following:
a. To add a new schedule to associate with this program, click the blue Plus
sign ( 4), create  a name for the schedule in the dialog, then click Save  (or
Cancel  to back out).
The new schedule now appears in the Schedules with this Program table
on this page as well as in the list on the main Schedules page , with this
program listed as its filler program.
b. To make this program the filler program for  an existing schedule, go to
the Schedules page, select Edit from the desired schedule’s Ellipses  icon,
select this program from the Filler Program drop -down list, then click
Save  (or Cancel  to back out).
5. To assign content ( playlist, file, URL) to an area  of the layout, or delete  it, do
the following .



<!-- Page 076 -->

76 Chapter 7  • Programs
1042412 -0001 Revision  G

Note that when you first add a new program, all elements of the Playlist and
## Data Feeds tables will read zero (0) or none , accompanied by a red warning
sign, as shown below.

As you assign content to the various areas, these will be replaced with the
number of content items included (or the URLs) .
Playlist/Content File
a. Click a Playlist or URL table item in the Program’s pa ge (Figure  73). For
![a. Click a Playlist or URL table item in the Program’s pa ge (Figure  73). For](/images/page076_Im0.jpg)
example, MainPlaylist .
The page for that item opens:



<!-- Page 077 -->

# Programs
1042412 -0001 Revision G  77

Figure 74: Add/Remove Playlist/Content File
![Figure 74: Add/Remove Playlist/Content File](/images/page077_Im0.jpg)
b. Add a playlist or content file by clicking the appropriate menu item in the
gray sidebar ( 1).
c. To remove a playlist or content file, click the Ellipses  icon at the far right
of that content’s row ( 2), click Remove , and then click  Yes (or No to back
out).
## Data Feeds
a. To change a data feed, from the  Data Feeds  table on the Program’s page
(Figure 73) , click the one you want to change . For example, RSS .
If you want to add a new data feed, just click any item in the Data Feeds
table.
The page for that item opens. For example:



<!-- Page 078 -->

78 Chapter 7  • Programs
1042412 -0001 Revision G


Figure 75: Add/Change Data Feed
![Figure 75: Add/Change Data Feed](/images/page078_Im0.jpg)
b. To add a data feed, click Add Data Feed  (1) in the gray menu bar , fill in
the Data Feed dialog  fields , then click Save  (or Cancel  to back out) .
c. To change the data feed you selected in Step a, select the desired  one
from the Data Feed drop -down list ( 2), wh ich automatically changes to it.
d. To validate a data feed selected in the drop -down list, click the blue
Validate  button (3). You will see either a green Success or red Error
indicator .



To schedule a program to run, see “ Scheduling Programs .”

![Page 78 image](/images/page078_Im1.jpg)


<!-- Page 079 -->

# Programs
1042412 -0001 Revision G  79
## Deleting a Program
IMPORTANT:  Be sure that you really want to delete the program because once
deleted, it can’t be retrieved. You would have to re -create it.
1. In the main Programs list, click the  Ellipsis  icon at the far right of the row  for
the program you want to delete .
2. Select Delete  from the drop -down list .
3. On the confirmation prompt, click Yes  (or No to back out).



<!-- Page 080 -->

80 Chapter 7  • Programs
1042412 -0001 Revision G




<!-- Page 081 -->

# Schedules
1042412 -0001 Revision G  81
# Chapter  8
# Schedules
Creating schedules and scheduling programs  is the final step in creating a
MediaSignage display. You  can create multiple schedules and assign them to
MediaSignage players or player groups.
See “Setting Up/Modifying Players ” f or information about assigning schedules to
MediaSignage players.
Adding (Creating) S chedules
1. Click  Schedules >  Add Schedule .

Figure 76: Add Schedule  Option
![Figure 76: Add Schedule  Option](/images/page081_Im0.jpg)
The Add Schedule d ialog opens.



<!-- Page 082 -->

82 Chapter 8  • Schedules
1042412 -0001 Revision G


Figure 77: Add Schedule Dialog
![Figure 77: Add Schedule Dialog](/images/page082_Im0.jpg)
2. In the dialog, specify  the following information:
- Name  for the schedule
- Filler program  selected from the drop -down list
The filler program plays anywhere in the schedule that does not have
another program scheduled.
3. Click Save  (or Cancel  to back out) .
When you click Save, the Schedules > Schedule name  details page opens. You can do
any of the following tasks on the page right now or come back later at any time to
do them:
- Edit
- Copy
- Delete
- Publish
For information about adding programs to schedules , see “Scheduling Programs. ”
## Editing Schedules
You can change  the name or  filler program of a schedule  by doing the following:
1. On the main Schedules page , click  the Ellipses  icon at the far right of the row
for the schedule that you want to edit.
2. Select  Edit from the drop- down .
3. In the  dialog  that opens, make any desired  changes.
4. Click Save  (or Cancel  to back out).
Copying  Schedule s
To save time, y ou can copy  a schedule  to use it as a template to create a new one
that will be similar .
1. On the S chedule s page , click the schedule  in the list that you want to copy .
2. From the menu options in the left -side gray banner, click Copy .



<!-- Page 083 -->

# Schedules
1042412 -0001 Revision G  83
The page instantaneously changes to the copied schedule, with the word
“COPY” now appearing after the name at the top of the page and in the Name
field. For example:

Figure 78: Copied Schedule Details Page
![Figure 78: Copied Schedule Details Page](/images/page083_Im0.jpg)
NOTE:  The schedule that you copied from remains unchanged.
The copied schedule also now appears in the Schedules list:

Figure  79: Copied Schedule in Schedules List
![Figure  79: Copied Schedule in Schedules List](/images/page083_Im1.png)
3. To change the name of the copied schedule, do either of the following:
- From the Schedule  name  COPY details page, click Edit in the left -side gray
menu banner, change the name in the dialog that opens, and click Save
(or Cancel  to back out).



<!-- Page 084 -->

84 Chapter 8  • Sched ules
1042412 -0001 Revision G

- On the Schedules page, click the Ellipses  icon at the far right of the row
for the copied schedule, click E dit, change the name in the dialog that
opens, and click Save  (or Cancel  to back out).
## Deleting Schedules
Deleting a schedule removes it from any assignments to MediaSignage players or
player groups. It does not delete any programs or program content.
IMPORTANT:  Be sure that you really want to delete the schedule because once
deleted, it can’t be retrieved. You would have to re -create it.
Delete Multiple Schedules at the Same Time
1. In the Schedules list, select the ones to delete (check their c heckboxes) ( 1).

Figure 80: Delete Multiple Schedules
![Figure 80: Delete Multiple Schedules](/images/page084_Im0.jpg)
2. Click the drop- down Delete  button that appears at the top of the page ( 2).
3. Click OK (or Cancel  to back out).
Of course, you could also delete a single schedule in this same way ; or you can
do it as described in the next section.
Delet ing a Single Schedule
1. In the Schedules list, click the Ellipses  icon at the far right of the row for the
schedule you want to delete.
2. Select Delete .
3. Click Yes (or No to back out).




<!-- Page 085 -->

# Schedules
1042412 -0001 Revision G  85
## Publishing Schedules
There are a few  ways you can publish a schedule, as explained here.  With any
method, the schedule is immediately published.
## Using the Details View Page
1. If you are not already on the schedule’s details page, go to it by clicking the
name of the schedule you want to publish in the main Schedules list.
For example:

Figure 81: Select Schedule to Publish
![Figure 81: Select Schedule to Publish](/images/page085_Im0.jpg)
2. Click the Publish  option in the gray menu  bar.



<!-- Page 086 -->

86 Chapter 8  • Schedules
1042412 -0001 Revision G


Figure 82: Select Publish Option
![Figure 82: Select Publish Option](/images/page086_Im0.jpg)
## Using the Schedules Table Publish Column
If you have the Publish heading included in your  Schedules table,  then all you
need to do is click the Publish  button in the row for the schedule you want to
publish .
To include the Publish heading (and make any other heading changes to this
or any other table), do the following:
1. At the top right of the  table, click the Settings  icon.

Figure 83: Table Settings Icon
![Figure 83: Table Settings Icon](/images/page086_Im1.png)




<!-- Page 087 -->

# Schedules
1042412 -0001 Revision G  87
The Table Settings dialog opens , with the appropriate headings for specific
table :

Figure 84: Table Settings Dialog
![Figure 84: Table Settings Dialog](/images/page087_Im0.jpg)
2. Click the type of device you want to modify table settings for: Desktop,
Tablet , or Mobile  (1).
The available heading options for that device type appear ( 2).
3. Select the headings you want to include and deselect any you no longer want
(2).
In this case, b e sure to select the Publish heading.
As you add/delete headings, the Table Header Example ( 3) above the
options changes to show what the table heading row would look like.
4. Repeat Steps 2 and 3 for any other device type you want to set.
After you have made all desired changes, click Save  (or Cancel  to back
out).
The Publish heading/column is now included in the table, with the Publish
buttons in the schedule rows.



<!-- Page 088 -->

88 Chapter 8  • Schedules
1042412 -0001 Revision G


Figure 85: Schedules Table Publish Column
![Figure 85: Schedules Table Publish Column](/images/page088_Im0.jpg)
## Using the Airplane Icon
From v irtually anywhere within the MediaSignage program, you can quickly and
immediately publish a schedule.
1. Locate the Airplane  and Plus -sign icons at the top right of any page, next to
your name and photo , and click the Airplane  icon ( 1).

Figure 86: Publish Airplane Icon
![Figure 86: Publish Airplane Icon](/images/page088_Im1.jpg)
2. From the Programs drop -down list, select the program to publish ( 2).
3. Click Publish Now  (3).



<!-- Page 089 -->

# Schedules
1042412 -0001 Revision G  89
## Scheduling Programs
In television and radio parlance, a “daypart ” is a standard block of time, such as the
morning drive or prime time. TV and  radio stations typically schedule their
programming based on dayparts.
## Adding Programs
1. Set a program to run within a particular schedule by going to the Schedules
page and then clicking the schedule name in the list . (If you need to create a
schedule fir st, see “Adding Schedules .”)
For example:

Figure 87: Select Schedule
![Figure 87: Select Schedule](/images/page089_Im0.jpg)
The schedule ’s details page opens .



<!-- Page 090 -->

90 Chapter 8  • Schedules
1042412 -0001 Revision G


Figure 88: Schedule Details Page
![Figure 88: Schedule Details Page](/images/page090_Im0.jpg)
The page opens in the default view (shown above), which is represented by
the Info icon ( 2). You can also schedule a program while in the Calendar view
(3).
2. To label this schedule as a favorite, click the Favorite sta r  so that it turns gold
(1).
Any schedule that you label here as a favorite will then also have a gold star appear in its row in the main Schedule page table. For example:

To undo its Favorite status, just click the star again, in either place, so that the
gold coloring disappears.
3. Click the Plus -sign icon at the top right of the Programs Scheduled box ( 4,).
The Schedule Program dialog opens.

![Page 90 image](/images/page090_Im1.png)


<!-- Page 091 -->

# Schedules
1042412 -0001 Revision G  91

Figure 89: Schedule Program Dialog
![Figure 89: Schedule Program Dialog](/images/page091_Im0.jpg)
4. Select a program to schedule from the Program drop -down list ( 1).
5. Select a time zone  from the drop- down list or simply select Local to Player  (2).
6. Select start and end dates and times ( 3) for the program to run with in the
schedule.
Click in the Start Time  and End Time fields to open drop -down calendars
where you can select the dates and times. Note that these fields are required.
7. To repeat the program, select an option in the Repeat Frequency section ( 4):
- Never (default):  Program plays just once and never repeats.



![Page 91 image](/images/page091_Im1.jpg)


<!-- Page 092 -->

92 Chapter 8  • Schedules
1042412 -0001 Revision G

- Daily : The program play s at the same time at a specified daily interval
(1). The default is every day. You can change the daily interval and set an
end date (Until…) for the program : Forever (never ends)  (2), Specific date
(select from drop -down calendar ) (3), or After ‘n’ Times (select number
of times to play from drop -down list)  (4).



![Page 92 image](/images/page092_Im0.jpg)


<!-- Page 093 -->

# Schedules
1042412 -0001 Revision G  93
- Weekly: Program play s on the same day s of the week at weekly
intervals. You can select specific days of the week  (1), choose the weekly
intervals  (2), and set an end date for the program  (3).



![Page 93 image](/images/page093_Im0.jpg)


<!-- Page 094 -->

94 Chapter 8  • Schedules
1042412 -0001 Revision G

- Monthly : Program repeat s on the same day of the month at specified
monthly intervals. You can spe cify whether you want the program to
repeat on the same day of the month  (1) (for example, always on the
21st) or on the same day s of the week  (2) (for example, always on the
second and last  Mondays  of the month). You can also set the monthly
repeat interval ( 3) and an end date for the program  (4).



![Page 94 image](/images/page094_Im0.jpg)


<!-- Page 095 -->

# Schedules
1042412 -0001 Revision G  95
- Yearly : Program play s at specified yearly intervals. You can select the
date you want the program to play , choose the interval,  and set an end
date fo r the program .



![Page 95 image](/images/page095_Im0.jpg)


<!-- Page 096 -->

96 Chapter 8  • Schedules
1042412 -0001 Revision G

- Custom : Select specific dates you want the program to play on. Click in
the empty field to open a calendar, select a date, and click Add . Repeat
as necessary.


8. Click Save  to save the program in the schedule  (or Cancel  to back out) .
The program appears on the calendar. Repeat the process to schedule
additional programs.
9. Click Publish Now  to publish the new schedule.
NOTE:  If adding a program to a schedule interrupts a playlist, the playlist will restart
at the beginning  after the program runs .
Schedule a Program in Calendar View
When you click the program you want to schedule from the Schedule s list, the
program’s details page opens in the Info view by defa ult. To schedule the program
in the Calendar view instead, do the following.
1. At the top right of the page, click the Calendar  icon.

Figure  90: Calendar Icon
![Figure  90: Calendar Icon](/images/page096_Im0.png)

![Page 96 image](/images/page096_Im1.png)


<!-- Page 097 -->

# Schedules
1042412 -0001 Revision G  97
By default, the schedule opens to the Monthly calendar view, with the
calendar type  (1) and today’s date ( 2) highlighted :

Figure 91: Calendar Month View
![Figure 91: Calendar Month View](/images/page097_Im0.jpg)
2. To see previous or future months, use the Back  or Forward arrow, located on
either side of the linked word “Today ” in the upper -right corner ( 3).
3. To return to the current month’s calendar from whatever month you are
looking at, just click Today .




<!-- Page 098 -->

98 Chapter 8  • Schedules
1042412 -0001 Revision G

4. To see the details of any program listed on any day, click the program instance
in the day’s square , and an information pop -out opens:

Figure 92: Program Info Pop -Out
![Figure 92: Program Info Pop -Out](/images/page098_Im0.jpg)
5. Use the links at the bottom of the pop -out to edit the program, delete this
occurrence of the program, delete the entire scheduled series of the program (so there is no evidence of it, even in the past), or delete all the following (future) scheduled occur rences of the program.
Clicking Edit takes you to the program’s Edit page, where you can make
changes (see “ Editing/Deleting Scheduled Programs”).
Clicking any of the “Delete” options opens a Confirma tion Required message
to which you must click Yes  (or No to cancel).
6. To see all the same details and make the same edit/delete changes to any program, but use  different viewing options that may better fit your
planning/organizational preferences, simply click Day or Week in the top left
of the page to change from the Month view:

Figure 93: Calendar Day/Week View Options
![Figure 93: Calendar Day/Week View Options](/images/page098_Im1.jpg)




<!-- Page 099 -->

# Schedules
1042412 -0001 Revision G  99
Editing /Deleting  Scheduled Programs
You can modify programs or delete them from the schedule .
1. On the main Schedules page, click the name in the list of the schedule that
contains  the program you want edit or delete.
2. In the Programs Scheduled box, click the  Ellipses  icon at the far right of the
row for the program you want edit or delete .

Figure 94: Modify Scheduled Program
![Figure 94: Modify Scheduled Program](/images/page099_Im0.jpg)




<!-- Page 100 -->

100 Chapter 8  • Schedules
1042412 -0001 Revision G

3. From the drop -down that opens, select any of the following options:

Figure 95: Modify /Delete  Program Options
![Figure 95: Modify /Delete  Program Options](/images/page100_Im0.bin)
- Edit:  Opens the Schedule Program dialog where you can change the
program selection, start/end time, and repeat frequencies. After
modifying, click Save  (or Cancel  to back out).
- Delete This Occurrence: Deletes just the selected scheduled program.
- Delete Series: Deletes listed programs in the Programs Scheduled list.
- Delete All Following:  Deletes all programs in the list starting with the
program immediate after (below) the currently selected one.
4. If you modified the program , click the Airplane  icon in the top ri ght of the
page, select the schedule it’s in from the drop -down list ( 1), and click Publish
Now  (2).

Figure 96: Publish Schedule after Editing Program
![Figure 96: Publish Schedule after Editing Program](/images/page100_Im1.png)



<!-- Page 101 -->

# VOD (Video on Demand)
1042412 -0001 Revision G  101
# Chapter  9
# VOD (Video on Demand)
In addition to providing live TV and video, still images, and scrolling data feeds,
MediaSignage also provides on -demand HD video to any number of screens.  This
service delivers high -impact video content to even the most remote site, allowing
employees to choose when and where to view it.
# VOD s are  organized via groups, with subgroups, categorie s, and s ubcategories
providing extensive hierarchy possibilities .
## Adding a VOD Group
When you click VOD in the left blue menu, you see the main VOD Groups page, displaying a list of all VOD groups currently in your account and summary info for each group.
To add a new VOD group, do the following:
1. Click Add VOD Group  in the gray left menu .

Figure 97: Add VOD Group
![Figure 97: Add VOD Group](/images/page101_Im0.jpg)
2. In the VOD Group dialog that opens, specify a name for the group (required)
and optionally also select locations and (account) g roups to associate with this
# VOD group.
The new group appears alphabetically in the main VOD Groups list.




<!-- Page 102 -->

102 Chapter 9  • VOD (Video on Demand)
1042412 -0001 Revision G

Modifying a VOD Grou p
To change the VOD group name or the locations or groups associated with it:
1. On the main VOD Groups page, click the Ellipses  icon at the far right of the
row for the VOD group you want to modify.
2. Click Edit.
3. In the VOD Group dialog that opens, make the de sired changes.
4. Click Save  (or Cancel  to back out).
## Managing a VOD Group
Once you create a VOD Group, there are a number of ways  you can manage and
organize it.
1. To do any of them, you first need to access the VOD group’s main/summary
page by go ing to the main VOD Groups page and then clicking the El lipses icon
at the far right of the row for the VOD group you want to manage  and then
clicking View  (1). (Alternatively, you can also simply click the VOD group name
in the list ( 2).

Figure 98: Accessing VOD Group Summary Page
![Figure 98: Accessing VOD Group Summary Page](/images/page102_Im0.jpg)
The summary page shows how many account groups ( 1) and locations  (2) are
associated with the VOD group as well as info about categories/subcategories
(3) and videos ( 4) in this VOD group.



<!-- Page 103 -->

# VOD (Video on Demand)
1042412 -0001 Revision G  103

Figure 99: VOD Group Summary Page
![Figure 99: VOD Group Summary Page](/images/page103_Im0.jpg)
Note that if you click one of the category names (e.g., Celebrating You), a
similar summary page opens with the details specific to  that category:

Figure 100: VOD Group Category Summary Page
![Figure 100: VOD Group Category Summary Page](/images/page103_Im1.jpg)




<!-- Page 104 -->

104 Chapter 9  • VOD (Video on Demand)
1042412 -0001 Revision G

2. Use the gray left menu options on any summary  page to do the following:
- Add a category to either a VOD group or a category ( a subcategory)  (5,
Figure 99 above)
- Add a video to a VOD group or category ( 6)
- Edit (change the name of) a VOD group or category ( 7)
- Delete a VOD group or category ( 8)






























<!-- Page 105 -->

# Players: Account
1042412 -0001 Revision G  105
# Chapter  10
# Players: Account
MediaSignage players are added to a MediaSignage network at the time they are
registered to the MediaSignage server .
All Players  Information
Go to  Players > All Players  to see information about existing players and player
groups.

Figure 101: All Players Page
![Figure 101: All Players Page](/images/page105_Im0.jpg)
The following are the default table headings:
- Player or group name
- Group or player description
- Schedule  assigned to the player or group
- Any flags on the player or group
- Status of the player or group
## Adding Player Groups
## Groups  help you organize players, especially if you have a large number of them.
You can also use groups to more easily set up players through inheritance.
1. Click Players > All Players > Add Group .



<!-- Page 106 -->

106 Chapter 10  • Players: Account
1042412 -0001 Revision G


Figure 102: Add Player Group
![Figure 102: Add Player Group](/images/page106_Im0.jpg)
2. Specify a group name in the dialog that opens.
3. Click Save  (or Cancel  to back out).
The group appears in the main Players list, which is ordered alphabetically. You can
click the toggle arrow next to the Name column heading in the table to change the
alphabetization direction (A -Z or Z- A).
## Updating Multiple Players Simultaneously
You can simultaneously make the same tag or time zone change to multiple players .
If You Have Only a Few Players to Update
1. Select the checkboxes  (1) next to each player name.
Use the Filter or Search feature  to locate the desired players if you have  many
players and scrolling would be onerous.



<!-- Page 107 -->

# Players: Account
1042412 -0001 Revision G  107

Figure 103: Multi -Player Update > Small Number
![Figure 103: Multi -Player Update > Small Number](/images/page107_Im0.jpg)
2. Click Update  (2) at the top of the page .
3. On the Players > Bulk Edit page that opens, make your desired changes (add
tags, delete tags, and/or change the time zone) .
4. Click Save  (or Cancel  to back out).
If you need to make changes to the general and/or location Information, in addition
to or instead of the tags and time zone info, then click each player  name  individually
and then click Edit  in the gray side menu  on the player’s page . Make the changes on
the Edit page, then click Save  (or Cancel  to back out). (See “ Editing Basic Player
Information ” for more info.)
If You Have Many  Players to Update
1. To create a CSV file of all your players and their information, click Players > All
Players > Download CSV .
2. Name the file and select a location to save it to.
3. Open the CSV file, m ake the desired changes , and then save it.
4. Click Players > A ll Players > Bulk CSV Update .
5. In the dialog that appears, click Choose File and select the CSV file  you just
saved .
6. Click Upload  (or Cancel  to back out).
Your players are automatically updated with the info from the modified CSV
file.
## Setting Up/Modifying Players
1. In the main Players list ( see Figure 101 above ), click the player you want to set
up or modify.
If the player is in a group, click the group to open the list of players in the
group and then click the player you want.
The player’s main page opens:



<!-- Page 108 -->

108 Chapter 10  • Players: Account
1042412 -0001 Revision G


Figure 104: Player Main Page
![Figure 104: Player Main Page](/images/page108_Im0.jpg)
Although this page is mainly just informational, you can do a few things
concerning screenshots from this page.
In the Recent Screenshots section at the bottom of the page, you can click the following “shortcut” icons along the top banner:


- Camera ( 1): Displays all previously taken screenshots (also accessed via
Player name  > Screenshots > Screenshots)
- Camera -plus sign ( 2): Immediately takes a screenshot, which will be
captured the next time the player checks in (also done via Player name  >
Screenshot s > Take Screenshot)
- Calendar (3 ): Displays all scheduled screenshots and lets you schedule
new ones (also accessed via Player name  > Screenshots > Screenshot
# Schedules)
See “ Taking a Screenshot of a Player ” for mo r e information.
2. Complete the steps in the following sections to set up or modify the player in
any of the following ways:
- Editing Basic Player Information
- Assigning/Unassigning Player Tags
- Moving a Player


![Page 108 image](/images/page108_Im1.png)


<!-- Page 109 -->

# Players: Account
1042412 -0001 Revision G  109
- Deleting a Player
- Rebooting a Player Remotely
NOTE:  At any time while making changes, you can publish  (send to the player)  the
updated  information /settings by clicking the Paper Airplane icon at the top
right of the window.
Editing Basic  Player  Information
1. In the main Players list ( see Figure 101 above),  click the player you want to
![1. In the main Players list ( see Figure 101 above),  click the player you want to](/images/page109_Im0.jpg)
edit.
If the player is in a group, click the group to open the list of players in the
group , and then click the player you want.
2. In the gray menu of the player’s main page, click Edit.
3. On the player’s Edit page, specify  or change any of the information in the
following sections.

Figure 105: Player Edit Page
- General Info: Player name  (1), player description ( 2), schedule assigned
to player  (3), and whether the player inherits settings from the group
settings (if it’s in a group)  (4).



<!-- Page 110 -->

110 Chapter 10  • Players: Account
1042412 -0001 Revision G

- Tags:  Tags assigned to the player are shaded blue and have a checkmark.
If the list of available tags ( 6) is very long, use the Search field ( 5) to find
the tags you want to assign to (or remove from) th e player. Otherwise,
you can ju st use the scroll bar. To add a new tag, or remove an existing
one, click the tag  name .
- Location Info: Name, address, and phone number of the contact person
for this player ( 7). Time zone for the player ’s location  (8). And the site ID
and SAN for the player ( 9, 10).
- Contact Host:  Name  of the Content Host ( 11) associated with this player.
4. Click Save  (or Cancel  to back out).
Assigning /Unassign ing Player Tags
1. On a player’s main page ( Figure 104), c lick the Tags  option in  the gray side
menu.
2. On the Edit Tags page, assign tags to the player by clicking their checkboxes.
3. Unassign any currently assigned tags by deselecting ( clicking ) their checked
boxes.
4. Click Save  (or Cancel  to back out).
NOTE:  Tags can also be assigned/unassigned from the player’s Edit page. See
“Editing Basic Player Information ” just above.
Moving a Player
To move a player into a group or from one group to another, do the following:
1. Click the Move option in the gray side menu  of the player’s main page (Figure
104) .
The Move Player dialog opens.


<!-- Page 111 -->

# Players: Account
1042412 -0001 Revision G  111

Figure 106: Move  Player Dialog
![Figure 106: Move  Player Dialog](/images/page111_Im0.jpg)
2. Select the group to move the player to.
If there is a hierarchy of groups and subgroups, use the Plus  (+) and Minus  (-)
buttons to navigate to the group/subgroup you want.
To create a new group, see “ Adding Groups .”
3. Click Move  (or Cancel  to back out).
Deleting a Player
NOTE : Deleting a MediaSignage player  removes it from the MediaSignage account.
If the p layer is still online and active, it will automatically reregister with the
MediaSignage Server  the next time  it reboots.
1. Click the Delete  option in the gray side menu  of the player’s main page (Figure
104).
2. In the Confirmation Required dialog, click Yes  (or No to back out).
3. Remove the deleted player from the physical network.
Rebooting a Player  Remotely
1. Click the Reboot  option in the gray side menu  of the player’s main page
(Figure 104).
2. In the Confirmation Required dialog, click Yes  (or Cancel  to back out).
The reboot will take place the next time the player checks  in with the server.
To schedule automatic reboots using a custom parameter setting, see  the
Reboot parameter on the  Settings >  Advanced  t abbed  page .



<!-- Page 112 -->

112 Chapter 10  • Players: Account
1042412 -0001 Revision G

Taking a Screenshot of a Player
You may want to take screenshots of players in order to see what is being displayed
on a screen at any given moment, to see what is being displayed on a screen at
certain times throughout the day, or even to share a screen with others.
1. Click the Screenshots  option in the gray side menu  of the player’s main page
(Figure 104).
2. To view all screenshots previously tak en of this player, click Screenshots .
3. To immediately add a screenshot that will be captured the next time the
player checks in, click Take Screenshot .
4. To view all screenshots that are scheduled, click Screenshot Schedules .
5. To schedule a screenshot at a spe cific day/time in the future, click Screenshot
# Schedules, click the New Screenshot Calendar button, and then do the
following in the dialog that opens:
a. Give the schedule a name.
b. Click in the Start Time  field to specify a day and time for the screenshot.
c. Select a time zone  option  for the start time you  chose :
- Local to Player: Takes the screenshot at the selected  time  and
date/day  in the local time zone of every player . For example, when
it is 5 p.m. every Monday  in every player’s  location/time zone.
- Specific  Time Zone : Takes the screenshot of every player at the
time  and date/day  in a specific  time zone, no matter what time (or
date/ day) it is at each individual player ’s location. F or example, you
could set the screenshot to be taken every Monday at 5 p .m. in
your Chicago  headquarter’s U.S. Central time zone —and when the
screenshot is taken  every Monday at 5 p .m. in Chicago , it is also
taken  at all your other offices: Los Angeles (wh ere it is 3 p.m.
Monday) , New York (where it is  6 p.m.  Monday ), London (where it
is 11 p.m. Monday ), and Kyiv (where it is 1 a .m. Tuesday ).
d. Choose the frequency at which you want the screenshot to be repeated (if any).
e. Click Save  (or Cancel  to back out).
6. To delete or edit a scheduled screenshot, click Screenshot Schedules, click the
far-right Ellipses  icon in the row of the desired screenshot, and then do the
following:
a. To delete the screenshot, click Delete  and then click Yes  to confirm the
deletion (or No  to back out).
b. To edit the screenshot’s schedule, click Edit , make the desired changes
(see Step 5 above), and then click Save  (or Cancel  to back out).




<!-- Page 113 -->

# Players: Account
1042412 -0001 Revision G  113
Using Screenshot Analysis
The Smart Scan technology integrated into MediaSignage enables you to analyze
screenshots of players/ screens in your account  locations to keep an eye on  how
they’re functioning  and if they’re having any issues .
To ensure Smart Scan is activated  for an account , go to Admin > Settings and in the
Screen Shots section at the bottom, toggle Smart Scan  to On and then click Save .
When activated, all  screenshots returned for all players on that a ccount are
analyzed.
The dashboard for every account (click on the House icon next to the account name
at the top) includes a Smart Scan  section that gives a bar graph summ ary of the past
seven days of screenshots ( 1) as well as the stats for the current day’s screenshots
(2).

Figure 107: Smart Scan Summary  Info
![Figure 107: Smart Scan Summary  Info](/images/page113_Im0.jpg)
Click See Details  (3) to view more specific information provided by  the
screenshot analysis.



<!-- Page 114 -->

114 Chapter 10  • Players: Account
1042412 -0001 Revision G


Figure 108: Smart Scan Details Info
![Figure 108: Smart Scan Details Info](/images/page114_Im0.jpg)
- 7-Day Trend ( 1): Bar graph giving  you a quick visual of the most recent
week ’s Smart Scans —how many screens were Good, how many received
a Warning  (e.g., a screen with one area not working) , and how many
were flagged with an Error  (e.g., an extreme condition such as the entire
screen blank).
- Today  (2): Good, Warning, Error percentages in today’s screenshots.
- Today’s  Screenshots ( 3): Total number of screenshots taken today .
- Error/Warning/Good Breakdown (4 ): Number of screens receiving each
of the indicators in the most recent w eek.
- Warning/Error Table ( 5): Lists all players whose most recent screenshots
indicate a Warning or Error . Shows the screenshot, the player name, the
scan date, and the player status . At the right end of each row is a link
that takes you  to the player. Use the Filter  button  (6) at the top left of
the table to select what shows in the table (Warnings only, Errors only,
or both).
## Settings
1. From the Players list, select the player you want to view, set, or changes
setting for.
2. Click the Settings  option in the gray left -side menu  of the player’s main page .
3. Complete the tasks in the foll owing sections as desired.



<!-- Page 115 -->

# Players: Account
1042412 -0001 Revision G  115
## Settings
Configuration
When you click Settings  on the player’s main page (Step 2 above), the Player
name  > Settings > Configuration  page opens by default , such as the example
in the following figure.

Figure 109: Player Settings  - Configuration
![Figure 109: Player Settings  - Configuration](/images/page115_Im0.jpg)




<!-- Page 116 -->

116 Chapter 10  • Players: Account
1042412 -0001 Revision G

Set or change the following parameters as desired , then click Save  (or Cancel  to
back out) :
- Inherit from Group  (1): Yes causes the player to inherit settings from the
group (if it is in one)  and deactivates all parameters on the page  (default = No)
- Check-I n Frequency  (2): How often the player checks in with the server
(default = every 5 minutes)
- Show ‘Offline’ After ( 3): Amount of time that the player has not checked in
after which it is shown to be offline (default = 30 minutes)
- Player Volume ( 4): Yes regulates the volume of the player , only  if it has
headphone output and uses speakers directly connected to it ( it does not
control  the volume of the monitor, which is set on the Display  page)  (default=
No)
- Bandwidth Limit  (5): Limits bandwidth usage during unicast (rsync) file
transfers  (default = no limit)
- Local Still Duration  (6): Sets a duration (in seconds) for local content still
images  (no de fault) (Durations for individual still images can be edited o n the ir
Content page)
- Placeholder Limit  (7): Limits the number of local content files played at a local
content spot in a playlist  (no default)
- When to Download ( 8): Limits the time of day that the three types of content
will be transferred  from the server (no default) (S pecify the time range s in 12-
hour format  and include AM or PM; for example, 10 :00 PM to 03 :30 AM)



<!-- Page 117 -->

# Players: Account
1042412 -0001 Revision G  117
Display
The parameters on this page control aspect s of the monitor display .

Figure 110: Player Settings – Display
![Figure 110: Player Settings – Display](/images/page117_Im0.jpg)
Set or change the following parameters as desired, then click Save  (or Cancel  to
back out):
- Inherit from Group  (1): Yes causes the player to inherit settings from the
group (if it is in one) and deactivates all parameters on the page
- Monitor Control  (2): (Smart TV only) Yes  overrides the remote (default = No)
- Type  (3): Correctly  type in the kind  of monitor being used  (supported
monitors are Elo, LG, NEC, Panasonic, Samsung, Sharp, Sony, ViewSonic )
- Volume  (4): Yes regulates the volume of the monitor if the TV is connected to
the player with the included RS232 cable (not the volume of the player , which
is set on the Configuration  page)  (default = No)



<!-- Page 118 -->

118 Chapter 10  • Players: Account
1042412 -0001 Revision G

- Daily Schedule  (5): Sets the times when the monitor is on each day of the
week  (no default) (S pecify the time range s in 12-hour format  and include AM
or PM; for example, 10 :00 PM to 03 :30 AM)
## Tags and Schedule
The parameters on this page control the use of tags and schedules on the player .

Figure  111: Player Settings – Tags and Schedule
![Figure  111: Player Settings – Tags and Schedule](/images/page118_Im0.png)
Set or change the following parameters as desired, then click Save  (or Cancel  to
back out):
- Inherit Tags  (1): Yes causes the pla yer to inherit tags from the group (if it is in
one) (default = No)
- Ignore Tags  (2): Yes causes the player to ignore all tags, even if some are
selected  (default = No)
- Inherited Tags  (3): Lists any tags inherited when you toggled Inherit Tags  to
Yes
- Local Tags  (4): Lists all tags  specifically  assigned to the player
- Inherit  Schedule  (5): Yes causes the player to inherit and use the group’s
schedule (if it’s in a group ) (default  = No )
- Schedule  (6): If you set Inherit Schedule  to Yes, this field will contain the
name of th e inherited  schedule; if you set Inherit Schedule  to No, this field
will contain a drop- down list to choose from of all schedules that exist




<!-- Page 119 -->

# Players: Account
1042412 -0001 Revision G  119
Inheriting
The parameters on this page control what does and does not get inherited from the
group (if the player is in a group).
No matter what inheritance parameters you may have set elsewhere , the settings
on this page immediately override the same settings on ot her pages —in fact, those
other settings will physically change on those pages to match their corresponding
settings here if they were different.

Figure 112: Player Settings – Inheriting
![Figure 112: Player Settings – Inheriting](/images/page119_Im0.jpg)
Set or change the following parameters as desired, then click Save  (or Cancel  to
back out) . All defaults = No.
- Inherit Schedule  (1): Yes causes the player to inherit the group’s schedule
- Inherit Configuration ( 2): Yes causes the player to inherit the grou p’s
configuration
- Inherit Tags  (3): Yes causes the player to inherit the group’s tags
- Inherit Parameters  (4): Yes causes the player to inherit the group’s
parameters
- Inherit Display  (5): Yes causes the player to inherit the group’s display
- Inherit Screenshot Schedule  (6): Yes causes the player to inherit the group’s
screenshot schedule




<!-- Page 120 -->

120 Chapter 10  • Players: Account
1042412 -0001 Revision G

Advanced
The parameters on this page control a number of additional, advanced settings for
your player.

Figure 113: Player Settings – Advanced
![Figure 113: Player Settings – Advanced](/images/page120_Im0.jpg)
Set or change the following parameters as desired, then click Save  (or Cancel  to
back out).
- Inherit from Group  (1): Yes causes the player to inherit these additional
parameters  from the group (if the player is in a group); if this is set to Yes, the
Inherited Custom Settings  (9) parameter  will appear  on the page —otherwise,
it will not (default = No)
- Local Content USB  (2): On enables  local content to be transferred to the
player  from a USB st orage device
- Local Content PW  (3): Sets the password for the local playlist manager on the
player
- Cache Min Free Disk ( 4): Sets the minimum amount of free disk space in
gigabytes before deleting entries in the content cache (default = 20)



<!-- Page 121 -->

# Players: Account
1042412 -0001 Revision G 121
- Cache Delete Aft er (5): Sets the number of days to retain content in the
content cache ; content is deleted if it is not used or scheduled in
MediaSignage during  the set value  (default = 90)
- Reregister Retry  (6): Sets a maximum delay (in number of heartbeats) before
a player  attempts to reregister with the network after a file transfer error
(default = 3, which  is sufficient for most situations)
- Randomize Heartbeat  (7): Randomizes heartbeat signals from MediaSignage
players to the network to prevent large numbers of simultaneous heartbeats
from affecting server performance. Set the value as a percentage of the
heartbeat interval. (default = 0.25 , randomizes the interval b y 25% )
- Reboot  (8): Reboots the player  daily  at the s pecified  time  (HH:MM AM/PM)
- Inherited Custom Settings  (9): This sectio n appears on the page only if Inherit
from the Group is set to Yes and it will list all inherited parameters and their
values
- Custom S ettings  (10): In this  section you can add even more parameters by
clicking the Circle -plus  symbol, specifying the name and value of the
parameter in the Add Custom Setting dialog, and clicking Add  (or Cancel  to
back out); delete any from the list by clicking the Trash  Can icon next to it (for
additional settings and their details, see Appendix A ).
System
The system information  on the Player  > Settings > System page  is just for view ing
purposes and reports on the following:
- General: Basic player info (serial number, MAC address, IP address, storage
stats, etc.)
- Software: Types and versions of software loaded on the player
(MediaSignage, OS, Ruby, Webkit , etc.)
- Hardware: Player hardware info (model name/number, processor, memory,
disk space, USB storage, etc.)
- Updates:  Scheduled player update info



<!-- Page 122 -->

122 Chapter 10  • Players: Account
1042412 -0001 Revision G

Emergency
Here you can create an emergency message to upload that will full screen replace
whatever is currently playing on your monitors.

Figure  114: Emergency Message
![Figure  114: Emergency Message](/images/page122_Im0.jpg)
1. To use the group’s message, set Inherit Emergency Message to Yes (1).
2. To use a message specific to this player, do either of the following:
- Create a message and click Save  to have it ready and waiting.
- Wait to create  (and save)  a message in real time , just before you need  it.
3. To display the message, set Turn On Emergency Message to Yes (2).
The message will continue to display until you revert Turn On Emergency Message
back to No.




<!-- Page 123 -->

# Players: Account
1042412 -0001 Revision G  123
## Software Files
As changes are made to the MediaSignage Server system software, you will be sent
files to use to update your system  via your players . Whenever you  are sent such
files, save them  to your computer and then do the following:
1. Click Software Files > Upload.

Figure 115: Upload Software Files
![Figure 115: Upload Software Files](/images/page123_Im0.jpg)
2. In the Software File dialog that opens , do the following :
a. Select your player type from the drop -down list .
b. Click Choose File, then find and select the latest software update file you
received from Hughes.
c. Click Save  (or Cancel  to back out) .
The file now appears in the main Software Files list, inserted
alphabetically by filename.
To apply the updated software t o your system, s ee the next section,
“Software Updates .”




<!-- Page 124 -->

124 Chapter 10  • Players: Account
1042412 -0001 Revision G

## Software Updates
To update your MediaSignage Server system  whenever you receive software update
files from Hughes , do the following:
1. If not already done, comple te the steps in “Software Files ” above.
2. Click Software Updates > Add .

Figure 116: Add Software Update
![Figure 116: Add Software Update](/images/page124_Im0.jpg)
The Software Update dialog opens.



<!-- Page 125 -->

# Players: Account
1042412 -0001 Revision G  125

Figure 117: Set Up Software Update
![Figure 117: Set Up Software Update](/images/page125_Im0.jpg)
3. In the dialog, do the following :
a. Specify a name for this update ( 1).
b. Optionally create a description about this update ( 2).
c. From the Type drop -down list, select the type of player to be updated
(3).
d. From the Sub Type drop -down select the player subtype to be updated
(4).
e. From the Software  File drop -down, select the software file associated
with this update ( 5). (See “ Software Files ” for more information.)
f. Schedule a day and time for the update to occur ( 6).
g. In the Players section, select the players to update ( 7).
Until you select a player type and software file, this area will show the
message seen in the image above.
h. Click Save  (or Cancel  to back out).
The newly configured update appears in the main Software Updates list, inserted alphabetic ally by the name you assigned it.




<!-- Page 126 -->

126 Chapter 10  • Players: Account
1042412 -0001 Revision G





<!-- Page 127 -->

# Admin: Account
1042412 -0001 Revision G 127
# Chapter  11
Admin : Account
## Users
On t he Admin > User s page you can view a list of all the users in your a ccount. You
can also add users  and impersonate users  as well as modify them by  editing their
settings and delet ing them .
Adding Users
To add a new user, do the following:
1. Click Admin > Users > Add User in the left -side menus .

Figure 118: Add a User
![Figure 118: Add a User](/images/page127_Im0.jpg)
2. In the Create User dialog that opens, optionally upload a photo and then
specify the foll owing information about/for the user :
- First Na me (required)
- Last Name
- Preferred Name
- Email Address  (required)
- Position
- Opt out of all recognition ( Yes/No toggle)
If opt out, all blue Recognition  icons will automatically “pink out”; you
can leave this toggled to No and opt out of  any individual Recognitions  as
noted below.



<!-- Page 128 -->

128 Chapter 11  • Admin: Account
1042412 -0001 Revision G

- Employment Start Date  (can opt out)
- Birth Month and Birth  Day (must supply both or neither ; can opt out )
- Military Service ( Yes/No toggle ; can opt out )
- Role  (required)
- Attributes
Note that attributes are new to MediaSignage Server with this release
and function similar to a tag  in that they  can be used to help organize
users and quickly add them  to a piece of content just by sele cting an
attribute.
- Locations
- Groups
3. Click Save  (or Cancel  to back out).
The new user now appears in the user list, in alphabetical order.
Modifying Users
You can modify users by editing their settings or deleting them.
Find the user in the Users list and click the Ellipses  icon at the far right of that row
(1) to open a drop -down list of options.

Figure 119: Modify a User
![Figure 119: Modify a User](/images/page128_Im0.jpg)
Editing User Settings
1. To change any of a  user’s settings, go to the user’s line entry on the Users
page and select Edit from the drop -down list ( 2).
2. Make the desired changes and then click Save  (or Cancel  to back out).



<!-- Page 129 -->

# Admin: Account
1042412 -0001 Revision G  129
Deleting Users
IMPORTANT: When you delete a user, you can never retrieve it or its data again.
The most you can do is re -create it.
1. To delete a user, go to the user’s line entry on the Users page and s elect
Delete  from the drop -down list ( 3).
2. In the Confirmation Required message that appears, select Yes to delete it (o r
No to back out and keep the account).
Impersonating a User
If a user  is having an issue that the Account  Admin does not also see, the Account
Admin can log in as that user  to better understand what they’re experiencing.
To do this, the Account  Admin “imp ersonates” the user  by doing the following:
1. Go to the user’s line entry on the Users page and select Impersonate from the
drop -down list ( number 4, Figure 117 above ).
![drop -down list ( number 4, Figure 117 above ).](/images/page129_Im0.jpg)
The Users page remains open, but a notice appears on the right side of the
top banner indicating that you are now impersonating the user you selected
and what their role is ( 1):

Figure 120: Impersonat e a User
IMPORTANT:  While you’re impersonating the user, they are still logged in and
can continue to work in the system as usual. But they don’t see
any indication that someone is impersonating them, so if they
need to know for some reason, then they must be told.
2. When you no longer need to impersonate the user, click STOP  (2).
The impersonation notice disappears from your top banner.
NOTE:  While impersonating a user, you may not change their password. Only the
actual user can do that.
## Reports
There are five reports available for your use. They are  all in your Reports list by
default:
- Messages
- Local Playlist Changes
- Content Templates Usage



<!-- Page 130 -->

130 Chapter 11  • Admin: Account
1042412 -0001 Revision G

- Locations Counts
- VOD Watch Counts
All reports in the Report list are automatically kept updated ; whenever you vie w a
report, it will reflect the most current information.
You can rename , download , and email  any report. You also can delete (remove) any
report as well as add it back to the list at any time.
Viewing a Report
To view a report, simply click on its name in the Reports list .
Renaming a Report
1. In the Reports list, click the Ellipses  icon at the far right of the row for the
report you want to rename  and select Edit  from the drop -down list .

Figure 121: Edit Report Name
![Figure 121: Edit Report Name](/images/page130_Im0.jpg)
2. In the Name  field  of the dialog that opens, change the name as desired.
3. Click Save  (or Cancel  to back out).
The report now appears in the Reports list with the new name, realphabetized
accordingly.
Downloading a Report
To download a CSV file of a report ( or, in the case of the Local Playlist Changes
report only, an additional option of a .z ip file), do the following:
1. Click on the report name in the Reports list.



<!-- Page 131 -->

# Admin: Account
1042412 -0001 Revision G  131
2. In the gray menu, click Download CSV  (or Download Zip , if available).

Figure 122: Download Report
![Figure 122: Download Report](/images/page131_Im0.jpg)
3. In the dialog that opens, save the file (or Cancel  to back out).
Emailing a Report
To have a report emailed to you or anyone else  in your account, do the following:
1. In the Reports list, click the Ellipses  icon at the far right of the row fo r the
report you want to have emailed and select Edit from the drop -down list.

Figure 123: Edit Report Option
![Figure 123: Edit Report Option](/images/page131_Im1.jpg)



<!-- Page 132 -->

132 Chapter 11  • Admin: Account
1042412 -0001 Revision G

2. In the dialog that opens, toggle the Email Report  button to Yes:

Figure 124: Edit Report Toggle
![Figure 124: Edit Report Toggle](/images/page132_Im0.jpg)
This expands the dialog so you can set the email parameters .



<!-- Page 133 -->

# Admin: Account
1042412 -0001 Revision G  133

Figure 125: Report Email Parameters
![Figure 125: Report Email Parameters](/images/page133_Im0.png)
- Name  (1): Report name.
- Report Parameters  (2): For information only. Can’t be modified.
- Email Report  (3): Yes/No toggle  (Yes opens additional parameters) .



<!-- Page 134 -->

134 Chapter 1 1 • Admin: Account
1042412 -0001 Revision G

- Start Time/Time Zone  (4): Click in the Start Time  field to open a calendar
and select the date and time the email parameters should take effect.
Select your time zone from the Time Zone drop -down list.
- Add Recipient  (5): Type a recipient name in the Search  field or scroll and
select people  from the list  to receive the report email. Click a name again
to deselect it.
- Repeat Frequency  (6): Sets the following frequency options for how
often and when to send the report email.
Never (default):  Report is emailed just once , on the Start Time ( 4)
day/time , and never repeats.  (Note that a summary of what you set up
appears at the bottom, so you can check that you’ve got it set how you want. In this example: “Never Repeats.”)

Daily:  Email is sent  at a specified daily interval ( Repeat Every ). Set the
daily interval and an end date ( Until… ) for how long to continue sending
the report email : Forever (never ends), Specific Date (select from drop -
down calendar), or After ‘n’ Times  (select number of tim es to send it
from drop -down list).



![Page 134 image](/images/page134_Im0.jpg)
![Page 134 image](/images/page134_Im1.png)


<!-- Page 135 -->

# Admin: Account
1042412 -0001 Revision G  135
Weekly: Email is sent  on the same day (s) of the week at weekly intervals.
Select specific days of the week, choose the weekly intervals  (Repeat
Every ), and set an end date for the emails  (Until…).



![Page 135 image](/images/page135_Im0.jpg)


<!-- Page 136 -->

136 Chapter 11  • Admin: Account
1042412 -0001 Revision G

Monthly : Email is sent  on the same day (s) at specified monthly intervals.
Specify whether you want the email to be sent  on the same D ay of the
Month (for example, always on the 1st and 15th ) or on the s ame Day of
the Week (for example, always on the second  and last  Mondays  of the
month). Also set the monthly repeat interval ( Repeat Every ) and an end
date for the program  (Until… ).



![Page 136 image](/images/page136_Im0.jpg)


<!-- Page 137 -->

# Admin: Account
1042412 -0001 Revision G  137
- Yearly : Email is sent  at a specified yearly  interval ( Repeat Every ). Set the
interval and an end date (Until …). The first time it will be sent is the Start
Date ( 4) you selected , and it will be sent on that same month/day of
every year it is scheduled to be sent.

- Custom : Select specific dates you want the email sent on. Click in the
empty field to open the calendar, select a date, and click Add . Repeat for
as many dates as you desire . Click the Trash Can  icon next to any
selected date to delete it.


3. Click Save  to save t he report email parameters  (or Cancel  to back out) .


![Page 137 image](/images/page137_Im0.png)
![Page 137 image](/images/page137_Im1.jpg)


<!-- Page 138 -->

138 Chapter 11  • Admin: Account
1042412 -0001 Revision G

Deleting a Report
1. In the Reports list, click the Ellipses  icon at the far right of the row for the
report you want to delete  and select Delete  from the drop -down list .

Figure 126: Delete Report
![Figure 126: Delete Report](/images/page138_Im0.jpg)
2. In the confirmation dialog that opens, click  Yes (or No to back out).
Adding a Report
1. In the gray menu on the Reports page, click Add/View  Report .



<!-- Page 139 -->

# Admin: Account
1042412 -0001 Revision G  139

Figure 127: Add Report
![Figure 127: Add Report](/images/page139_Im0.jpg)
2. In the dialog that opens, select  the type of report you want to add from the
drop -down list.  For example:

Figure 128: Report Types Options
![Figure 128: Report Types Options](/images/page139_Im1.png)
3. Click View Report  (or Cancel  to backout).
The report opens in view mode.
The report generated contains all instances in your account of the report type
you selected (in this example, all messages).
4. (Optional) To customize a report by changing/specifying what is  included in it ,
do the following:
a. Click the Filter  button just above the table, on the left:



<!-- Page 140 -->

140 Chapter 11  • Admin: Ac count
1042412 -0001 Revision G


A dialog opens that lets you narrow down what’s included in the report
by selecting from all possible groups, locations, and/or topics as well as
by specifying creation and/or archive date ranges.
b. Select the groups, locations, and/or topics you want included in your
reports by clicking their checkboxes. For example:

If you don’t select any  options in a category, then all options from that
category will be included in the report .
c. Specify the creation and/or archive date ranges (and times) for the
reports you want to include by clicking in the field to open the calendar.
For example :

![Page 140 image](/images/page140_Im0.png)
![Page 140 image](/images/page140_Im1.jpg)


<!-- Page 141 -->

# Admin: Account
1042412 -0001 Revision G  141

If you don’t select any  dates , then all will be included.
d. Click Save  (or Cancel  to back out).
When a report’s content has been customized, the Filter  icon includes a
checkmark:

e. To change the customization of a report after it has been saved (see
Steps 5 and 6 below), click the report name in the main Reports list and repeat Steps 4a –4d above.
5. In the gray menu, click Save Report .

![Page 141 image](/images/page141_Im0.jpg)
![Page 141 image](/images/page141_Im1.jpg)


<!-- Page 142 -->

142 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Figure 129: Save Report
![Figure 129: Save Report](/images/page142_Im0.jpg)
6. In the dialog that opens, name the report, then click Save  (or Cancel  to back
out).  For example:

Figure 130: Name Report
![Figure 130: Name Report](/images/page142_Im1.png)
The new report is added to the main Reports list.



<!-- Page 143 -->

# Admin: Account
1042412 -0001 Revision G  143
## Groups
NOTE:  This section is about groups in relation to locations and users. For
information about player group s, see “ Adding Player Groups .”
Adding a Group
1. Click Admin > Groups > Add Group :

Figure 131: Add Group Option
![Figure 131: Add Group Option](/images/page143_Im0.jpg)
2. In the dialog that opens, specify a name for the group and also an optional
parent group to place this group under.
3. Click Save  (or Cancel  to back out).
Accessing a Group
To open any group page listed on the main Groups page, simply click in the group’s
“square” under the Groups column .



<!-- Page 144 -->

144 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Figure 132: Access a Group
![Figure 132: Access a Group](/images/page144_Im0.jpg)
The g roup page opens, showing all subgroups, locations, and users that are
part of the group:

Figure  133: Specific Group Page
![Figure  133: Specific Group Page](/images/page144_Im1.jpg)
From this page, you can complete the tasks outlined in the following three sections.



<!-- Page 145 -->

# Admin: Account
1042412 -0001 Revision G  145
Renaming a Group
1. To rename a group, on the group’s page, click Edit  in the gray menu:

Figure 134: Group Edit (Rename) Option
![Figure 134: Group Edit (Rename) Option](/images/page145_Im0.jpg)
2. In the dialog that opens, change the name of the group.
3. Optionally, you can select or change the parent group for this group.
4. Click Save  (or Cancel  to back out).




<!-- Page 146 -->

146 Chapter 11  • Admin: Account
10424 12-0001 Revision G

Managing a Group
This option actually entails managing a group’s content.
On the group’s page, click Manage Group in the gray menu:

Figure 135: Group Manage Group Option
![Figure 135: Group Manage Group Option](/images/page146_Im0.jpg)
You are taken to the group’s Content page. See “ Managing Content ” for
information about what you can do there.




<!-- Page 147 -->

# Admin: Account
1042412 -0001 Revision G  147
Deleting a Group
1. On the group’s page, click Delete in the gray menu:

Figure 136: Group Delete Option
![Figure 136: Group Delete Option](/images/page147_Im0.jpg)
2. On the confirmation prompt, select Yes  (or No to back  out).




<!-- Page 148 -->

148 Chapter 11  • Admin: Account
1042412 -0001 Revision G

## Locations
Adding a Single  Location
1. Click  Admin > Locations > Add Location.

Figure 137: Add Location
![Figure 137: Add Location](/images/page148_Im0.jpg)
The Location dialog opens.



<!-- Page 149 -->

# Admin: Account
1042412 -0001 Revision G  149

Figure 138: Location Info  Dialog
![Figure 138: Location Info  Dialog](/images/page149_Im0.png)
2. Specify the following required and any optional details:
- Name (Required) ( 1): Location name
- Time Zone (Required) (2 ): Time zone of the location
- Group ( 3): Group you want the location to be in
- Tags (4): Type a tag name in the Search field or scroll to select the t ags
you want to assign to the location  (click a selected tag to deselect it)
3. Click Save  (or Cancel  to back out).
Adding Multiple Locations Simultaneously
To add a large number of locations, create a CSV file with the locations ’ information
and then upload the file.
Creating the CSV File
1. Create  a CSV file with the following format and location information:
- Create a header row (cell A1) that contains the following headings
(spelled and capitalized exactly  as shown here):
name
timezone



<!-- Page 150 -->

150 Chapter 11  • Admin: Account
1042412 -0001 Revision G

group_name
tags
IMPORTANT:  This header row must  exist. If you don’t make this row a
header but instead just start your list of locations in this
first row, the location listed in this row will not  be added
because this row is ignored by the system.
- Put only one location name on each row
2. Save the fi le with any name you’d like.
Uploading the CSV File
1. In the main Locations page gray menu, click Upload CSV .

Figure 139: Upload Location CSV
![Figure 139: Upload Location CSV](/images/page150_Im0.jpg)
2. In the dialog that opens, browse to find and select the location CSV file you
created , and then click Save  (or Cancel to back out).




<!-- Page 151 -->

# Admin: Account
1042412 -0001 Revision G  151
Downloading a Locations CSV File
To download a CSV file of all the locations (and their details) in your account, do the
following:
1. In the main Locations page gray menu, click Download CSV .

Figure 140: Download CSV
![Figure 140: Download CSV](/images/page151_Im0.jpg)
2. In the dialog that opens, select whether to open or save the file, and then click
OK (or Cancel  to back out).




<!-- Page 152 -->

152 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Viewing a Location’s Information
To view all the information for a location, do either of the following  on the main
## Locations page :
- Click the Ellipses  icon on the far right of the row for the desired location  and
then click View  (1).
OR
- Simply click the location name in the table  (2).

Figure 141: View  Location
![Figure 141: View  Location](/images/page152_Im0.jpg)
- The top section of the page that opens is a summary of the location’s
information. The subsequent sections display the details of the categories.



<!-- Page 153 -->

# Admin: Account
1042412 -0001 Revision G  153

Figure 142: Location  Info Page
![Figure 142: Location  Info Page](/images/page153_Im0.jpg)
Editing  a Location’s Information
To modify the name, time zone, group(s), and/or tag(s) for a location, do th e
following:
1. On the main Locations page, click the Ellipses  icon on the far right of the row
for the location you want to edit.
2. Click Edit.



<!-- Page 154 -->

154 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Figure 143: Edit Location
![Figure 143: Edit Location](/images/page154_Im0.jpg)
NOTE:  If you happen to be on the location’s Information page ( see Figure 142
above), you can simply click the Edit option in the gray side menu.
3. In the dialog that open s, make the desired changes.
4. Click Save  (or Cancel  to back out).




<!-- Page 155 -->

# Admin: Account
1042412 -0001 Revision G  155
Managing a Location
This option actually entails managing a location’s content.
1. On the main Locations page, click the Ellipses  icon on the far right of the row
for the location you want to manage the content of .
2. Click Manage .

Figure 144: Manage Location’s Content
![Figure 144: Manage Location’s Content](/images/page155_Im0.jpg)
NOTE:  If you happen to be on the location’s Information page ( see Figure 1 40
above), you can simply click the Manage  option in the gray side menu.
You are taken to the location’s Content page . See “ Managing Content ” f or
information about what you can do there.




<!-- Page 156 -->

156 Chapter 11  • Admin: Account
1042412 -0001 Revision G

Deleting a Location
1. On the main Locations page, click the Ellipses  icon on the far right of the row
for the location you want to edit.
2. Click Delete .

Figure 145: Delete Location
![Figure 145: Delete Location](/images/page156_Im0.jpg)
NOTE:  If you happen to be on the location’s Information page ( see Figure 142
above), you can simply click the Delete  option in the gray side menu.
3. In the confirmation dialog, click Yes  (or No to back out).
## Tags
On the Admin > Tags page, you can add a new tag, m odify a tag by changing its
name, or delete a tag.
Adding a Tag
1. Click Admin > Tags > Add Tag .



<!-- Page 157 -->

# Admin: Account
1042412 -0001 Revision G  157

Figure 146: Add Tags
![Figure 146: Add Tags](/images/page157_Im0.jpg)
2. In the Tag pop -up that opens, specify a name for the tag.
3. Click Save  (or Cancel  to back out).
The new tag is added to the Tags list , which is in alphabetical order.




<!-- Page 158 -->

158 Chapter 11  • Admin: Account
1042412 -0001 Revision G

Editing  (Renaming) a Tag
1. In the Tags list, click the Ellipses  icon at the far right of the row for the tag you
want to rename ( 1) and then select Edit  from the drop -down list ( 2).

Figure 147: Modify Tags
![Figure 147: Modify Tags](/images/page158_Im0.jpg)
2. In the Tag pop -up that opens, change the name.
3. Click Save  (or Cancel  to back out).
The tag name is changed, and the tag is realphabetized in the Tags list.
Deleting a Tag
IMPORTANT: When you delete a  tag, you can never retrieve it  again. All you can do
is re-create i t. It is also automatically disassociated from any content,
etc., it had been connected to.
1. In the Tags list, click the Ellipses  icon at the far right of the row for the tag you
want to delete  and then select Delete  from the drop -down list ( 3, above ).
2. In the Confirmation Required pop -up that opens, select Yes (or No to back
out).



<!-- Page 159 -->

# Admin: Account
1042412 -0001 Revision G  159
## Fonts
By default, MediaSignage Server provides the Arial font for your use when
creating/modifying content templates . You c an also add more  fonts , from Google
## Fonts.
Adding a Font
1. Click Admin > Fonts > Add Font .

Figure 148: Add Font  Option
![Figure 148: Add Font  Option](/images/page159_Im0.jpg)
2. In the Font dialog that opens, select a font family and font variant from the
drop -down lists.
As you select different options, the “nonsense text” ( “One can never have
enough socks” ) changes to reflect the current selections, so that you can see
how the font looks as you decide which one to add.



<!-- Page 160 -->

160 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Figure 149: Add Font Dialog
![Figure 149: Add Font Dialog](/images/page160_Im0.jpg)
3. When you’ve selected a family/variant combination you want , click Save  (or
Cancel  to back out).
The new font is added to the main Fonts list, which is in alphabetical order.
Note that Arial never appears in the Font lists, and once you add any Google
font, Arial is no longer available for your use.
Deleting Font s
Deleting a Single Font
1. On the main Fonts page, click the Ellipses  icon at the far right of the row of
the font you want to delete.
2. Click Delete  from the list .

Figure 150: Delete Font
![Figure 150: Delete Font](/images/page160_Im1.png)
3. In the Confirmation Required pop -up that opens, click  Yes (or No to back out).



<!-- Page 161 -->

# Admin: Account
1042412 -0001 Revision G  161
Deleting Multiple Fonts at Once
1. On the main Fonts page, hover your mouse to the left of the name of a font
you want to delete to make the hidden checkbox appear, then click in the
checkbox ( 1).

Figure 151: Delete Multiple Fonts
![Figure 151: Delete Multiple Fonts](/images/page161_Im0.png)
2. Repeat Step 1 for every font you want to delete.
3. Click  the Delete  button that descends at the top of the page ( 2).
4. On the confirmation pop -up, s elect OK (or Cancel  to back out).
## Layouts
There are two types of  layout s in MediaSignage Server: an existing layout  th at you
upload and a new layout  t hat you create .
Uploading  an Existing Layout
To upload an existing layout, do the following:
1. Click Admin > Layouts > Upload  Layout .



<!-- Page 162 -->

162 Chapter 11  • Admin: Account
1042412 -0001 Revision G


Figure 152: Upload Existing Layout
![Figure 152: Upload Existing Layout](/images/page162_Im0.jpg)
2. In the Upload Layout (.zip) dialog that opens, do the following:

Figure 153: Upload Layout Dialog
![Figure 153: Upload Layout Dialog](/images/page162_Im1.jpg)
a. Click Choose File  (1) and then select the layout .zip file you want to
upload.



<!-- Page 163 -->

# Admin: Account
1042412 -0001 Revision G  163
The name of the file  faintly  appears to the right of the Choose File button
(2).
b. Specify a name for the layout in the Name  field ( 3).
This can be just an identifier/descriptive name and doesn’t need to be
related to the filename at all.
c. Click Upload  (or Cancel  to back out).
Note that  it may take a little time for a layout file to be processed. Once it is , a
preview of the layout will appear in the Preview column ( 1). Until a layout is
processed, the preview area will be blank ( 2), the size will be 0 bytes,  and a pair of
arced arrows w ill appear to the right of the Last Modified date ( 3).
If the processing seems to take a while, try clicking in the blank preview area; the
process may be done but the preview may not have populated the table.

Figure 154: Upload Layout Processing
![Figure 154: Upload Layout Processing](/images/page163_Im0.png)
Creating a New Layout
Although MediaSignage Server provides a way for you to create new layouts, we
recommend that you take advantage of the many already created layouts provided
that can be uploaded for use.
If for some reason you want or need  to create your own layouts, contact  Hughes
Media Support for assistance.
Modifying  a Layo ut
MediaSignage Server also provides a way for you to modify layouts , but we
recommend  simply upload ing a different layout for your needs. But i f, for some
reason , you want or need modify a layout , contact Hughes Media Support for
assistance.



<!-- Page 164 -->

164 Chapter 11  • Admin: Account
1042412 -0001 Revision G

Deleting a Layout
IMPORTANT: When you delete a  layout , you can never retrieve it.  The most you can
do is upload it again (or re -create it if it was one you created yourself) .
1. On the main Admin > Layouts  page, click the Ellipses  icon at the far right of
the row for the layout you want to delete.
2. Select Delete .

Figure 155: Delete Layout
![Figure 155: Delete Layout](/images/page164_Im0.jpg)
3. On the  confirmation prompt, c lick Yes (or No to back out).
Layout Designs and Specifications
For images of the different default layout and playlist  templates, including  their
specifications, see Appendix B, “ Default Layout & Playlist Templates .”
## Settings
Clicking Admin > Settings  opens the Account Settings dialog where you can set the
following options.  After setting the options, click Save  (or Cancel  to back out).
- Employee Profiles
The default profile image.
- Content Default s
The amount of  time (in seconds ) that every piece of content displays
onscreen .




<!-- Page 165 -->

Admin: Accoun t
1042412 -0001 Revision G  165
- Schedule
Schedule that is used by default  and the time it’s published . (For more
information, see Chapter 7, “ Schedules .”)
- Players
Amount of time (in minutes) that must pass since a player last checked in to
the system before it is considered officially offline
- Messages
Toggle Yes or No to enable/disable messages.
- Screen Shots
Enable the Smart Scan screenshot analysis feature by toggling to On (or Off to
disable it).




<!-- Page 166 -->

166 Chapter 11  • Admin: Account
1042412 -0001 Revision G




<!-- Page 167 -->

# Additional Custom Player Settings
1042412 -0001 Revision G  167
Appendix A
# Additional Custom Player Settings

Parameter  Description  Default Value
enableHTTP  Enables in -application HTTP server
for remote control functions.  False
encryptDrive  Triggers drive encryption by setting
to any value. One -way operation that
cannot be undone from MSS.
lgLogAddConsole  Sends log messages to the
console.log facility as well as the
specified log receiver host.  False
lgLogIp  Sends log messages to the log
receiver host at the specified IP
address.  Unset
slgLogLevel   Sets the level of log messaging  (0 to
5). A higher number indicates more
detail and more messages.  0
maxImageSize  Sets the maximum allowed image
size (in bytes). The default is equal to
a little more than a full -screen 1980 x
1080 image.  10 million
maxVideoKBitsPerSecond  Sets the maximum allowed video
bitrate in kilobits per second. A value
of 0 disables this check.  0
reporting_duration  Determines how often in seconds
that file play reporting is sent to the server. Setting this value to zero (0)
disables reporting.  10800
reporting_duration_offset  Percentage of the duration that
determines the amount of randomness to add or subtract from the duration. This prevents all
players from reporting back at
exactly the same time. This random
percentage cannot exceed 40%.  5
reporting_level  Sets the type of report generated or
turn reporting off.   It can have these
values:
0 reporting disabled
1 detailed reports
2 summarized reports  1


<!-- Page 168 -->

168 Appendix A  • Additional Custom Player Settings
1042412 -0001 Revision G


reporting_max_size





Sets a maximum file size for
playouts.csv. File is deleted
automatically when it reaches set
size to prevent report file from
taking too much disk space. This
value cannot be less than 10k
(102800).  10 MB
reporting_transfer_compression  Sets the rsync compression setting.
Zero (0) equals no compression, 9 is maximum compression. Higher
compression requires more
processing, but less bandwidth.  4
reporting_window_end  Limits reporting to a specific time of
day. Formatted as HHMM  in 24- hour
time. Four numbers are required. Midnight is 0000, and the maximum
is 2359 (11:59 pm). Set in
conjunction with a valid
reporting_window_start.  2359
reporting_window_start  Limits reporting to a specific time of
day. Formatted as HHMM in 24 -hour
time. Four numbers are required.
Midnight is 0000, and the maximum is 2359 (11:59 pm). Set in
conjunction with a valid
reporting_window_end.  0000
resumeDownloadSizeThreshold  Specifies the video file size threshold
after which the M ediaSignage Player
uses the resumable download
method  (resumes the file at the
point where it was interrupted,
rather than restarting it from the
beginning) .

For example, i f you set it to 100 M B,
and a 1 GB file gets interrupted after
101 MB have downloaded, the MSP
resumes downloading it from the
101 MB point. But if only 99 MB have
downloaded when it’s interrupted,
then the MSP completely restarts
the download from the beginning.
Unset



<!-- Page 169 -->

# Additional Custom Player Settings
1042412 -0001 Revision G  169
resume DownloadSizeThreshold  (cont’d.)  If you don’ t set this parameter at all,
any interrupted download restarts
from the beginning no matter how far
it is in the download process.
slingAspectRatio  Specifies the aspect ratio parameter
to the Sling Player Plugin. Valid
values are, 16:9, 4:3, Auto. 16 and 4
can be used in place of 16:9 and 4:3.  Auto
slingboxName  Specifies the name of the Slingbox an
HS1000m will connect to. After discovery, the Slingbox with this name is used. If no name is specified,
the HS1000m will connect to the first
Slingbox it finds.
slingDiscoveryTimeout  Specifies the number of seconds to
wait for a successful discovery.  120
slingDisplayStats  Enables displaying of diag nostic
information. Valid values are O n and
Off. Off
slingIPAddress  Specifies a Slingbox IP address.
Specifying an IP address skips the
discovery phase.  None
slingIPPort  If the IP address is specified, this port
is used.  5001
slingRestartDelay  Sets a value (in seconds) that a
Slingbox will wait to restart when an
error is detected.  15
timeNTPServer  Sets the NTP server address. The
default is where time.google.com
resolves to.  216.239.35.0




<!-- Page 170 -->

170  • Additional C ustom Player Settings
1042412 -0001 Revision G




<!-- Page 171 -->

# Default Layout & Playlist Templates
1042412 -0001 Revision G  171
Appendix B
Default Layout  & Playlist  Templates
Design and Spec Reference
This appendix gives an overview of how the default templates are designed and
work . The “L” in a template name indicates a landscape layout; “P” indicates a
portrait layout.
- Layout L1
- Layout L2
- Layout L3
- Layout L4
- Layout P1
- Layout P2
- Playlists for L1 & L2
- Playlists for L3 & L4
- Playlists for P1
- Playlists for P2
- Time & Date
- RSS Feed
- Weather


<!-- Page 172 -->

172 Appendix B  • Default Layout & Playlist Templates
1042412 -0001 Revision G

Layout L1

Layout L2



![Page 172 image](/images/page172_Im0.jpg)
![Page 172 image](/images/page172_Im1.jpg)


<!-- Page 173 -->

# Default Layout & Playlist Templates
1042412 -0001 Revision G  173
Layout L3

Layout L4



![Page 173 image](/images/page173_Im0.jpg)
![Page 173 image](/images/page173_Im1.jpg)


<!-- Page 174 -->

174 Appendix B  • Default Layout & Play list Templates
1042412 -0001 Revision G

Layout P1

Layout P2



![Page 174 image](/images/page174_Im0.jpg)
![Page 174 image](/images/page174_Im1.jpg)


<!-- Page 175 -->

# Default Layout & Playlist Templates
1042412 -0001 Revision G  175
# Playlists for L1 & L2

# Playlists for L3 & L4



![Page 175 image](/images/page175_Im0.jpg)
![Page 175 image](/images/page175_Im1.jpg)


<!-- Page 176 -->

176 Appendix B  • Default Layout & Playlist Templates
1042412 -0001 Revision G

# Playlists for P1

# Playlists for P2



![Page 176 image](/images/page176_Im0.jpg)
![Page 176 image](/images/page176_Im1.jpg)


<!-- Page 177 -->

# Default Layout & Playlist Templates
1042412 -0001 Revision G  177
Time & Date

RSS Feed



![Page 177 image](/images/page177_Im0.jpg)
![Page 177 image](/images/page177_Im1.jpg)


<!-- Page 178 -->

178 Appendix B  • Default Layout & Playlist Tem plates
1042412 -0001 Revision G


Weather




![Page 178 image](/images/page178_Im0.jpg)
![Page 178 image](/images/page178_Im1.jpg)
