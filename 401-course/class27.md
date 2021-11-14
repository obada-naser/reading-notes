# Intents, Activities, and SharedPreferences

## Tasks and the back stacks

As we understand the app contains components and these components work with each other to implement an app. The activities is one component of the app and the collection of them called a task and these activities when used stored in a back stack and when the user finish them, they get popped out of the stack .

When the user starts adding a more activities to the back stack it will be stored so when he/she start finishing the activities it will start popping out and when arrives to the home or the main activity and pop out of the stack of root launcher, here will depend on the version:

* If the system is android 11 or lower it will finish the activity.
* If the is android 12 or higher the user can return using the app where stopped and the data will be stored.

If we are using two apps and each of them having its own tasks so when we go to the home page each of their activities will be working fine if we returned to them because their tasks remained on the back stack and stored in the background.

When we have more than one activity that starts the same activity that the application will not add the same activity on the back stack but it will add it more than one time to the back stack and will not be removed. also with the multi-window each window will it's own tasks.


## Managing Tasks
There are many different ways the android manages the activities with tasks like the typical stack or we need to interrupt the activity with other task and many other ways. and we can do these methods using activity and startActivity with other tags inside them

Launch modes allows the app to know which task is with which activity and bind them together and there is two method to asscoiate them one using the manifest file and other using the intent flags. There are four launch modes we can use to the launch mode attribute using the manifest file :
* Standard
* SingleTop
* SingleTask
* singleInstance

also there are three flags we can use in our launch modes:
* FLAG_ACTIVITY_NEW_TASK
* FLAG_ACTIVITY_SINGLE_TOP
* FLAG_ACTIVITY_CLEAR_TOP

### Handling affinities
In the same app by default all tasks and activities have the same affinities and we can change this by using taskAffinity attribute. the importance of any affinity is when we have FLAG_ACTIVITY_NEW_TASK flag or when we have  allowTaskReparenting attribute set to true.

The stack will always be cleared when it is left for a long time and only the root stack will remain that is to allow the user to start a new task.


## Save key-value data
SharedPreferences API is used when we have key-values pairs and we need to write or read them.

1. Getting a shared preference: we can use getSharedPreferences() and getPreferences() to create new shared preference or getting an existing one.
2. writing to shared preference: we can write on shared preference by creating SharedPreferences.Editor and continue more steps to be able to write on it.
3. Reading from shared preference: like the writing method we will use getInt() and getString to get the values.
