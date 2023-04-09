# Assignment 01: Heuristic Evaluation - Maleeha Zaman, DH110
## Tentative Title: Family Memory Archival 
>When my parents immigrated to America from Pakistan, they were only able to bring a few pictures with them. Whenever we did travel back to Pakistan to visit my grandparents, we found most of the photos had been lost during the moving process or misplaced. Years worth of nostalgic stories my parents told me about their younger days had been lost and it was sad they weren't able to share these memories with me. Although memories today have become digitized and encapsulated in our phone camera rolls, there is still a struggle to fully preserve those old photos our parents took on film all in one place. I plan to contribute through this UX project in order to preserve precious family memories to be shared across future generations and viewed at the user's convenience, strengthening the connection between us and our loved ones. 

## Competitor A: Collectionaire
![Collectionaire homepage](collectionaire-screenshot.png)
View the full site here: [Collectionaire](https://collectionaire.com/)
>Collectionaire is a website with a mission to document family history and archive immediate family's memories. To do this, users can make an account, go to "Create a new collection", and select a type of collection to make (Family Tree or Organization structure). From there, users can build a family tree or GEDCOM (genealogical data) file as a tree. The website has extensive information on what Connectionaire is, services that they provide, and video tutorials. 
#### Heuristic Evaluation
_Overall Evaluation_:
<br>
<br>
### 1. Visibility of system status
The website clearly informs the user about its current status.<br>

>**GOOD**
>+ The site lets the user know the members being affected when they edit information on the tree by enlarging the icon of the family member.<br><img src="h1_singleenlargement.png" width=25% height=25%> <img src="h1_twoenlargement.png" width=25% height=25%>
>+ The site clearly lets the user know if an invitation to view their collection has been sent by darkening the rest of the screen and showing a pop-up saying “Success!”.<br><img src="h1_success.png" width= 35% height= 35%> <br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ The site lets the user know when they are in tree editing mode by having a tab on the side appear that says “Tree Edit Mode”, however the site does not indicate when the user is in collection viewing mode. This is inconsistent and can confuse the user as to which mode of editing they are in.<br><img src= "h1_treeeditingmode.png" width=25% height=25%> <br>_Severity Rating: 2_<br>_Recommendation: Add a tab when the user is in collection viewing mode that says “Collection Viewing Mode”._ <br>

### 2. Match between system and the real world
The website uses language that is familiar to the user and presents information in a way that is analogous to the real world<br>

>**GOOD**
>+ The site utilizes a search bar for linked albums and a search bar for people when viewing collections. The placeholder of the text in the search bars are very specific and understandable. The album search bar says "Keyword, name, etc.;search all Linked Albums" and the people search bar says "Enter a few characters of a name". Having specific text placeholders within the search bar that prompt the user what to type into it is very helpful for the user's habits and denotes the relevant information they can search to find a person or album.<br><img src="h2_searchbar.png" width=25% height=25%><br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ The navigation menu uses terms that could be misguiding users to get to where they want to be, particularly "View Collections" and "Guest Permissions".<br><img src= "h2_searchbar.png" width=25% height=25%> <br>_Severity Rating: 1_<br>_Recommendation: Consider modifying navigation text to something more helpful towards users' existing habits. Perhaps changing "View Collections" to "My Collections" and "Guest Permissions" to "Share Collections"._ <br>      
                                                                                         
### 3. User control and freedom
The website gives users a way to easily undo an unwanted action<br>

>**GOOD**
>+ The site has a save or cancel option when editing any text, such as names, titles, or descriptions. This is helpful for the user who might not want to save the changes they made and allow them to keep the previous version of the text.<br><img src="h3_saveorcancel.png" width=25% height=25%><br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ The only way to undo an action while editing the collection is through the undo button, the user can't use "ctrl+z" keys. Furthermore, the user can't redo their work, they can only undo it.<br><img src="h3_undobutton.png" width=25% height=25%><br>_Severity Rating: 2_<br>_Recommendation: Add a forward arrow to the side bar that users can click on to redo their work. Add functionality for users to use "ctrl+z" keys for undo and "ctrl+y" keys for redo._ <br> 
                                                                                               
### 4. Consistency and standards
The website follows conventions followed by similar websites.<br>

>**GOOD**
>+ Clicking on "Collectionaire" on the top left corner of the page takes the user back to the homepage.
>+ The options of the navigation bar is listed at the top of the screen. These options collapse into a hamburger menu when the window width is narrow.<br><img src="h4_hamburger.png" width=25% height=25%> <img src="h4_fulllength.png" width=25% height=25%> <br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ The term "Exit" when hovering over the user's account is unconventional and difficult to understand.<br><img src="h4_exit.png" width=25% height=25%><br>_Severity Rating: 2_<br>_Recommendation: Change the term "Exit" to "log Out" which follows standard account conventions._ <br> 

### 5. Error prevention
The website prevents errors by reducing error-prone conditions or checking for them and notifying the user.<br>

>**GOOD**
>+ The site autosaves the collection when navigating to a new page, and it doesn't allow the user to navigate to a new page before deciding to save or cancel the work the user has done.<br> 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ The text input box for descriptions of albums, people, or events does not have spelling or grammar check options.<br><img src="h5_grammar.png" width=25% height=25%><br>_Severity Rating: 3_<br>_Recommendation: Add spell check to the text input boxes to prevent grammar errors._ <br> 
                                                                              
### 6. Recognition rather than recall
The website makes information needed to navigate the website visible or easily accessible.<br>

>**BAD**
>+ The editing modes for a collection are inconsistent with each other. The tree editing mode has a button to navigate to the other mode that says “Exit Tree Editing Mode”, however the collection viewing mode has no button to navigate to tree editing mode. The user has to click on the three dots and “Edit Tree” to switch to tree editing mode.<br> <img src = "h6_exitmode.png" width = 25% height = 25%><br>_Severity Rating: 3_<br>_Recommendation: When the user is in tree editing mode, instead of having a button that says “Exit Tree Edit Mode”, have a button that says “Switch to Collection Viewing Mode”. Apply this vice versa for collection viewing mode with a button that says “Switch to Tree Edit Mode”._<br>
>+ The "Guest Permissions" option on the navigation bar has sub-menu options within it that specify an action related to invites and requests. Some options sound too redundant and unneccesary which can be confusing for the user.<br><img src="h6_guestperm.png" width=25% height=25%><br>_Severity Rating: 3_<br>_Recommendation: Consolidate the sub-menu options to reduce cognitive load on users. Perhaps condense "Invite Friends and Family to View or Edit" and "Invitations & Requests to View My Collection" to one sub-menu option "Invitations & Requests to Access My Collections"._<br>
                                           
### 7. Flexibility and efficiency of use
The website allows processes to be tailored to all users from novice to expert.<br>

>**GOOD**
>+ The collection editing page for each family member gives users different options to add descriptions of the family member, linked albums, and a timeline. Such editing features include adding photos or text.<br><img src = "h7_edit.png" width=25% height=25%><br> 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
>**BAD**
>+ There is no option to audio record a memory or any speech to text option, which makes it less efficient to use for people who may not be as good with typing and who would like to speak about the memories being added to the collection. _Severity Rating: 3_<br>_Recommendation: Add a speech to text and audio recording feature._<br> 
>+ Having two editing modes, tree editing mode and collection viewing mode, can be inefficient and frustrating for the user to constantly switch between the two to perform one action. 
                                                                
### 8. Aesthetic and minimalist design
The website only contains information that is relevant and is designed to highlight the essentials<br>  
                                
### 9. Help users recognize, diagnose, and recover from errors
The website provides clear error messages that state the problem and potential solutions<br>

### 10. Help and documentation
The website has resources to help users understand how to complete tasks<br>


## Competitor B: My Stories Matter
![My Stories Matter homepage](mystoriesmatter-screenshot.png)
View the full site here: [My Stories Matter](https://www.mystoriesmatter.com/)
>My Stories Matter is an organization with a mission to help seniors to write creative stories. To do this, users can make an account, go to their "Creativity Center", and select a prompt to follow. From there, users can type their story in a text box or upload a photo of a written response. The website also has extensive information on what TimeSlips is, services that they provide, resources, news, and ways to get involved with the organization.
#### Heuristic Evaluation
