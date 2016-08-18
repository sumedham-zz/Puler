

# FB Final Project - *püler*

**püler** is an iOS Swift application that allows users to easily split gas costs and carpool. Good for the environment, good for your bank account.

## User Stories

The following functionality is complete:

- [x] püler finds user's current location on map
- [x] User can track his/her ride on the map while in progress or choose from a variety of routes based on current location and destination.
- [x] Implementation of Parse to save user details, ride history, etc.
- [x] User can update profile features, including a profile photo.
- [x] User can select friends from his/her contacts to split the ride with or add a new contact within the app.
- [x] Selected contacts receive SMS from user indicating how much to pay and user's PayPal.Me link to pay to.
- [x] User can view his/her ride history, including how much each person was charged, miles driven, etc.
- [x] User can view ride details for specific ride in history, including image of route taken, start/end locations, riders in car, total gas price, total miles driven, amount charged per person, etc.
- [x] User can choose his/her car model or choose from an already added list of cars.
- [x] Average suggested gas price available for user to view or change to a custom price if he/she chooses.
- [x] User can retrieve forgotten password using phone number. püler will send an automated text with the user's password.
- [x] User can cancel ride
- [x] User can share ride while driving to allow other users to join in upon request.
- [x] User can view shared rides from other users and ask others who have shared their ride to join in. 
- [x] User can view how much money he/she saved with püler in total or see how much he/she saved on particular rides.
- [x] User can share a particular ride and details on Facebook or Twitter.
- [x] User can track who's paid and who still owes gas money. He or she can send a reminder text for payment.
- [x] Clean, sophisticated UI
- [x] Simple, intuitive UX
- [x] Animated side bar menu
- [x] Map view includes a compass to relocate current location
- [x] Scroll view between child view controllers
- [x] Transitional animations on menu and between view controllers
- [x] Custom animations: menu, splash image, text, slider, gifs, bounces, popup view controllers, etc.
- [x] Autolayout to accomodate different sized iPhone screens


## Video Walkthrough

Here's a [walkthrough](https://www.youtube.com/watch?v=tpKefqxTx3s) of implemented user stories:

## Notes
For full project, please message me. Contact information can be found on my [website](http://MariamSulakian.com).

The GoogleMaps framework is too large to upload to GitHub. To use the project, please delete GoogleMaps from the podfile
and reinstall.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library
- [GoogleMaps](https://developers.google.com/maps/) - distance, route images, polyline, places autocomplete
- [Edmund's Car API](http://developer.edmunds.com/api-documentation/vehicle/)
- [Parse](http://www.parse.com/) - Used cloud server [Heroku](https://dashboard.heroku.com/) to host
- [SwiftyJSON](https://github.com/SwiftyJSON)
- [SwiftAddressBook](https://github.com/SocialbitGmbH/SwiftAddressBook)
- [TextFieldEffects](https://cocoapods.org/pods/TextFieldEffects)
- [YALSideMenu](https://github.com/Yalantis/Side-Menu.iOS)
- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD)
- [JLToast](https://github.com/devxoul/JLToast)
- [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell)
- [CNPopupController](https://github.com/carsonperrotti/CNPPopupController)
- [Twilio](https://www.twilio.com) - host automated SMS services
- [NSDate+TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo)
- [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController)
- [SwiftRequest](https://github.com/rickyrobinett/SwiftRequest)
- [FBShimmer](https://github.com/facebook/Shimmer)
- [Login GIF](http://rebloggy.com/post/classic-travel-sunset-rush-hour-san-francisco-golden-gate-bridge-sf-cinemagraphs/60952306705)

## License

    Copyright [2016] [Mariam Sulakian, Sumedha Mehta, Mazen Ibrahim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
