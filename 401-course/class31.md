# Espresso

Testing the code is one of the most important thing for the developer. As before in our java testing we used it to make sure that the program is working fine without any errors or cliches. In android this process provide us with more advantages such as we can save our time with testing the application by using the tests therefore we can get the errors, see how it works, and test different things in the app. Hence, the testing in android have different definition and called as espresso tests. Espresso tests is regraded as one of the most important tests the developers can use in their codes especially in codeBase.

## Testing with espresso

when we test usually using the @Test and a function. Inside the function, to perform any test we use the inView and in turn it performs the assertions and other actions. To know that testing is done we can use either the message queue if it was empty or no tasks is being executed or even no resources are working.

Most common packages that are used with testing are :

* espresso-core
* espresso-web
* espresso-idling-resource
* espresso-intents 

And other packages for using espresso.



## Creating UI tests

In espresso there are something that makes testing and confirming our UI is more easier and better that is called test recorder tool. The recorder test tool is used to provide the developer with an easier methods to make tests not based on anything but the action of the user. As it takes the recording for the actions of the user and UI elements and produce a tests that can works in sync from the generated record.


### How record happens

As we know, every app has both the the activities like pressing button or getting to other page and called here as the UI interactions and the other thing is the elements that is shown to the user. These both components is the main things that needs a tests to their working conditions and by using the espresso test we can can generate tests to both of them.

### UI interactions and verifying the elements

to test the actions between the app and user we need first to run the app then start recording and choose which window then build it and start interacting with it. As for the UI elements we need to check three things text, exists, or does not exist and also there are certain steps to finish it as the interaction like recording the screen and add the assertions for specific elements.

Finally, when we finish recording the actions and elements now we need to save the recording and terminate it to be able to generate an automatic tests and creating the class for the tests.

### Running the tests locally/firebase
Now we can use the the recorded espresso to run the tests locally or online on the clouds by using the fireBase test lab . Locally we can run it by going to the test file on the user's pc however with the advanced technology we can now go to any cloud and run the app.