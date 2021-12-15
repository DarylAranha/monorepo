# MonoRepo
A template for react that shares components and logic across all the projects. Out of the box you will see the following.
- Components folder
- React Native (Mobile)
- React, created using CRA (Web)

Additional react based projects can be added. The project is configured in such a way that a component is created once and is shared across all the projects. 

## Set up

Clone the project and run `yarn`
```
$ cd <project-directory> 
$ yarn
```

## Commands to run the application
```
# For Web
$ yarn workspace web start

# For Mobile (Android)
$ yarn workspace mobile run-android

# For Mobile (IOS)
$ yarn workspace mobile run-ios
```
