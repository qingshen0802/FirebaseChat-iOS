Chat(Swift) Example

iOS Chat Sample App implemented in Swift. Works fine in Xcode 6.2. 

# Features
- You must log in with Twitter.
- You can send and receive messages.
- Service : Firebase

## Configure Firebase
- Create a new [Firebase](https://www.firebase.com/).
- Open `FireChat-Swift.xcodeproj` in Xcode.
- Edit [MessagesViewController.swift](FireChat-Swift/MessagesViewController.swift) and change `swiftfirebasechat.firebaseio.com` to your Firebase url.

## Configure Login

- Create a [new Twitter app](https://apps.twitter.com/) to use for login.
- Go to your [Firebase Dashbaord](https://www.firebase.com/account/) and navigate to your Firebase.
- Click 'Login & Auth' in the left side menu. Select 'Twitter' and check the box to 'Enable Twitter Login'
- Paste your Twitter API Key and API Secret into the form.
- Edit [`LoginViewController.swift`](FireChat-Swift/LoginViewController.swift) and change `swiftfirebasechat.firebaseio.com` to point to your Firebase. Update `twitterAppId` on the next line to match your Twitter API Key.
- Run the app on a device or simulator
- On your iOS device or simulator, go to Settings, scroll down to the accounts section (which contains Twitter, Facebook, Flickr and Vimeo), select Twitter -> Add Account.
