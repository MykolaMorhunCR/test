   
   -------------------------------
   
# SPIOS . As a User I can Share Books/Articles/Texts/Folders I added before
 ### Steps: 
 - Launch App
 - Open [Library](#SPIOS-0301-As-a-User-I-can-see-list-of-items-I-added-before-so-that-I-am-able-to-listen-to-all-of-them)
 - Tap on three dots icon near any Item 
 - Choose Share 
 - default iOS 'share screen' opens, where you can choose how you want to share
 - Choose a way to share
 
  Expected result: Appropriate file is shared. Link is viable and can be opened. 
  
 ### Acceptance Criteria 
 
 - User can share any item he wants 
 - Appropriate item is shared, link is viable 
 
    -------------------------------

# SPIOS . As a User I can Rename Books/Articles/Texts/Folders I added before

  ### Steps: 
 - Launch App 
 - Open [Library](#SPIOS-0301-As-a-User-I-can-see-list-of-items-I-added-before-so-that-I-am-able-to-listen-to-all-of-them)
 - Tap on three dots icon near any Item 
 - Choose Rename
 
   | Action| Expected result |
| ------ | ------ |
| Choose Rename  | Rename pop-up appears with text field and two buttons : 'cancel' and 'rename'. Also keyboard appears, cursor is on text field. |
| Enter any text | Appropriate text is typed and shown |
| CLick 'cancel' button | No changes are made, pop-up is closed |
| Click 'Rename' button | Text, which is in text field is set as name of a file, pop-up is closed |

  ### Acceptance Criteria 
 
 - User can set any name of a file he wants 
 - After chancing name on a file only name of appropriate file  is changed 

 
      -------------------------------
      
# SPIOS . As a User I can Search through Books/Articles/Texts/Folders I added before

  ### Steps: 
 - Launch App 
 - Open [Library](#SPIOS-0301-As-a-User-I-can-see-list-of-items-I-added-before-so-that-I-am-able-to-listen-to-all-of-them)
 - Pull down list in root folder 
  - Tap on a search field

   | Action| Expected result |
| ------ | ------ |
| Tap on a search field | Keyboard appears, cursor is on search field. |
| Enter any text | Appropriate text is typed and shown, list is changed according to search query |
| CLick 'cancel' button | User is returned to library|
| Click on any item | Listenign screen for appropriate item is opened |

  ### Acceptance Criteria 
 
 - User can search and open any item in Library 
 
       -------------------------------
       
 # SPIOS . As a User I can Add Cover Photo ( Via Local storage / Taking Photo) to Books/Articles/Texts 
 
  ### Steps: 
 - Launch App 
 - Open [Library](#SPIOS-0301-As-a-User-I-can-see-list-of-items-I-added-before-so-that-I-am-able-to-listen-to-all-of-them)
 - Tap on three dots icon near any Item 
 - Choose Add cover photo 
 
  Add photo from local storage
  
     | Action| Expected result |
| ------ | ------ |
| Press 'image' icon | 'Photos' inApp view is opened |
| User chooses some photo | Photo that is chosen is highlighted with blue |
| User clicks on photo, he chose before| Highlighting and number disappear only appropriate photo |
| User chooses  >1 photos  | Error 'max photo limit reached' appears |
| User clicks 'Select' button| Photo he chose can be seen in Preview screen  |
| Click 'check' button | Photo is set as cover photo of appropriate file |
| User clicks 'cross' button| User redirected back to photo screen |

Take photo with camera

 | Action | Expected result |
| ------ | ------ |
| Press on photo button | Photo is taken, preview is shown  |
| Click 'check' button | Photo is set as cover photo of appropriate file |
| User clicks 'cross' button| User redirected back to photo screen |

Note: Permission flow is similar to (Scan)[]

  ### Acceptance Criteria 
 
 - User can set any cover photo for any file he wants 
 
        -------------------------------
       
 # SPIOS . As a User I can access Multi-Selection functionality via clicking and holding any Folder/Text inside my Library
 
  ### Steps: 
 - Launch App 
 - Open [Library](#SPIOS-0301-As-a-User-I-can-see-list-of-items-I-added-before-so-that-I-am-able-to-listen-to-all-of-them)
 - Tap and hold on any item
 
 Expected result: multi-selection menu appears. On the left of each non-selected item appears green 'plus' icon, which changes to blue checkmark on tap; folder, share and delete icons appear; 'cancel' and 'see all' buttons appear; item counter appear.
 
   | Action| Expected result |
| ------ | ------ |
| User selects >1 item | Share button disappears, counter is appropriately changed |
| User clicks 'cancel' | Multi-selection menu is closed, no changes are made |
| User clicks share button| iOS share menu opens |
| User clicks 'See All' button  | Screen with all chosen before items appear (folders are marked with folder icon). User can click back to return to multi-selection menu |
| User clicks 'Delete' button| Appropriate items are moved to 'deleted items' menu from Library  |
| User clicks 'folder' button | 'Choose your folder' menu appears |
| User clicks 'cross' button| User redirected back to Library |
| User clicks 'See All' button  | Screen with all chosen before items appear (folders are marked with folder icon). User can click back to return to 'Choose your folder' menu |
| User clicks on any available folder | Appropriate items are moved to chosen folder. User is redirected to chosen folder |
| User clicks on 'Create new folder' button | 'Create new folder' (menu)[] appears |
  
   ### Acceptance Criteria 
 
 - User can access multi-selection menu, where he can select as many items as he wants and make with them available actions. 
 
 -------------------------------

 
  
