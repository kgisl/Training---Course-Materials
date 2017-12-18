## Android Developer Fundamental 1 

#### I.Why Learn Android?  #
	•	Technology for life. Deep interaction with our daily life. 
	•	Mobile, Simple & Practical. 
	•	Biggest user base (see statistics) 
	•	Open Source, Control & Flexibility 
	•	Future Technology 

#### II.	Objectives 
Upon completion of this course, you will be able to: 

	•	Build your own Android apps 
	•	Understand how Android applications work, their life cycle, manifest, Intents, and using external resources 
	•	Design and develop useful Android applications with compelling user interfaces by using, extending, and creating your 
	own layouts and Views and using Menus 
	•	Take advantage of Android's Application Framework API to build complex applications 
	•	Utilize the power of background services, threads, and notifications 
	•	Use Android's communication APIs for SMS, telephony, network management, and internet resources (HTTP) 
	•	Secure, tune, package, and deploy Android applications 

#### III.	Audience 
<p>This course is designed for software developers interested in designing, creating, deploying, and testing applications for the Android mobile phone platform. It is valuable to both novices and professional (who already have experience in developing mobile applications for other platforms). </p>

#### IV.	Prerequisites 
Java Programming covering following topics: 
###### Java Basic 
1. Basic Syntax 
2. Object & Classes 
3. Basic Datatypes 
4. Variable Types 
5. Modifier Types 
6. Basic Operators 
7. Loop Control 
8. Decision Making 
9. Numbers 
10. Characters 
11. Strings 
12.	Arrays 
13.	Date & Time 
14.	Methods 
15.	Files and I/O 
16.	Exceptions 

###### Java Object Oriented 
1.	Inheritance 
2.	Overriding 
3.	Polymorphism 
4.	Abstraction 
5.	Encapsulation 
6.	Interfaces 
7.	Packages 

###### Java Advanced: 
Collections (Arraylist, Hashmap)

__________
## Detailed Outline
**1. History of Android**
		<p>History of Android module focuses on how we got here. The goal of the module is to give us an idea of design philosophy behind Android, and what it may say about the future of the platform. At this high level, we explore both technical and business choices that effect the platform for a long time. We'll look at how and Android operating system gets put together by various parties involved, from Google to carriers. Topics in this module include: </p>

		•	Vision for Android 
		•	History overview 
		•	Android Open Source Project (AOSP) versions 
		•	OEM add-ons 
		•	Third Party Android add-ons 
		•	Carrier Bloatware 
		•	Android fragmentation 
**2. Android Stack**

<p>Understanding how the entire Android operating system is put together is important in order to understand how to leverage everything it has to offer. This module provides an overview of each layer of the stack and its role. We'll look at both the business and the technical design choices. Topics in this module include: </p>
	•	Design philosophy 
	•	Open Source licenses 
	•	Linux kernel space 
	•	Native layer 
	•	Dalvik VM 
	•	Application layer 
	•	Apps 

**3. Hello Android**
<p>The goal of this module is to have you write a simple Hello, World application. By the end of this module, you should be able to identify main parts of an Android app. You should also be able to verify that your tools are setup properly and that you can run the application on an Android device, either physical or emulated. Topics covered include: </p>
	•	Android SDK: How to set it up and what it consists of 
	•	About Eclipse: The power of the tools 
	•	Creating a new Android project 
	•	Anatomy of a project: What are all the moving parts 
	•	Running the app: Emulator, real device, tools to monitor them both 

**4. Architecting Android Apps** 
<P>Android framework provides some new and different concepts for developing an  app. The goal of this module is to introduce you to main components used to create Android apps. By the end of this module, you should have a good idea what Android app building blocks are, and their key properties. For each building block, we'll explore its typical usage, the life-cycle, and gotchas related to the implementation. Most of the focus of this module is on the conceptual understanding at the lines-and-circles level of the design. Topics covered include: </p>
	•	What makes up an Android app 
	•	Activities and Android UI 
	•	Fragments and best practices for reusable UI 
	•	Intents, Action Bar, and More 
	•	Services, IntentServices, Remote Service 
	•	Content Providers and Loaders 
	•	Lists and Adapters 
	•	Broadcast Receivers 
	•	App Widgets 
	•	Federation of apps design model 

