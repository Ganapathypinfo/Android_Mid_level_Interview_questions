# Android Mid level Interview questions


**Question: What is the difference between surface view and Textureview?**

>**TextureView**


A TextureView can be used to display a content stream. Such a content stream can for instance be a video or an OpenGL scene
http://developer.android.com/reference/android/view/TextureView.html

>**SurfaceView**


Provides a dedicated drawing surface embedded inside of a view hierarchy.
http://developer.android.com/reference/android/view/SurfaceView.html

**Question: Explain viewpager2, constraint layout?**

**ViewPager**


ViewPager2 supports paging through a modifiable collection of fragments, calling notifyDatasetChanged() to update the UI when the underlying collection changes. This means that your app can dynamically modify the fragment collection at runtime, and ViewPager2 will correctly display the modified collection


**constraint layout**


ConstraintLayout is a ViewGroup that allows you to position and size widgets in a flexible way.

**Question: What are some of the features which are there in Kotlin but not In Java?**


Lambda expressions + Inline functions = performant custom control structures.

- Extension functions.
- Null-safety.
- Smart casts.
- String templates.
- Properties.
- Primary constructors.
- First-class delegation. and more…

**Question: What are Coroutines? and how many types of coroutines?**


Coroutines is a new way of writing asynchronous, non-blocking code. An asynchronous code (from asynchronous programming) is code that runs parallel to others. It is also called non-blocking since it does not block the main thread. Asynchronous programming helps in running multiple unrelated tasks faster

**Question: What are a work manager and the features of a work manager?**


WorkManager is the recommended solution for persistent work. Work is persistent when it remains scheduled through app restarts and system reboots. Because most background processing is best accomplished through persistent work, WorkManager is the primary recommended API for background processing

**Question: What is an infix function in Kotlin?**


functions marked with infix keyword can also be called using infix notation means calling without using parenthesis and dot.
There are two types of infix function notation in Kotlin-
Standard library infix function notation
User-defined infix function notation

**Question: What is a socket?**


A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to

**Question: What is Rxjava?**


RxJava is a Java VM implementation of ReactiveX, a library for composing asynchronous and event-based programs using observable sequences.
The building blocks of RxJava are observable and subscribers. Observable is used to emit items and the subscriber is used to consume those items. It is similar to the standard Observable model. But in fact, it’s much more flexible and fluid, making it a powerful programming paradigm.

**Question: What is the difference between signed apk and apk bundle?**


App Bundles are a publishing format,
whereas APK (Android application PacKage) is the packaging format that eventually will be installed on the device.
App Bundles use bundletool to create a set of APK. (.apks) This can be extracted and the base and configuration split as well as potential dynamic feature modules can be deployed to a device.
The dependencies can look something like this:


**Question: What are dex files are used for?**


About the .dex File :
One of the most remarkable features of the Dalvik Virtual Machine (the workhorse under the Android system) is that it does not use Java bytecode. Instead, a homegrown format called DEX was introduced and not even the bytecode instructions are the same as Java bytecode instructions.

Compiled Android application code file.

Android programs are compiled into .dex (Dalvik Executable) files, which are in turn zipped into a single .apk file on the device. .dex files can be created by automatically translating compiled applications written in the Java programming language.

**Question: What is a JobScheduler?**


This is an API for scheduling various types of jobs against the framework that will be executed in your application’s own process
This is commonly called batch scheduling, as the execution of non-interactive jobs is often called batch processing, though traditional jobs and batch are distinguished and contrasted.


**Question: What is the difference between compileSdkVersion and targetSdkVersion?**


https://developer.android.com/guide/topics/manifest/uses-sdk-element.html

**Question: Explain ANR.**


When the UI thread of an Android app is blocked for too long, an “Application Not Responding” (ANR) error is triggered. If the app is in the foreground, the system displays a dialog to the user, as shown in figure 1. The ANR dialog gives the user the opportunity to force quit the app


