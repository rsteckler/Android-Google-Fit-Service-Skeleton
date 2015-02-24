# Android-Google-Fit-Service-Skeleton
People want to run Google Fit inside of an Android service, and to minimize the amount of Google Fit code insie their activities and fragments.  This project contains two files:
MainActivity.java
GoogleFitService.java

...that attempt to do just that.  I use this pattern in my application, [Cinch](https://play.google.com/store/apps/details?id=com.ryansteckler.perfectcinch), and it's very reliable.  I have multiple fragments make requests to the service, and MainActivity only contains a small set of Fit code required to do the initial authorization.

