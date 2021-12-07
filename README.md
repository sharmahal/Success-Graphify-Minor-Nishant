# success_graphify

Ready to use Flutter Application. Uses codeforces API. Useful for codeforces programmers.

This is my group project (group of 3)<br>
we basically make analysis easier for people who are highly active in codeforces contests.<br>
basically for a <b>competitive programmer</b>


## ScreenShots
## starting app 
<img src="ss/2.png" width="302" height="480">  <img src="ss/5.png" width="302" height="480">  <img src="ss/11.png" width="302" height="480">

### Single User Page
<img src="ss/3.png" width="302" height="480"> <br> <img src="ss/18.png" width="302" height="480"><br>  <img src="ss/9.png" width="302" height="480"><br>
<img src="ss/12.png" width="302" height="480"><br> <img src="ss/4.png" width="302" height="480"><br>  <img src="ss/7.png" width="302" height="480"><br>
<img src="ss/20.png" width="302" height="480"> <br> <img src="ss/22.png" width="302" height="480"> <br> <img src="ss/22.png" width="302" height="480"> <br> 
<img src="ss/21.png" width="302" height="480"> <br> <img src="ss/24.png" width="302" height="480"> <br> <img src="ss/8.png" width="302" height="480">  


### Compare User Page
<img src="ss/23.png" width="302" height="480"> <br> <img src="ss/1.png" width="302" height="480"> <br> <img src="ss/8.png" width="302" height="480"><br>
<img src="ss/15.png" width="302" height="480"> <br> <img src="ss/16.png" width="302" height="480"> <br> <img src="ss/25.png" width="302" height="480"><br>
<img src="ss/6.png" width="302" height="480">

### Last 10 Contests Analysis
<img src="ss/10.png" width="302" height="480"> <br> <img src="ss/14.png" width="302" height="480"> <br> <img src="ss/19.png" width="302" height="480"><br>
<img src="ss/17.png" width="302" height="480"> 

## Features
* User Statistics
* Compare Users
* Last 10 Contests Analysis

## Api Used 
* codeforces official api (open to all ).

## Packages Used
* http
* flutter_spinkit
* fl_chart

***
## Cloning and Debugging

Download project
```

https://github.com/ashutosh61973/success_graphify_minor.git

```

Get flutter dependencies
```
flutter pub get
```
Run the app
```
flutter run
```
If you have any error with generated files try to run this
```
flutter pub run build_runner build --delete-conflicting-outputs
```

***
## Testing
Unit Test
```
flutter test
```
Integration Test
```
flutter drive --driver=test_driver/integration_test.dart --target=integration_test/main_test.dart
```

***
## Installation on android device

* Step 1: Open terminal in the cloned project folder.
* Step 2: Run flutter clean
```
flutter clean
```
* Step 3: Get dependencies again
```
flutter pub get
```
* Step 4: Connect the android device via USB cable and enable USB debugging on the device.
* Step 5: Run flutter install
```
flutter install
```

***
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

