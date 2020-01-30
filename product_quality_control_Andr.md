- [:star: As User I can go through Onboarding to get known with functionality of App](#SPA-01-As-User-I-can-go-through-Onboarding-to-get-known-with-functionality-of-App)

- [:star: As User I can sing in/up via email + password](#spa-02-as-user-i-can-sing-inup-via-email--password)

- [:star: As User I can sing in/up via Google](#spa-03-as-user-i-can-sing-inup-via-google)

- [:star: As User I can Import files from Google Drive](#spa-04-as-user-i-can-import-files-from-google-drive)

- [:star: As user I can import files from Dropbox](#spa-05-as-user-i-can-import-files-from-dropbox)

- [:star: As user I can import files from OneDrive](#spa-06-as-user-i-can-import-files-from-onedrive)

- [:star: As user I can import files from Local Files](#spa-07-as-user-i-can-import-files-from-local-files)

- [:star: As user I can import articles from browsers using share function](#spa-08-as-user-i-can-import-articles-from-browsers-using-share-function)

- [:star: As user I can import text from third-party applications (notes / other notes-taking app)](#spa-09-as-user-i-can-import-text-from-third-party-applications-notes--other-notes-taking-app)

- [:star: As User I can import article via coping and pasting link](#spa-10-as-user-i-can-import-article-via-coping-and-pasting-link)

- [:star: As user I can create the list of my favourite sites](#spa-11-as-user-i-can-create-the-list-of-my-favourite-sites)

- [:star: As user I can can access inApp browser so that i can search and import articles](#spa-12-as-user-i-can-can-access-inapp-browser-so-that-i-can-search-and-import-articles)

- [:star: As User I can access crop menu for imported file from cloud service](#spa-13-as-user-i-can-access-crop-menu-for-imported-file-from-cloud-service)

- [:star: As user I can connect Gmail, so that I will be able to listen to my emails](#spa-14-as-user-i-can-connect-gmail-so-that-i-will-be-able-to-listen-to-my-emails)

- [:star: As user I can open 'Text' screen, where I can create my own document](#spa-15-as-user-i-can-open-text-screen-where-i-can-create-my-own-document)

- [:star: As User I can take Photo of Text, so that I will be able to listen to it](#spa-16-as-user-i-can-take-photo-of-text-so-that-i-will-be-able-to-listen-to-it)

- [:star: As User I can create text, using 'Text' screen](#spa-17-as-user-i-can-create-text-using-text-screen)

- [:star: As User I can see list of items I added before so that I am able to listen to all of them](#spa-18-as-user-i-can-see-list-of-items-i-added-before-so-that-i-am-able-to-listen-to-all-of-them)

- [:star: As User I can Create Folder inside my library](#SPA-19-As-User-I-can-Create-Folder-inside-my-library)

- [:star: As User I can Create Folder inside my library](#spa-20-as-user-i-can-delete-booksarticlestextsfolders-i-added-before)

- [:star: As User I can Listen to items I Added to Library before](#spa-21-as-user-i-can-listen-to--items-i-added-to-library-before)

- [:star: As User I can Pause and Continue listening via Pause/Play button](#spa-22-as-user-i-can-pause-and-continue-listening-via-pauseplay-button)

- [:star: As User I can Skip n seconds Forward/Backwards via Pressing Skip buttons](#spa-23-as-user-i-can-skip-n-seconds-forwardbackwards-via-pressing-skip-buttons)

- [:star: As User I can change speed of listening](#spa-24-as-user-i-can-change-speed-of-listening)

- [:star: As User I can navigate through text via tapping on word, I would like to start listening from](#spa-25-as-user-i-can-navigate-through-text-via-tapping-on-word-i-would-like-to-start-listening-from)

- [:star: As User I can Change Font Size](#spa-26-as-user-i-can-change-font-size)

- [:star: As User I can change voice/languages of listening](#spa-27-as-user-i-can-change-voicelanguages-of-listening)

- [:star: As User I can continue listening from same point I stopped before](#spa-28-as-user-i-can-continue-listening-from-same-point-i-stopped-before)

- [:star: As User I can Listen to text when App is in Background Mode](#spa-29-as-user-i-can-listen-to-text-when-app-is-in-background-mode)

- [:star: As User I can edit text](#spa-30-as-user-i-can-edit-text)

- [:star: As User I can set default listening voice](#spa-31-as-user-i-can-set-default-listening-voice)

- [:star: GENERAL FUNCTIONALITY](#SPA-32-GENERAL-FUNCTIONALITY-Android)

# SPA 01 As User I can go through Onboarding to get known with functionality of App 
[As User I can go through Onboarding to get known with functionality of App](#SPA-01-A- User-I-can-go-through-Onboarding-to-get known-with functionality-of-App)
### Steps
 - Luanch app
 - Onboarding [screen 1] (Welcome to Speechify) Press "I'm ready! Lets go!" button
    - Onboarding [screen 2] (Make Audiobooks) Press "Got it!" button 
    - Onboarding [screen 3] (Save Time. Listen Faster) Press "Got it!" button
    - Onboarding [screen 4] (Sync your library) Press "Got it!" button
    - Onboarding [screen 5] (I'm using Speechify) Select one of the options: as a student, for my work, as a teacher, for my child, for my hobbies, other and can select extra option: I have dyslexia or ADHD. Press "Start Speechify" button
 - Onboarding [screen 1] (Welcome to Speechify) Press "I have already an account" buttom  

### Accepctance criteria
 - Errors during the screens sequence are absent
 - Ucer can login into his account after tappin "I already have an account" button on the first onboarding screen
___________________________________

# SPA 02 As User I can sing in/up via email + password

### Steps
 - Launch app
 - Open "Home" screen
 - Press "Settings" button
 - Press "Sing In" button

User on the "Sing In" screen and has account 

 |Action|Expected result|
|--------|---------------|
|Enter incorrect email|"Email is invalid"  tip ahould appear|
|Clear email field|"Email is empty" tip ahould appear|
|Enter passwors shorter than 6 characters|"Password must contain at least 6 characters" tip should appear|
|Clear password field|"Password is empty" tip should appear|
|Enter correct email and paswword|"Sign In" button should become active|
|Enter correct email and incorrect password, press "Sign In" button|"The password is invalid" popup should appear| 
|Enter correct email and password, press "Sign In" button| User should be logged into his account and redirected to the "Library" screen, all added to the account books should appear in the library. User's email should display instead of "Sing In" button should displayed on the "Settings" screen|

User on the "Sing In" screen and hasn't account 

 |Action|Expected result|
|--------|---------------|
|Press "Create na account" button|User should be redirected to the "Sing Up" screen|
|Actions with incorrect email and password the same as on the "Sing In" screen||
|Enter correct email and twice password|"Sign Up" button should become active|
|Enter correct email and twice password, press "Sign Up" button|New account should be created and user should be redirected to the empty "Library" screen. User's email should display instead of "Sing In" button should displayed on the "Settings" screen|

User on the "Sing In" screen and has account but forgot the password

 |Action|Expected result|
|--------|---------------|
|Press "Forgot Password?" button|User should be redirected to the "Forgot Password?" screen|
|Actions with incorrect email the same as on the "Sing In" screen||
|Enter the email address with which the account was not created and press "Reset Password" button|"Account is not created with this email" popup should appear
|Enter correct email and press "Reset Password" button|"Check email to reset your password" popup should appear|

### Acceptance criteria
 - User should be logged into his account and redirected to the "Library" screen, all added to the account books should appear in the library. User's email should display instead of "Sing In" button should displayed on the "Settings" screen
 - New account should be created and user should be redirected to the empty "Library" screen. User's email should display instead of "Sing In" button should displayed on the "Settings" screen
__________________________________________________

# SPA 03 As User I can sing in/up via Google

### Steps
 - Launch app
 - Open "Home" screen
 - Press "Settings" button
 - Press "Sing In" button
 - Press "Sign In with Google" button

No accounts added before case

 |Action|Expected result|
|--------|---------------|
|Press "Sign in with Google" button|User should be redirected to the "Google Sing in" screen in inApp browser|
|Enter valid account data|InApp Browser closed, user returned to "Library" screen|
|User Enter invalid account data|User got error message|

User has google account/s connected to phone 

 |Action|Expected result|
|--------|---------------|
|Press 'Sign in with Google' button|"Choose an account to continue to Speechify" should appear|
|Press "Back" button|"Choose an account to continue to Speechify" should disappear|
|User chooses account|User is signed in and redirected to the "Library" screen|
|Press "Add another account" button|User should be redirected to the "Google Sing in" screen in inApp browser|
|Press "Privacy Policy/Terms of service" button|User should be redirected to the "Privacy Policy/Terms of service" screen in to the browser|

### Acceptance Criteria 
 - User can Sign In/Up vie Google
______________________________

# SPA 04 As User I can Import files from Google Drive

### Steps
 - Launch app
 - Open "Import" screen

No accounts added before case

 |Action|Expected result|
|--------|---------------|
|Press "Google Drive" button|User should be redirected to the "Google Sing in" screen in inApp browser|
|Enter valid account data|InApp Browser closed, user redirrected to custom drive screen|
|User Enter invalid account data |User got error message |

User has google account/s connected to phone 

| Action | Expected result |
| ------ | ------ |
|Press 'Google Drive' button|"Choose an account to continue to Speechify" should appear|
|Press "Back" button|"Choose an account to continue to Speechify" should disappear|
|User chooses account|User redirrected to custom drive screen|
|User Enter invalid account data |User got error message |

Choose any file of supported format 

|Action| Expected result |
| ------ | ------ |
|User choose file of supported format|User should be redirected to the "Crop" screen|
|Press "Create" button|User should be redirected to the "Library" screen and book should be imported|

### Acceptance Criteria 
 - All supported format files can be imported and listened after it 
_________________________

# SPA 05 As user I can import files from Dropbox

### Steps
 - Launch app
 - Open "Import" screen

User doesn't have Dropbox App installed, doesn't have account connected case:

| Action | Expected result |
| ------ | ------ |
| Choose Dropbox | Dropbox 'Sign In' screen in InApp browser appears |
| Enter valid account data| User redirrected to custom dropbox screen  |
| User Enter invalid account data | User got error message |

User doesn't have Dropbox App installed, has account connected case:

|Action|Expected result|
|------| ------|
| Choose Dropbox | User redirrected to custom dropbox screen |

User has Dropbox App installed, doesn't have account connected case:

| Action| Expected result |
| ------ | ------ |
| Choose Dropbox | User redirrected to the "Sign In" screen in Dropbox app |
| Enter valid account data| User redirrected to custom dropbox screen  |
| User Enter invalid account data | User got error message |

User has Dropbox App installed, has account connected case:

| Action| Expected result |
| ------ | ------ |
| Choose Dropbox | User redirrected to custom dropbox screen |

Choose any file of supported format: 

|Action| Expected result |
| ------ | ------ |
|User choose file of supported format|User should be redirected to the "Crop" screen|
|Press "Create" button|User should be redirected to the "Library" screen and book should be imported|

### Acceptance Criteria 
 - All supported format files can be imported and listened after it 
_________________________

# SPA 06 As user I can import files from OneDrive
### Steps: 
 - Launch app
 - Open "Import" screen

 No accounts added before case:

  | Action| Expected result |
| ------ | ------ |
| Choose Dropbox | Dropbox 'Sign In' screen in InApp browser appears |
| Enter valid account data| User redirrected to custom dropbox screen  |
| User Enter invalid account data | User got error message |

User has google account/s connected to phone:

  | Action| Expected result |
| ------ | ------ |
| Choose OneDrive | User redirrected to custom drive screen |

Choose any file of supported format: 

|Action| Expected result |
| ------ | ------ |
|User choose file of supported format|User should be redirected to the "Crop" screen|
|Press "Create" button|User should be redirected to the "Library" screen and book should be imported|

### Acceptance Criteria 
 - All supported format files can be imported and listened after it 
_________________________

# SPA 07 As user I can import files from Local Files

### Steps
 - Launch app
 - Open "Import" screen

|Action| Expected result |
| ------ | ------ |
|Press "Local Files" button|Permisson popup should appear|
|Press "Deny" button|Permisson popup is disappeared and user should be redirected to the "Import" screen|
|Press "Accept" button|User should be redirected to the custom local files screen|

Choose any file of supported format: 

|Action| Expected result |
| ------ | ------ |
|User choose file of supported format|User should be redirected to the "Library" screen and book should be imported|

### Acceptance Criteria 
 - All supported format files can be imported and listened after it 
_______________________

# SPA 08 As user I can import articles from browsers using share function

### Steps
  - Install App
  - Open article in browser
  - Press Share button 
  - Choose Speechify (If not used before it is in 'more' list)

| Action| Expected result |
| ------| ------ |
|Tap anywhere|Share popup should disappeared|
|Press "Listen Later" button|Article saved to the library|
|Press "Listen now" button| User should be redirected to the library and popup fro saving shared article should appeared|
|Press "x" button| Popup with shared article should disaapeared and article should not be added to the library|
|Press "Import to library" button| Popup with shared article should disaapeared and article should be added to the library|

### Acceptance Criteria 
 - User can import any articles from browser
 - importing should be within max 1min even on low internet connection. If it takes more time, it should mark the file as failed.
____________________

# SPA 09 As user I can import text from third-party applications (notes / other notes-taking app)

### Steps:
 - Open any note-taking app;
 - Press Share button on the note, you want to import;
 - Choose Speechify (If not used before it is in 'more' list);

|Action| Expected result |
| ------ | ------ |
|Tap anywhere|Share popup should disappeared|
|Press "Listen Later" button|Article saved to the library|
|Press "Listen now" button| User should be redirected to the library and popup fro saving shared article should appeared|
|Press "x" button| Popup with shared article should disaapeared and article should not be added to the library|
|Press "Import to library" button| Popup with shared article should disaapeared and article should be added to the library|

### Acceptance Criteria 
 - User can import any articles from browser
 - importing should be within max 1min even on low internet connection. If it takes more time, it should mark the file as failed.
 ______________________

# SPA 10 As User I can import article via coping and pasting link

### Steps
 - Install
 - Open any articles in the browser
 - Copy link of the article

|Action| Expected result |
| ------ | ------ |
|Launch app|Import arctile popup should appear|
|Press "x" button| Popup with shared article should disaapeared and article should not be added to the library|
|Press "Import to library" button| Popup with shared article should disaapeared and article should be added to the library|

### Acceptance Criteria 
 - User can import any articles from browser
 - importing should be within max 1min even on low internet connection. If it takes more time, it should mark the file as failed.
 ___________________________

# SPA 11 As user I can create the list of my favourite sites

### Steps
 - Launch app
 - Open "Import" screen
 - Press "Article" button

|Action| Expected result |
| ------ | ------ |
|Press "+" button|"Enter website URl" popup should appear|
|Press "Cancel" button|"Enter website URl" popup should disappear|
|Enter URL of website and press "Add" button|Site should be added to the list|

### Acceptance Criteris
 - User shoould be abble to add his favourite sites to the list
_____________________________

# SPA 12 As user I can can access inApp browser so that i can search and import articles 

### Steps
 - Launch app
 - Open "Import" screen
 - Press "Article" button 

|Action| Expected result |
| ------ | ------ |
|Tap on the search field|USer should be able to enter text into the search field|
|Enter text in the search field and press "Search" button|Founed articles should display in the inApp browser|
|Press "x" button|innApp browser should close and User should be redirected to the "Article" screen|
|Tap on the one of the founded articles and press "Speechify This" button|User should be redirected to the library and article should be added to the library|

### Acceptance Criteria 
 - User can import any articles from inApp browser
 - importing should be within max 1min even on low internet connection. If it takes more time, it should mark the file as failed.
____________________________________

# SPA 13 As User I can access crop menu for imported file from cloud service

### Steps:
 - Import file from any cloud-service 
 - Crop file 
 - Press 'Create' button

### Acceptance Criteria 
 - User can open crop menu, crop file according to his preferences and add cropped file to library
_______________________________________

# SPA 14 As user I can connect Gmail, so that I will be able to listen to my emails

### Steps
 - Launch app
 - Open "Home" screen
 - Press "GMAIL" button

No accounts added before case

|Action|Expected result|
|--------|---------------|
|Press "GMAIL" button|User should be redirected to the "Google Sing in" screen in inApp browser|
|Enter valid account data|InApp Browser closed, user redirrected to custom gmail screen|
|User Enter invalid account data |User got error message|

User has google account/s connected to phone 

| Action | Expected result |
| ------ | ------ |
|Press 'Gmail' button|"Choose an account to continue to Speechify" should appear|
|Press "Back" button|"Choose an account to continue to Speechify" should disappear|
|User chooses account|User redirrected to custom gmail screen|
|User Enter invalid account data |User got error message|
|Press "Back" button|User should be redirected tothe "Home" screen|
|Tap on the one of the emails|Screen with selected email should be opened|
|Press "X" button|Screen with selected email should be closed and user should be redirected to the castom gmail screen|
|Press "Speechify This" button|User should be redirected to the "Library" screen and selected email should be imported to the library|

### Acceptance Criteria
 - User can import any email from his gmail
______________________________________________________

# SPA 15 As user I can open 'Text' screen, where I can create my own document

### Steps: 
 - Open 'Text' Screen 
  Expected result: Screen with such options appear : 
 - Document title field
 - Text field 
 - Listen button 
 - Paste button
 - Add To Library button

### Acceptance Criteria 
 - User can open Text screen, all core features can be accessed and are working properly
_______________________________________

# SPA 16 As User I can take Photo of Text, so that I will be able to listen to it 

### Steps
 - Launch app
 - Open "Scan" screen

First launch case 

 | Action | Expected result |
| ------ | ------ |
| Open 'Scan' screen | 'Speechify would like to access your camera' pop-up appears |
| Click 'Deny'| pop-up closed, permission is not given, user can't take photos untill he gives it |
| User click 'Allow' button| pop-up closed, permission is given, user can take photos |

User gave permissions 

 | Action | Expected result |
| ------ | ------ |
| Press on photo button | Photo is taken  |
| User click 'Create' button| Photo is processed and added to Library, user redirected to Library |
______________________________________________

# SPA 17 As User I can create text, using 'Text' screen

### Steps
 - Open "Text" screen

  | Action| Expected result |
| ------ | ------ |
| Click on 'Document title' field | Cursor is on 'Document title' field, keyboard appears |
| Set name for your document | Appropriate text is typed and shown. Any symbols allowed |
| Click Done  | Keyboard disappears, name, that was set is shown |
| User click 'Listen now' | Article saved to chosen folder, Browser goes to background mode, User redirected to Library screen in Sceechify App |
| Click on 'text' field | Cursor is on 'text' field, keyboard appears |
| Type any text | Appropriate text is typed and shown. Any symbols allowed |
| Click Done  | Keyboard disappears, text, that was typed is shown |
| User has text copied to clipboard | Paste button is active|
| Click 'Paste' button | Text, that was in clipboard is pasted to 'text' field|
| Click 'Listen' button | User should be able to dictate|
| Click 'Add To Library button' button | New document in Library is created ( in chosen folder, root is default) Title is given either by user ( 'Document title' field) Or if it was empty, title is automaticly made from beginning of the text|

### Acceptance Criteria 
 - User can set name for his document
 - User can paste text into his document
 - User can add to library dicument, he created
 ______________________________

# SPA 18 As User I can see list of items I added before so that I am able to listen to all of them 

### Steps:
 - Launch App
 - Open Library 
 
 Expected result: User can see list of previously added items 

### Acceptance Criteria 
 - Library screen successfully opens, all items that were previously added can be seen and accessed
____________________________

# SPA 19 As User I can Create Folder inside my library  

### Steps
 - Launch app
 - Open "Library" screen

|Action| Expected result |
| ------ | ------ |
|Press "Create new folder" button|"New folder" popup should appear|
|Press "Cancel" button|"New fodler" popup should disappear|
|Press "OK" button and don't enter title of the folder|Folder with default title should be added to the library|
|Enter title of the folder and press "OK" button|Folder with entered title should be added to the library|

### Acceptance Criteria 
 - Folder can be created and named 
 - Folder appears inside appropriate folder 
________________________________

# SPA 20 As User I can Delete Books/Articles/Texts/Folders I added before

### Steps
 - Launch app
 - Open Library screen
  - Tap on three dots icon near any Item 
 - Choose Delete 
 Expected result: Appropriate item deleted from library

### Acceptance Criteria 
 - Appropriate item is deleted from Library
________________________________________

# SPA 21 As User I can Listen to  items I Added to Library before

### Steps
 - Launch App
 - Open Library screen
 - Tap on item to listen to 
 
 Expected result: Listening started, appropriate text is highlighted 

 ### Acceptance Criteria 
 - User can open any book from Library and start listening to it 
______________________________________

# SPA 22 As User I can Pause and Continue listening via Pause/Play button 

### Steps
 - Start listening

 | Action| Expected result |
| ------ | ------ |
| User press Pause | Listening Paused |
| User press Play | Listening continues from where it stopped |

### Acceptance Criteria 
 - User can Press/pause his listening
 - Listening continues from where it stopped 
 - Play/Pause cause appropriate actions 
_____________________________________

# SPA 23 As User I can Skip n seconds Forward/Backwards via Pressing Skip buttons

### Steps
 - Start listening

| Action| Expected result |
| ------ | ------ |
| User press Forward skip | Listening skips forward for n seconds, Appropriate text is highlighted, listening continues from appropriate point |
| User press Backwards skip | Listening skips backwards for n seconds, Appropriate text is highlighted, listening continues from appropriate point |

### Acceptance Criteria 
 - User can skip listening for appropriate interwals
 - Listening continues from appropriate point
 _________________________

# SPA 24 As User I can change speed of listening

### Steps
 - Start listening
 - Press "Speed" button

| Action| Expected result |
| ------ | ------ |
| User changes speed via dragging | Speed and time remaning indicator are appropriately changed, correct speed is shown  |
| User changes speed via tapping | Speed and time remaning indicator are appropriately changed, correct speed is shown |
| User changes speed via clicking '+' icon | Speed and time remaning indicator are appropriately changed, correct speed is shown  |
| User changes speed via clicking '-' icon | Speed and time remaning indicator are appropriately changed, correct speed is shown |
 N.B. : Speed changes apply only to book, you are listening to, other remain default
 
### Acceptance Criteria 
 - Speed can be changed 
 - Appropriate speed is set after changing
_____________________________

# SPA 25 As User I can navigate through text via tapping on word, I would like to start listening from 

### Steps
 - Start listening
 - Tap on any word in text you are listening
 Expected result: Listening continues from appropriate word, appropriate word is highlighted

### Acceptance Criteria 
 - Naviagating throgh text via tapping is possible
 - Nothing is changed except from listening position highlighting and listening poing
_________________________________

# SPA 26 As User I can Change Font Size

### Steps
 - Start listening
 - Press "Display & Text Size" button

 | Action| Expected result |
| ------ | ------ |
| User click uppercase letter | Font size gets bigger, user can click this letter untill he reaches limit, after that button becomes N/A  |
| User click lowercase letter | Font size gets smaller, user can click this letter untill he reaches limit, after that button becomes N/A |

### Acceptance Criteria 
 - User can make font size bigger 
 - User can make font size smaller 
________________________________________

# SPA 27 As User I can change voice/languages of listening

### Steps
 - Start listening
 - Press "Voices & Languages" button

| Action| Expected result |
| ------ | ------ |
|Tap on one of the voices from the list|Reading should continue with selected voice|
|Tap on one of the languages from the list|Reading should continue with selected languages|
|Press "x" button|"Voices & Languages" screen should be closed|

### Acceptance Criteria 
 - User can set any of avaliable for him listening voices/languages
_______________________________________________

# SPA 28 As User I can continue listening from same point I stopped before

### Steps
 - Start listening

### Acceptance Criteria 
- After ANY actions, except from reinstalling an app and permanently deleting book user can continue listening from same point he stopped before
_________________________________________________

# SPA 29 As User I can Listen to text when App is in Background Mode 

### Steps: 
 - Start listening
 - Put App in background mode 
 Expected result: Listening continues 

### Acceptance Criteria 
 - User can continue listening to the book, when application is in background mode 
________________________________________________

# SPA 30 As User I can edit text

### Steps:
- Start listening 
- Press "Display & Text Size" button
- Press "Edit text" button

 | Action| Expected result |
| ------ | ------ |
| User click on place in text, he wants to edit | Keyboard appears, cursor is at appropriate place |
| User types some text | Typed text is shown |
| User click 'Save' button| Changes are saved, user returned to default listening screen|
| User click 'Cancel' button| Changes are undone, user returned to default listening screen |

### Acceptance Criteria 
 - User can make any changes he wants to text
 - User can save changes, he made
__________________________________________________

# SPA 31 As User I can set default listening voice

### Steps
 - Open Settings screen
 - Open Listening Preferences screen
 - Press "Default Listening Language" button

 | Action| Expected result |
| ------ | ------ |
| Click on search bar | Cursor is on serach bar, keyboard appears |
| Type some text | Screen constantly refreshes, according to your searching query |
| Choose any voice  | Voice is set by default |

### Acceptance Criteria 
 - User can set default listening voice
________________________________________________
# SPA 32 GENERAL FUNCTIONALITY Android
________________________________________________

# All functionality can be accessed without signing In 
User can make ANY of described above actions without signing in. Sign In is required ONLY for sync with your account, which is described below. 
    
# Sync functionality flow

### User Sign Up 
Expected result : Books sync with created account (Both added before AND Added after signing up). Synced books become avaliable on ANY platform, when user signs in into this account.
    
### User Sign In
Expected result : Books sync with created account (Both added before AND Added after signing in). Books, that are already connected to this account, are added to library. Synced books become avaliable on ANY platform, when user signs in into this account.
### User Log Out
Expected result: All books, that were Synced with this account disappear from library. None of further added books will be synced with account, from which user signed out. All synced books must be accessed after repeated Sign In. 

_____________________________________

# When there is a copied Link or Text in Clipboard and user opens App pop-up appears to add this text/article to library
Rough text case 
 ## Steps: 
 1) Copy any text 
 2) Open Application 

 | Action| Expected result |
| ------ | ------ |
| Open App | Text Detected pop-up appears |
| Click 'Cross' button| pop-up closed, text not added to Library |
| User click 'Create New File' button| pop-up closed, text added to Library |
    
Link case
## Steps: 
 1) Copy link to an article   
 2) Open Application 
 
  | Action| Expected result |
| ------ | ------ |
| Open App | Link Detected pop-up appears |
| Click 'Cross' button| pop-up closed, article not added to Library |
| User click 'Create New File' button| pop-up closed, article added to Library |
 ### Acceptance Criteria 
 - User gets proper pop-ups when he has link/text copied to clipboard 
 - User can import article/text using those pop-ups
