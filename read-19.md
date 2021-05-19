# Tasks and Back Stack

### The application launcher makes another Task with the main Activity made and put in the foundation of the back stack.

### When the current Activity That we have created starts another Activity, then the new Activity is pushed on top of the stack and takes into focus.

### The Activities Keeps on piling the Back stack untill the back button is pressed .

### The Back Button at that point continues popping the present Activities and reestablishing the past exercises. At the point when the last Activity is expelled from the back stack, at that point the Task ends to the screen that was last running before the making of the Task .

### principal <activity> attributes you can use :

#### 1. taskAffinity

#### 2. launchMode

#### 3. allowTaskReparenting

#### 4. clearTaskOnLaunch

#### 5. alwaysRetainTaskState

## SharedPreferences

### Android provides many ways of storing data of an application. One of this way is called Shared Preferences. Shared Preferences allow you to save and retrieve data in the form of key,value pair.

### In order to use shared preferences, you have to call a method getSharedPreferences() that returns a SharedPreference instance pointing to the file that contains the values of preferences.

#### To write to a shared preferences file, create a SharedPreferences.Editor by calling edit() on your SharedPreferences.

#### To retrieve values from a shared preferences file, call methods such as getInt() and getString(), providing the key for the value you want .
