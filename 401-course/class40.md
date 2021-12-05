# Intent Filters

To make our app to be able to work with the other apps like when app needs to share something, we can make our app to be able to show on the apps that allow sharing and appear in share list. This property is because of intent filters that allow starting an activity from another app to my app and the system identify my app.

## Adding an Intent filter

When adding an Intent filter to the app, I should be more specific with the data and action that can be done and also the app should be compatible with other apps.

Such as :

* The action that is being used should be specific to what action it leads to either action send or action view.
* The type of data should be described when sending like either image or text.
* we can categorize the activity using where it started or the gesture but usually this part is default.

We can add multiple more than instance inside the intent filter but the one who will work is only one. and if we need to make both to work we can add one more intent filter.


## getting used to intent filters
Now when received the intent we can specify the activity using the intent or getIntent. and to se the result we can use setResult() and finish if it is done. Also we can specify the integer that is sent by passing it to setResult().