# landmark-remark

A simple mobile application – “Landmark Remark”
that allows users to save location based notes on a map. These notes can be
displayed on the map where they were saved and viewed by the user that
created the note as well as other users of the application.

## BackLog

- [x] As a user (of the application) I can see my current location on a map
- [ ] As a user I can save a short note at my current location
- [ ] As a user I can see notes that I have saved at the location they were saved
     on the map

- [ ] As a user I can see the location, text, and user-name of notes other users
    have saved
    
- [ ] As a user I have the ability to search for a note based on contained text or
     user-name


## Architecture choice

Use ViewModel to store all the data that your Activity needs and LiveData to handle communication
 between Activity and ViewModel

 The Activity is not fetching data directly but rather observing for data changes
 Data will survive configuration changes, a rotation won’t cause a new data fetch
 
 - MVVM 
 - ViewModel
 - LiveData
 
 
## UI components and styling

- Fragments

## Backend Integration 
### Map API

### Firebase Firestore

## Logic and mechanism 



## Add-ons

### Localisation


### Integration test

### Misc.

 - ic_launcher asset update  

