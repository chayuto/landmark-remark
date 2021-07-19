# landmark-remark

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
 - Fragments

## Backend Integration 


### Map API

### Firebase Firestore



## Add-ons

### UI-styling


### Localisation


### Integration test

### Misc.

 - ic_launcher asset update  

