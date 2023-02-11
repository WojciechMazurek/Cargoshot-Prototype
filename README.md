# roboflow-ios-sample

To get started, you'll need to have [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) installed, as well as [Cocoapods](Cocoapods). You can install Cocoapods by running either `sudo gem install cocoapods` (if you have Ruby installed) or `brew install cocoapods` (if you have the [Homebrew](https://brew.sh/) package manager installed). (I personally prefer using brew, as it was much quicker and simpler)

Navigate to `Cargoshot prototype app` directory and run `pod install`. This instals the Roboflow SDK.

## Setting up Xcode 
Open the `.xcworkspace` file with Xcode. Go to Xcode->Settings at the top bar

Choose accounts Accounts 

Add your account, click the + button, and follow the steps to add in your Apple ID, you may need to remove the old account if there is one:

Return to the project and click on the main folder `Roboflow Starter Project` 

![What you should see](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)


Go to the Signing & Capabilities section of Xcode: 

And add your Apple ID under “Team”. 


## Running the app on your Device
Because the app requires the use of the camera, it has to be run on a physical device to use its functionality; not the simulator. To do this, first make sure your iPhone or iPad has Developer Mode enabled. Once you’ve done that, your device will appear as an option in Xcode:
