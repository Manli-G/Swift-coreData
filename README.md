# Swift-CoreData
## FriendsDatacore Application

### 1.Workflow 

#### Screen1 -> screen2

Screen1 (FriendsTableViewController): 
showing the list of data that include icon, name, and phone, correspond with second page data. 

##### Action: Add action to creating new data.

Screen2 (AddFriendViewController): 
accordingly data from last page, function for creating or editing.

##### Action: 

* Pick image from iPhone picture album.

* Save data and update data to first listing page.

* Form validation. the save button not available until text fields have completed.


### 2.Function part 

#### 2.1 Form validate

The save button should not be enabled if the user's input is invalid or incomplete.do this by registering the view controller as an observer for the UITextFieldTextDidChange notification, sent by the text fields when their text changes. In viewDidLoad(), then register the view controller as an observer for the UITextFieldTextDidChange notification.

The implementation of the textDidChange(_:) method put the textField value stored in formIsValid is used to update the save button.

#### 2.2 Custom cell

Add class FriendsTableViewCell in FriendsTableViewController page

#### 2.3 Interface

* circle shape icon in cell 
* Constrain manually
* AppIcon

### 3. Unimplemented function
#### 3.1 Form validate
The text field constrain and validation need improve to more friendly for user.
#### 3.2 Implement more with Core data

### 4. Software
Xcode: Version 11.3.1 (11C504)
Simulator: iphone8 +, iphone11(recommendation).
