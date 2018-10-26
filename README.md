# Android SDK Release Timing Chart
The release timing chart of essential SDK and libraries for Android development. 

# Motivation
In application development, many many many many troubles occur depending on upgrading the Android SDK and libraries. Ideally, SDKs and libraries are almost compatible for upgrade, but in real, they have a lot of bugs and undocumented changes and somtimes cause critial problem. So I often avoid using the latest components and need to investigate what verions of library combination works.

Finding the proper version combination of the library is like a game, however, the libraries released at the same or close timing seems to have empirically less problems (they might be relatively well tested). So I tried to list recent versions and release times of SDK and libraries so that we can find a proper combination easier.

[SDK Platform Tools]: https://developer.android.com/studio/releases/platform-tools.html
[SDK Build Tools]: https://developer.android.com/studio/releases/build-tools.html
[Android Plugin]: https://developer.android.com/studio/releases/gradle-plugin.html
[Google Services Plugin]: https://developers.google.com/android/guides/google-services-plugin
[Support Library]: https://developer.android.com/topic/libraries/support-library/revisions.html
[Play Services]: https://developers.google.com/android/guides/releases
[Firebase SDK]: https://firebase.google.com/support/release-notes/android

# The Chart
|Release Date|[SDK Platform Tools]|[SDK Build Tools]|[Android Plugin]|[Google Services Plugin]|[Support Library]|[Play Services]|[Firebase SDK]|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Oct 2018||||||||
|Sep 2018|28.0.1|28.0.3|3.2.0||28.0.0|||
|Aug 2018||28.0.2||4.1.0|28.0.0 RC 2<br>28.0.0 RC 1<br>28.0.0 Beta1|||
|Jul 2018||||||||
|Jun 2018|28.0.0||||||
|May 2018||||4.0.1<br>4.0.0|||
|Apr 2018||||3.2.1|27.1.1|15.0.0|15.0.0|
|Mar 2018|||3.1.0||28.0.0 Alpha1|12.0.1<br>12.0.0|12.0.1<br>12.0.0|
|Feb 2018|||||27.1.0|||
|Dec 2017|27.0.1<br>27.0.0|27.0.3<br>27.0.2||||11.8.0|11.8.0|
|Nov 2017||27.0.1|3.0.1||27.0.2<br>27.0.1|11.6.2<br>11.6.0|11.6.2<br>11.6.0|
|Oct 2017|26.0.2|26.0.2|3.0.0||27.0.0|11.4.2|11.4.2|
|Sep 2017||||3.1.1||11.4.0|11.4.0<br>11.2.2|
|Aug 2017|||||26.0.2<br>26.0.1|11.2.2<br>11.2.0|11.2.0|
|Jul 2017||26.0.1|||26.0.0|11.0.4<br>|11.0.4|
|Jun 2017|26.0.0|26.0.0|2.3.3||26.0.0-beta2<br>25.4.0|11.0.2<br>11.0.1<br>11.0.0|11.0.2<br>11.0.0|
|May 2017|||2.3.2|3.1.0|26.0.0-beta1|10.2.6|10.2.6|
|Apr 2017|25.0.5|25.0.3|2.3.1|||10.2.4|10.2.4|
|Mar 2017|25.0.4||2.3.0||26.0.0-alpha1<br>25.3.1<br>25.3.0|10.2.1|10.2.1|
|Feb 2017|||||25.2.0|10.2.0|10.2.0|
|Jan 2017|||||25.1.1|||
|Dec 2016|25.0.3<br>25.0.2|25.0.2|2.2.3||25.1.0|||
|Nov 2016|25.0.1|25.0.1|||25.0.1|10.0.1<br>10.0.0|10.0.0|
|Oct 2016|25.0.0<br>24.0.4|25.0.0|2.2.2<br>2.2.1||25.0.0|9.8.0|9.8.0|
