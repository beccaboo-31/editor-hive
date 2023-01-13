# Editor Hive - Team Codent

### Team Members
1. Aayush Doshi [ doshi.aay@northeastern.edu ]
2. Jash Mehta [ mehta.jas@northeastern.edu ]
3. Jubin Kamdar [ kamdar.ju@northeastern.edu ]
4. Rebecca Biju [ biju.r@northeastern.edu ]
---
### USER REQUIREMENTS:

#### 1. Functional Requirements

- `Register`: The user can register in the application by making a new account.


- `Login`: The system will allow the user to log into their account by entering their email and password.

- `Create Document`: Create a document by assigning a title, and description and add members from a list of users who can access the document.

- `View Profile`: The user can view his account details by viewing his profile.

- `View Document`: View the document that has been created by the logged-in user or the document that has been shared with the logged-in user.

- `Delete Document`: Delete a document that has been created by the logged-in user.

- `Share Document`: Share a document that has been created by the logged-in user.

- `Edit Document`: Edit / Update the document which is either created by the logged-in user or has been shared with the logged-in user with update rights.

- `Create Group`: Create a group by adding other registered users

- `Add Members to the Document`: Add members to edit or view the newly created document.

- `Assign Access`: Assign access to users for the created or the newly created documents by the logged-in user [Document Owner]. Can be done by the owner or editors of the document.

- `Edit Access Rights`: The creator of the group can edit the Access Rights of the members of the group

- `Delete Group`: The creator of the group can delete the group

- `Logout`: The user can logout from the application

#### 2. Authentication and Authorization

- Authentication 
  - It verifies the identity of a user or service.
  - Usernames and passwords are the most common authentication factors. If a user enters the correct data, the system assumes the identity is valid and grants access.

- Authorization
  - Giving access rights to create, view, update, and delete a document
  - Giving rights to users for creating and deleting a group
  
#### 3. Non-Functional Requirement

- `Reliability`: Reliability is a sub-discipline of systems engineering that emphasizes the ability of equipment to function without failure. Reliability describes the ability of a system or component to function under stated conditions for a specified period of time. In our project, Reliability will play a major role in how reliable the system is when multiple users/groups are working on multiple documents at the same time.

- `Security`: The access services provided using user login credentials and unable to hinder the internal working system also not being able to get access to other documents will be a major part of Security in our System.

- `Maintainability`: Maintainability is the ease with which a product can be maintained to:
  1. Correct defects or their cause
  2. Repair or replace faulty or worn-out components without having to replace still-working parts
  3. Prevent unexpected working conditions
  4. Maximize a product's useful life
  5. Maximize efficiency, reliability, and safety
  6. Meet new requirements
  7. Make future maintenance easier
  8. Cope with a changing environment.

- `Portability`: The system can be accessed on any design at any time.
---
### DOMAIN MODEL
<img width="773" alt="image" src="https://user-images.githubusercontent.com/113070179/199333263-b5adc2be-2811-454a-a3a9-6f1a86023074.png">