**5. Debugging and Testing Android Apps**
<p>This module provides an overview of some of the tools available in Android SDK that can help you with debugging and testing your apps. By the end of this module you should have a general knowledge of what tools are available and how to use them. The tools we'll explore include: </p>
	•	Logcat 
	•	Debugger 
	•	Traceview 
	•	HierarchyViewer 
	•	Syslog 
	•	Exercise Monkey 
	•	Monkey Runner 
	•	UIAutomator 

**6. Android Security Overview**
<p>The goal of this module is to provide high level overview of how Android security is architected. By the end of this module, you should know how the apps are sandboxed how the security is enforced. Topics covered include: </p>
	•	Security design overview 
	•	Application sandboxing 
	•	Using permissions 
	•	Declaring permissions 
	•	Granting and enforcing of permissions 
	•	Social vectors of attack 
	•	Top 10 Bad Permissions 

**7. Activities and User Interface**
<p>In this module, you will learn how to create basic user interface in Android. You will learn that there is a declarative (XML-based) as well as programmatic (Java-based) approach to creating Android UI. Additionally, you will learn about activities, one of the most important building blocks for Android apps. You will explore at length the lifecycle of an activity as it is highly managed by the system and is important to understand from performance point of view. Topics in this module include: </p>
	•	Two ways to create Android UI: XML versus Java approach 
	•	Main view properties: width, height, ids, strings, and more 
	•	Structure of UI: Views and Layouts 
	•	Linear Layout vs. Relative Layout vs. Frame Layout vs. Absolute Layout 
	•	Localization of UI 
	•	Best practices for targeting various form factors: phone, tablet, TV 
	•	Handling UI events: a bit about listeners 
	•	Best practices when working designing Android UI 

** 8. Action Bar and Navigation**

<p>Your app is a collection of various "screens", implemented as activities. You also may have a few services, and other features that require a button to click to activate. Android offers a standardized method for managing menus and navigation across various components of your app in its Action Bar framework. In this module, you will learn how to use Action Bar to implement navigation in your app. Topics include: </p>
	•	What Action Bar is 
	•	Enabling the Action Bar 
	•	Removing the Action Bar 
	•	Adding Action Items 
	•	Split Action Bars 
	•	Using the App Icon for Navigation 
	•	Implementing the "Go Home" App Icon Feature 
	•	Implementing "Up" Navigation with the App Icon 
	•	Adding Navigation Tabs 
	•	Adding Drop-down Navigation 

**9. Preferences** 
<p>Your app often needs to store some user data for future use. For example, it needs to know user's login information for an online service, or other settings. Android framework offers a system for just doing that in form of Preferences. In this module, you will learn how to use preferences within your app. Topics include: </p>
	•	Overview of preferences 
	•	Preference resource: defining what you'll store locally 
	•	Preference activity: displaying the preference screen 
	•	Reading in the preference values 
	•	Programmatically editing the shared preferences 
	•	Registering for preference changes via a listener 
	•	Filesystem overview: where are the files stored and is it secure 

**10. Advanced UI**
 
<p>This module introduces some of the advanced UI techniques that will make your user interface, and experience stand out of the rest. Topics include: </p>
	•	Create activity layouts programmatically 
	•	Incorporate layout resources into a programmatic layout 
	•	Account for a device's screen resolution when programmatically setting screen dimensions 
	•	Designing for performance 
	•	Designing for multiple form factors 
	•	Testing and optimizing UI 

**11. Services**

<p>An Android application is just a collection of various building blocks. Services are one of the major such blocks. They represent something working in the "background" in your app. By background, we mean it is not visible, but is crucial to the functionality of you app. In this module you will learn what services are, when to use them, how they work, and how to implement them. Topics covered include: </p>
	•	Overview of Android services 
	•	Service lifecycle 
	•	Declaring a service 
	•	Registering a service 
	•	Starting and stopping a service 
	•	Threads and other concurrency considerations with services 
	•	Bound versus unbound services 
	•	Remote versus local services 

