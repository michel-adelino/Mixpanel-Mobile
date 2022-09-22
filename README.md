
<div>
  <h1 align="center">Mixpanel Mobile</h1> 
</div>

# Build Mixpanel Mobile app with Mixpanel APIs

Track and analyze users' top events data on just one hand, with a **Mixpanel Mobile** app in Flutter, implementing the Mixpanel API.

### Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Setup](#setup)
- [Version of Technologies](#version-of-technologies)
- [Folder Structure](#folder-structure)
- [Libraries and tools used](#libraries-and-tools-used)
- [Support](#support)
- [License](#license)


# Features

1. Analyze data in Mobile
2. Top events total counting
3. Set reminders when we achieved the goal.

# Screenshots

![demo](/Screenshots/Mixpanel.png)

# Setup

To run this project, you need to do the following.

For setting up and running this project, you need to basic username and password which generates a **Base64** hash key to authenticate. First of all, you need to create a Mixpanel account and Project.

Follow the steps.

1. Create a Mixpanel account from <a href="https://mixpanel.com/">Here</a>.
2. Create project.
3. Implement Mixpanel in your project using Mixpanel SDK.
4. To generate Base64, visit the page.
5. Clone the repository.

```sh

$ git clone

[https://github.com/](https://github.com/).....

$ cd Mixpanel-Mobile

```

### Install Dependencies
```
flutter pub upgrade

flutter pub get
```

### Change Base key
Add your Authorization BaseKey value ``` lib/core/constants/MyConstant.dart ``` in ```baseKey```

### Change Project ID
Add your Porject ID in``` lib/core/constants/MyConstant.dart ``` in ```projectId```

### Running the App 

```
flutter run
```
### Version of Technologies

Dart SDK Version 2.17.0 or greater.
Flutter SDK Version 3.0.0 or greater.

### App Navigations

Check your app's UI from the AppNavigation screen of your app.

## Folder Structure

After successful build, your application structure should look like this:

```
.
├── android                         - contains files and folders required for running the application on an Android operating system.
├── assets                          - contains all images and fonts of your application.
├── ios                             - contains files required by the application to run the dart code on iOS platforms.
├── lib                             - Most important folder in the project, used to write most of the dart code.
    ├── main.dart                   - starting point of the application
    ├── core
    │   ├── app_export.dart         - contains commonly used file imports 
    │   ├── constants               - contains all constants classes
    │   ├── errors                  - contains error handling classes                  
    │   ├── network                 - contains network related classes
    │   └── utils                   - contains common files and utilities of project
    ├── data
    │   ├── apiClient               - contains api calling methods 
    │   ├── models                  - contains request/response models 
    │   └── repository              - network repository
    ├── localization                - contains localization classes
    ├── presentation                - contains all screens and screen controllers
    │   └── screens                 - contains all screens
    ├── routes                      - contains all the routes of application
    └── theme                       - contains app theme and decoration classes
```

### Libraries and tools used

- get - State management
https://pub.dev/packages/get
- connectivity_plus - For status of network connectivity
https://pub.dev/packages/connectivity_plus
- pull_to_refresh - For list functionalities
https://pub.dev/packages/pull_to_refresh
- cupertino_icons - For iOS icons
https://pub.dev/packages/cupertino_icons
- shared_preferences - Provide persistent storage for simple data
https://pub.dev/packages/shared_preferences
- cached_network_image - For storing internet image into cache
https://pub.dev/packages/cached_network_image
    
### Support

If you have problems or questions, please open an issue on the repository.

## License
MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.