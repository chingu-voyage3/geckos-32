Music Library Web App Overview

The Music Library Web App will be a useful tool for organizing and utilizing a library of music scores (pieces of music). Musicians and musical ensembles build an inventory of musical scores. Keeping track of the inventory, and details associated with the scores such as difficulty and dates performed can all be facilitated by the app. While this app could be used by countless college, school, church, professional, and amateur musicians/ensembles, the app could be adapted for home book libraries, or cd and movie collections. A similar existing app is:

https://www.libib.com/

Necessary Components

* 2 user categories:

    * Admin

        * Login credentials

        * Ability to add new scores to library, edit existing entries

        * ie: the director of the ensemble, administrative assistant, music librarian

    * View only

        * Login credential or publicly viewable?

        * Ability to view, search, and sort existing library

        * ie: A student wishing to peruse the library to make a performance request to the director

* Database of entries

* Simple, elegant, attractive user interface

* Backup option for database info (simple spreadsheet?)

Programming

This project will be an excellent opportunity for us to gain proficiency with C.R.U.D. - Create (POST), Read (GET), Undo (PUT), Delete (DELETE). The MEAN stack of javascript-based software programs, (MongoDB, Express, Angular, and Node) is an excellent, and current method to deploy this app with a NoSQL database. There are numerous tutorials and existing code to refer to for inspiration. Substituting React for Angular is a viable option as well.

Another option to consider, may be to offer an option that allows for local storage of the data.

Page Detail

1. Login Page

2. User Page

    1. Options to view/edit existing library

    2. Start new library

3. New Library Setup

    3. Options for Title of Library, user permissions?

    4. Set entry detail information categories, ie: "Title", “Composer”, “Difficulty”, “Copyright Date,” etc.

    5. (should these be pre-filled, user created, or both?)

4. View/Edit existing library

    6. Add entry according to settings established in the New Library Setup

    7. Search and Sort entries by entry detail categories