**12. Broadcast Receivers**
 
<p>Broadcast receivers are Android's publish-subscribe mechanism that. It is an essential part of most Android apps. In this module, you will learn when to use broadcast receivers, how to implement them, as well as register them for intent actions. Topics covered include: </p>
	•	Broadcast receiver usage patterns: when and why to use them 
	•	Implementing a broadcast receiver 
	•	Registering a broadcast receiver via the manifest file 
	•	Registering a broadcast receiver programmatically 

**13. Content Providers**
<p>An Android app by default cannot access another app's data. This is the cornerstone of Android security, the principle of sandboxing. But often, you do want an app to share some data with others. 
Content providers are such an interface to data so that the data cab be mashed together across apps. </p>
<p>In this module, you will learn how to design and develop content providers. Topics covered include:</p>
	 • Why content providers: an overview 
	•	Using existing content providers: creating client code that can read and modify the data managed by a content provider 
	•	Creating a content provider: implementing a basic content provider to expose structured data to other applications 
	•	Intelligent data loading: using loaders to retrieve a Cursor from a content provider without blocking your application's main thread 

**14. List and Adapters**
 
<p>Android apps often have to deal with data, and frequently large amounts of it as well. Think an email client, opening up a mailbox of tens of thousands of emails. Given that the screen itself is rather small, and network connection often limited, the intelligence of how to efficiently handle large data sets on the screen is crucial to many apps. To help with that, Android offers a number of selection widgets, such as a list view. It also provides for a management of data that such widget display in a form of adapters. In this module, you will learn how to work with Lists and Adapters. Topics covered include: </p>
	•	Overview of selection widgets 
	•	Working with lists 
	•	Working with adapters 
	•	Implementing a list view and connecting it with an adapter 
	•	Creating custom item views 
	•	Creating custom view bindings 

**15. Fragments**
 
<p>Android runs on variety of devices, from phones with small screen sizes, to tablets and large-screen TV sets. Fragments in a nutshell represent a smaller part of a user interface that could take a whole screen, or be part of a larger UI. By creating and using fragments, your app can adapt to variety of devices and screen sizes. In this module, you will get a solid overview of fragments and will learn how to design them, develop them, and use them both statically and dynamically. Topics covered include: </p>
	•	What is a fragment: an overview and motivation 
	•	The compatibility package: targeting pre-Honeycomb devices 
	•	Fragment lifecycle 
	•	Creating a fragment class 
	•	Creating a fragment layout 
	•	Statically including fragments in an activity 
	•	Dynamically attaching fragments 
	•	Handling run-time configuration changes 
	•	Retaining Fragments Across Activity Re-Creation 
	•	Using Fragments with no Layouts 
	•	Finding Fragments 
	•	Fragment Operations 
	•	Performing Fragment Transactions 
	•	Managing the Fragment Back Stack 
	•	Integrating Fragment Action Bar/Options Menu Items 
	•	Integrating Fragment Action Bar/Options Menu Items (example) 
	•	Communication Between the Fragment and the Activity 
	•	Best Practices: Loose Coupling of Activities and Fragments 
	•	Best Practices: Define Fragment Interfaces to Invoke Activity Behavior 
	•	Best Practices: The Activity as a Switchboard 
	•	Advanced Fragment Initialization 
	•	Implementing Dialogs Using Fragments 
	•	Using a Fragment-Based Dialog 
	•	Fragment-Based Preference Management 
	•	Additional Fragment Subclasses 

**16. Testing Overview** 

<p>Testing is an important part of any app development. There are many facets of testing, such as unit testing, performance, or functional testing. In this module, you will get an overview of various tools that Android supports for testing apps. Topics covered include: </p>
	•	Testing guidelines: why test and what to test? 
	•	Overview of Android Testing: unit, functional, integration, black/white box 
	•	Android Testing Tools: JUnit, , Robotium, 


