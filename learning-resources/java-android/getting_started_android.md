*If you are brand new to Android, we recommend coming to the first meeting of the month which is First-Timers Night.  You are welcome to come any week, but that first week will be the one we cater to beginners.*

**What is Android?**

Android is a software stack for mobile devices that includes an operating system, middleware, and key applications. The Android Software Development Kit (SDK) provides the tools and Application Programming Interfaces (APIs) necessary to begin developing applications on the Android platform using the Java programming language.  You should know the basics of Java programming before starting your Android journey.  A good course to learn enough Java to prepare for Android programming is Udemy’s [Become an Android Developer From Scratch](https://www.udemy.com/become-an-android-developer-from-scratch/)** **course**.  **Additional Java resources can be found at the end of this document.

**What is Android used for?**

Android is used for making applications (apps) that run on Android devices.  This includes Android smartphones, smartwatches (Android Wear), and anything else that runs on the [Android operating system](https://developer.android.com/about/index.html) (OS) like [Andorid Wear](https://developer.android.com/wear/index.html), [Android TV](https://developer.android.com/tv/index.html) and [Android Auto](https://developer.android.com/auto/index.html).  Once developed, Android applications can be packaged easily and sold either through a store such as Google Play or the Amazon Appstore.

**Which tools do I need?**

You can write Android programs on PCs, Macs, and Linux machines.  (This is unlike writing apps for iOS devices which can only be done on Macs.)  You’ll need a piece of software called an IDE (Integrated Development Environment).  Android Studio is now the official IDE for Android, which we recommend.  It’s a free download and works on all platforms. Although there are other IDEs available to use with Android, such as Eclipse and IntelliJ, we are hoping to steer everyone towards Android Studio as that is platform fully supported by Google, the developer of Android,  moving forward.  You will also need both the Java Development Kit (JDK) and the Android SDK.  Note:  the JDK is different than the JRE (Java Runtime Environment)  which allows people to run Java programs.  We need the JDK to be able to write Java programs.

**Do I need an Android phone/tablet in order to make an app?**

No!*  The Android SDK includes a mobile device emulator — a virtual mobile device that runs on your computer. The emulator lets you develop and test Android applications without using a physical device.  There are other emulators we will discuss later.

*It sure is fun though to put the apps you make on your own device.

**What should I do first?**

Check to see that you have JDK 7 on your computer.  JDK 8 is not yet supported by Android.

* Windows:  visit [https://www.java.com/verify/](https://www.java.com/verify/) to check to see if the JDK is already installed on your machine.  Remember this is the JDK, not the JRE.

* Mac/Linux:  open a terminal window and type "which javac".  If something appears, then you have a version of the Java JDK on your machine.  If you’d like to know which version of Java you have, type “javac -version”.

* If you don’t have Java on your machine, install the JDK by visiting Oracle’s [website](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and downloading the most recent version of the Java SE 7 that is appropriate for your machine.

**Okay, I’ve got Java.  Now what?**

Now it’s time to download the most recent version of Android Studio, the official Android IDE.  Visit [http://developer.android.com/sdk/index.html](http://developer.android.com/sdk/index.html) to get the software appropriate for your operating system.

**To set up Android Studio on Windows:**

1. Launch the .exe file you just downloaded.

2. Follow the setup wizard to install Android Studio and any necessary SDK tools. (If you are new to Android Studio, you can’t go wrong with installing with default settings - you can always add additional packages later.)

**To set up Android Studio on Mac OSX:**

1. Launch the .dmg file you just downloaded.

2. Drag and drop Android Studio into the Applications folder.

3. Open Android Studio and follow the setup wizard to install any necessary SDK tools.

4. Depending on your security settings, when you attempt to open Android Studio, you might see a warning that says the package is damaged and should be moved to the trash. If this happens, go to System Preferences > Security & Privacy and under Allow applications downloaded from, select Anywhere. Then open Android Studio again.

If you need to use the Android SDK tools from a command line, you can access them at:  /Users/<user>/Library/Android/sdk/.

**To set up Android Studio on Linux:**
1. Unpack the downloaded ZIP file into an appropriate location for your applications.

2. To launch Android Studio, navigate to the android-studio/bin/ directory in a terminal and execute studio.sh.

3. You may want to add android-studio/bin/ to your PATH environmental variable so that you can start Android Studio from any directory. (Ex: `export PATH=$PATH:~/your_android_directory/android-studio/bin`) [For more info, see this guide.](http://www.codeproject.com/Articles/802813/Setting-Up-Android-Development-Ubuntu)


4. Follow the setup wizard to install any necessary SDK tools.

Important to note!

On first launch of Android Studio it will run an update. Please launch and update Android Studio  before you come to a meetup in order to save time staring at your computer.

[More details needed here to download and install the appropriate packages]



**Let’s take the time to set up your phone.**

Now is a good time as any to set up your phone/tablet if you have one. (Remember, you can build and test many apps with just the built-in emulator.)  You only have to do three things to enable testing of your apps on your device:

* Ensure your phone will allow the installation of apps from unknown sources (the unknown source is you rather than apps from the Play Store.)  Try looking under Settings → Security and make sure the checkbox for Unknown Sources is checked.

* Allow USB debugging.  Try looking under Settings → Developer Options and check the USB debugging box.

* Connect your Android phone to your computer via a cable.

**Hello, **~~World~~** Android!**

It’s time to check to see if everything has been installed and is working properly.  We will make a simple [Hello World app](http://www.techotopia.com/index.php/Creating_an_Example_Android_App_in_Android_Studio).

**Where do I go from here?**

You will get the most out of our hack nights if you follow one of our suggested resources.  These are the classes/books/resources that our members know the best and for which they can offer the most support.  The goal of the hack night is to help you learn the skills that will assist you with programming problems you may see in your workplace; not to actually assist you with work related to your job.  Asking problems specific to work projects derails the productivity of everyone at the event and may result in you not being included in future hack nights.

Taking a bit of liberty here, we’d like to define three groups of Android developers for the purposes of our hack nights:

* Beginner - someone new to Android who uses tutorials to build apps

* Intermediate - someone who comes up with an original idea and uses the constructs they’ve learned from the tutorials to put things together in new ways

* Advanced - [more]

**_Android Courses_**

(some older resources use Eclipse, but similar features are available in Android Studio)

 All Android Studio

* [Become an Android Developer from Scratch](https://www.udemy.com/become-an-android-developer-from-scratch/?dtcode=TPTbIQE29HVW)** **(paid - Udemy)

* [Developing Android Apps](https://www.udacity.com/course/ud853) (free - Udacity)

* [University of Reading Beginner Tutorial](https://www.futurelearn.com/courses/begin-programming) (free)

Some Eclipse/ Some Android Studio

* [The Complete Android Lollipop Development Course](https://www.udemy.com/android-lollipop-complete-development-course/) (paid - Udemy) - starts with Eclipse IDE, moves to Android Studio, teaches java along the way

Eclipse

* [Coursera Android Specialization](https://www.coursera.org/specialization/mobilecloudcomputing2/36?utm_medium=listingPage)** **(free)- videos from 2013/early 2014, four week courses start ~monthly

* [Coursera Sequence](https://www.coursera.org/specialization/mobilecloudcomputing2/36?utm_medium=listingPage) (free) - uses Eclipse in video

* [How to Program for Beginners](http://www.linux.com/learn/docs/683628-android-programming-for-beginners-part-1)[ (free)](http://www.linux.com/learn/docs/683628-android-programming-for-beginners-part-1)

* [Beginner Coursera](https://www.coursera.org/course/androidapps101)[ (free)](https://www.coursera.org/course/androidapps101)

* [Lynda.com](http://www.lynda.com/Android-tutorials/Building-Note-Taking-App-Android/122466-2.html)[ (get free access with DC library card!)](http://www.lynda.com/Android-tutorials/Building-Note-Taking-App-Android/122466-2.html)

**_Android Tutorials_**

* [Codepath](https://github.com/codepath/android_guides/wiki)

* [TutorialsPoint](http://www.tutorialspoint.com/android/android_tutorial.pdf)

**_Android Books_**

* [Big Nerd Ranch](http://www.bignerdranch.com/we-write/android-programming.html)

**_Android Bootcamps_**

* [Code Path Evening Bootcamp ](https://codepath.com/androidbootcamp)(8 weeks)

* [Big Nerd Ranch Bootcamp](https://training.bignerdranch.com/classes/android-bootcamp) (1 week)

**Suggested topics to tackle**

Multiple Activities, Layouts, Fragments, Persistence of Data (Shared Preferences, Files, SQLite, Parse, Firebase), Services, APIs, Sensors

**How to install a faster emulator**

[Genymotion](http://www.genymotion.com/) is an incredibly fast, memory-efficient VM that runs the Android OS in a more accurate manner than even the official emulator.  Many Android developers do all their device testing using this emulator especially when Google Play services is concerned.  In addition, the official Android emulator is plagued with a lot of bugs (i.e. intermittent network loss) that Genymotion is usually a far more reliable option.  [Start here](https://github.com/codepath/android_guides/wiki/Genymotion-2.0-Emulators-with-Google-App-support).

**_Linux installation of the genymotion package -_** After downloading the .bin file, move the .bin file where you would like to access genymotion from (suggested /home/username/Android/). Within that directory, type: chmod +x genymotion-*versionNumber*.bin to unpack genymotion. Remember what directory genymotion is in; you will need to know this when installing the plugin in Eclipse/Android Studio!  The[ plugin installation directions](https://www.genymotion.com/#!/download) on genymotion.com are otherwise pretty clear.

**Where to find help**

Android Studio just came out of Beta in the fall, so if you need help with Android Studio specifically, make sure you check the dates of the search results and only use recommendations/answers from the last six months. Prior to this, Eclipse was a popular IDE choice, (and will probably remain widely used for the near future) so some tutorials may give you Eclipse directions.  [more]

**Suggested projects **[more]

Easy - Tip Calculator

Medium - ToDo List

Hard

**How to share your app with others**

Once you have your app in a place where you wish to share it, you can package your app by creating a [signed APK (Android application package)](https://www.udacity.com/wiki/ud853/course_resources/creating-a-signed-apk) file.  Once this file is created, you can give it to anyone you want who has an Android phone.  An easy way to transfer the file is to send it to someone’s Gmail account as an attachment.  When they open the email from their phone, an option to download and install the app shows up right away.  Easy breezy!

**How to put your app in the Google Play Store**

* Register for a [Publisher Account](http://developer.android.com/distribute/googleplay/start.html) and pay the one-time $25 account fee.  This will allow you to publish an unlimited amount of apps.

* Complete the [launch checklist](http://developer.android.com/distribute/tools/launch-checklist.html).

* Share your success by letting WomenWhoCode DC know that you published an Android app!

**Where to buy inexpensive Android phones**

* [FreedomPop - $24.99](https://www.freedompop.com/offer/zte2499promo?utm_source=affiliate&utm_medium=slickdeals&utm_campaign=zte2499promo&sdtid=7609918)

**Additional IDEs**

* [Eclipse](http://www.eclipse.org/)

* [IntellJ](https://www.jetbrains.com/idea/)

**Supplemental Java resources**

**_Courses_**

* [Java for Complete Beginners (Udemy)](https://www.udemy.com/java-tutorial/)

* [Stanford University’s Introduction to Java](http://see.stanford.edu/see/courseinfo.aspx?coll=824a47e1-135f-4508-a5aa-866adcae1111)

* [A Bachelor’s Level Computer Science Curriculum](http://blog.agupieware.com/2014/05/online-learning-bachelors-level.html)

* [Intro to Programming Udacity: Java](https://www.udacity.com/course/cs046)

* [MIT’s Introduction to Programming in Java](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-092-introduction-to-programming-in-java-january-iap-2010/)

* [Coursera Introduction to Android Programming](https://class.coursera.org/android-001/lecture)

* [Intro to Programming](http://www.saylor.org/courses/cs101/)

* [Virtual Pair Programmers](https://www.virtualpairprogrammers.com/training-courses/Java-Fundamentals-training.html)

**_Books_**

* [Head First Java](http://www.amazon.com/Head-First-Java-2nd-Edition/dp/0596009208/ref=sr_1_1?ie=UTF8&qid=1400022857&sr=8-1&keywords=head+first+java)

* [Java: How to Program, 9th Edition (Deitel)](http://www.amazon.com/Java-How-Program-Edition-Deitel/dp/0132575663)

* [Effective Java](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)

**_Exercises and Tutorials_**

* [Coding Bat Java Exercises](http://codingbat.com/java)

* [Coderbyte Java Exercises](http://www.coderbyte.com/CodingArea/Challenges/)

* [Tutorialspoint Java Guides](http://www.tutorialspoint.com/java/)
