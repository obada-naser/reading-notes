# Android Fundamentals

We can use either kotlin,java,and C++ languages in our android application. there are two suffix used in any android app first one called .apk that are required in the runtime of the app and the other called .aab suffix or android app bundle that contains the contents of the app project. The security for each app is the most important to any user so that no one can steal their information and in android the security is the most crucial that's why it has a multi-user linux system, users have a unique linux ID, process has its own virtual machine, and every app runs in its own linux process. And here we will talk about the fundamentals of any android app. 


## App components

every building has its own basis components and here we have four different types of app components :

* **activities :** It is when the user is using the app there are many functionality that this app provide other than the main activity such as in email apps showing the numbers of emails or sharing an image using the camera these are some of the activities so in other words activity is the entry point for interacting with the user.

* **Services :** the services is when the app keeps running in the background for a specific reason such as playing music or if the user wants to return to the app so it keeps running. Therefore, there are two types of the services one is called started services and the other called bound services. other examples for the services such as, live wallpapers,notification listeners,screen savers and many other examples.

* **Broadcast receivers :**  The broadcast receiver is a component that allows receiving broadcasts from other apps even if they were not running in the background for example an alarm or notification to the user to tell him that battery needs to be recharged or the device need to be updated.

* **Content providers :** when the user download many apps and use them they always need to save data and that many data is stored in sql database or inside the local storage however this data needs to be managed and the one who will manage them is called content providers.



### Activating components 
Now to make the system works by these components we need to activate them by using asynchronous message called **intent** and that message is used to activate activities,services, and broadcast receivers but content providers does not require intents to be activated. intents is created by an intent object.

## The manifest file

Now when the system needs to start any component in the app it needs to know that this components exits so it knows what should do when used and therefore all information about the components of the app is inside the manifest file. Beside that there are other things is provided by the manifest like identifying any user permissions and many other things. 

### Declaring components

As we said before the main task for the manifest is to have the components inside it and without it the components will never work as they should be so when the system see the manifest it will declare all the components. 

### Declaring components capabilities
As we know to activate any componenent we used the intent message so we can activate them however we can use an implicit intent and describe the action and to respond to any received intent we use intent filter.


### Declaring app requirements
Now because there a vast types of devices who uses android but some of these devices has a different hardware that differs them than other devices therefore some of these devices cannot support some apps therefore in the apps we have inside the manifest can provide the requirements of the app and if it works on this devices or no.

## App resources

We can define amany other thing aside than coding like animations, menus,styles, and other things using app resources and that makes it easier to update from any where.


