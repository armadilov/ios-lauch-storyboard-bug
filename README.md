# ios-lauch-storyboard-bug

### Summary
When launching the app with InCall status bar enabled, centered logo in LaunchScreen.storyboard gets cropped in a strange way

![Launch Bug screenshot](https://raw.githubusercontent.com/armadilov/ios-lauch-storyboard-bug/master/screenshots/launch.png "Launch Bug")

![Storyboard setup](https://raw.githubusercontent.com/armadilov/ios-lauch-storyboard-bug/master/screenshots/storyboard-setup.png "Storyboard setup")

### Steps to Reproduce
1. Create a new app with LaunchScreen.storyboard
2. Add an UIImageView to the Launch View Controller and select some image
3. Center the image horizontally & vertically in the controller
4. Launch simulator and toggle 'In-call status bar'
5. Launch the app and notice the 

### Expected Results
The Splash logo displays properly

### Actual Results
The Splash logo 
