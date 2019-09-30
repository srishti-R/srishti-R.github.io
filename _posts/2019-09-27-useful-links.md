---
layout: post
title: Helpful links/references for android noobs
---
Caught in a web that is world wide, there is an onslaught of information if you go about searching a topic, especially 
tech blogs. Although most of them speak about a thing in almost the same manner, a few of these really stand out. For a 
beginner, I'll be jotting down all the links here that helped me come up the ladder everyday, bit-by-bit. Most of these 
will be no doubt stackoverflow links or medium articles. <br/>
* Splash-Screens in android: <https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565>
* Pending-Intents explanation: <https://stackoverflow.com/questions/2808796/what-is-an-android-pendingintent>
* Room-database: I found [this]("https://medium.com/mindorks/using-room-database-android-jetpack-675a89a0e942") article     useful although this article doesn't explain how to set up AppExecutors for querying room on background thread. Refer to   my repos for the same. What's an Executor? [Here](https://stackoverflow.com/questions/52173972/when-and-why-would-one-use-a-group-of-executor)
* Room with live-data and view-Model: 
* ViewModel and LiveData in depth explanation: <https://medium.com/google-developer-experts/viewmodels-under-the-hood-f8e286c4cc72> <br/> 
(TL;DR for the above post--> ViewModelProviders is a class that with its _of(Context, Factory)_ method creates and returns a ViewModelProvider which stores ViewModels in Hashmaps associated with their activity/fragment and returns a ViewModel if and when an instance is created, otherwise creates and returns a new ViewModel through _get(ModelClass)_ method.)
* Need to implement ViewModelProvider.Factory class: <https://medium.com/google-developer-experts/add-the-new-viewmodel-to-your-mvvm-36bfea86b159> <br/>
(TL;DR for the post--> In case you want to create a ViewModel that takes in an argument, implement ViewModelProvider.Factory and inject its instance in _of_ method.)
