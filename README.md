<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

TODO: Put a short description of the package here that helps potential users
know whether this package might be useful for them.

## Features

<table>
<tr>
<td>
<img src="https://raw.githubusercontent.com/jlouage/flutter-carousel-pro/master/screenshots/screenshot01.png" alt=" ">
</td>
</tr>
</table>
## Getting started
start using the package.

## Usage


```dart
import 'package:flutter/material.dart';
import 'package:carousel_nullsafety/carousel_nullsafety.dart';

void main() {
  runApp(MaterialApp(
    debugShowCheckedModeBanner: true,
    title: 'Carousel Pro',
    home: CarouselPage(),
  ));
}

class CarouselPage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return const Scaffold(
      body: Center(
        // if you have new ideas that you want to implement you can tell me....
        // instagram : xr_yr
        child: SizedBox(
            height: 200.0,
            width: 350.0,
            child: Carousel(
              images: [
                NetworkImage(
                    'https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
                NetworkImage(
                    'https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
                ExactAssetImage("assets/images/LaunchImage.jpg")
              ],
              showIndicator: false,
              borderRadius: false,
              moveIndicatorFromBottom: 180.0,
              noRadiusForIndicator: true,
              overlayShadow: true,
              overlayShadowColors: Colors.white,
              overlayShadowSize: 0.7,
            )),
      ),
    );
  }
}

//or another design only copy code and paste in scaffold in body in Center

// SizedBox(
// height: 200.0,
// width: 350.0,
// child: Carousel(
// images: [
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
// ExactAssetImage("assets/images/LaunchImage.jpg")
// ],
// dotSize: 4.0,
// dotSpacing: 15.0,
// dotColor: Colors.lightGreenAccent,
// indicatorBgPadding: 5.0,
// dotBgColor: Colors.purple.withOpacity(0.5),
// borderRadius: false,
// moveIndicatorFromBottom: 180.0,
// noRadiusForIndicator: true,
// overlayShadow: true,
// overlayShadowColors: Colors.white,
// overlayShadowSize: 0.7,
// )
// ),

//or another design only copy code and paste in scaffold in body in Center

// SizedBox(
// height: 200.0,
// width: 350.0,
// child: Carousel(
// images: [
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
// ExactAssetImage("assets/images/LaunchImage.jpg")
// ],
// dotSize: 4.0,
// dotSpacing: 15.0,
// dotColor: Colors.lightGreenAccent,
// indicatorBgPadding: 5.0,
// dotBgColor: Colors.purple.withOpacity(0.5),
// borderRadius: true,
// moveIndicatorFromBottom: 180.0,
// noRadiusForIndicator: true,
// )
// ),

//or another design only copy code and paste in scaffold in body in Center

// SizedBox(
// height: 200.0,
// width: 350.0,
// child: Carousel(
// images: [
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
// ExactAssetImage("assets/images/LaunchImage.jpg")
// ],
// dotSize: 4.0,
// dotSpacing: 15.0,
// dotColor: Colors.lightGreenAccent,
// indicatorBgPadding: 5.0,
// dotBgColor: Colors.purple.withOpacity(0.5),
// borderRadius: true,
// )
// ),

//or another design only copy code and paste in scaffold in body in Center

// SizedBox(
//   height: 150.0,
//   width: 300.0,
//   child: Carousel(
//     boxFit: BoxFit.cover,
//     autoplay: false,
//     animationCurve: Curves.fastOutSlowIn,
//     animationDuration: Duration(milliseconds: 1000),
//     dotSize: 6.0,
//     dotIncreasedColor: Color(0xFFFF335C),
//     dotBgColor: Colors.transparent,
//     dotPosition: DotPosition.topRight,
//     dotVerticalPadding: 10.0,
//     showIndicator: true,
//     indicatorBgPadding: 7.0,
//     images: [
//       NetworkImage('https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
//       NetworkImage('https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
//       ExactAssetImage("assets/images/LaunchImage.jpg"),
//     ],
//   ),
// ),

//or another design only copy code and paste in scaffold in body in Center

// SizedBox(
// height: 150.0,
// width: 300.0,
// child: Carousel(
// images: [
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*GqdzzfB_BHorv7V2NV7Jgg.jpeg'),
// NetworkImage('https://cdn-images-1.medium.com/max/2000/1*wnIEgP1gNMrK5gZU7QS0-A.jpeg'),
// ExactAssetImage("assets/images/LaunchImage.jpg")
// ],
// )
// ),




```

