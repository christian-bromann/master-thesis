# Design and Implementation of a Development and Test Automation Platform for HbbTV

My master's thesis on building a Development and Test Automation Platform for HbbTV.

## Abstract

Hybrid Broadcast Broadband TV is one of the latest big developments in the TV industry. It is an effort to standardize the delivery of user-friendly enhanced TV services to the end consumer through connected Smart TVs and set-top boxes. As the standard evolves, it gets rolled out to more countries in the world. With more devices being equipped with this technology, a larger audience is getting access to it which opens interesting opportunities for broadcasters to create new revenue streams via advertisement or pay-TV platforms. Due to the increasing number of manufactures and device models in the market the support level is highly fragmented and aggravates the development of HbbTV applications. To ensure the functionality on a majority of devices a cumbersome and manual testing process is required which is opposed to current standards in software development. The software industry has shifted over the last 5 years from a milestone oriented to an agile approach where shipping qualitative software fast and iteratively is the number one principle. To establish a high development velocity a key factor for success is a solid continuous delivery pipeline that tests software in an automated fashion and provides confidence in the quality of the product.

The major objective of this study is to improve the process of building HbbTV applications by implementing a developing and automation platform that helps HbbTV developers to overcome issues that have been around on web and mobile platforms for years. It examines current standards in debugging and testing of software applications and demonstrates how applying these best practices to the TV space helps to increase the development velocity and software quality of HbbTV applications. By building a debugging bridge that supports the Chrome DevTools Protocol it allows developers for the first time to inspect HbbTV applications in-depth and live on the TV using modern web authoring tools like Chromes DevTools. Furthermore shows this thesis how an Appium automation driver can use this bridge to run functional tests on real Smart TVs in an automated fashion based on the WebDriver protocol.

With that technology in place results demonstrate how powerful debugging HbbTV applications can be and how much information a developer can receive. From the full DOM tree to a JavaScript console up to a detailed report about all received network packages, the state of the app is accessible at any given point in time. Moreover, proves the new HbbTV driver that running automated tests in a continuous delivery pipeline using a tool like Jenkins is fast, reliable and interoperable. A comparison at the end reveals that this approach provides a higher scaleability, functionality and flexibility for debugging and automated testing than any other existing solution in the market before.

© 2017 Christian Bromann

[![Creative Commons License](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0)
