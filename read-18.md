# Android fundamentals

### Android apps can be written using :

#### 1. Kotlin

#### 2. Java

#### 3. C++ languages

## The Android system implements the principle of least privilege. That is, each app, by default, has access only to the components that it requires to do its work and no more.

### The basic components of any android application are the following:

#### 1. Activities

#### 2. Intent and broadcast receivers

#### 3. Services

#### 4. Content Providers

#### Activities: An activity represents a single screen with a user interface,in-short Activity performs actions on the screen. For example, an email application might have one activity that shows a list of new emails, another activity to compose an email, and another activity for reading emails. If an application has more than one activity, then one of them should be marked as the activity that is presented when the application is launched.

#### Services :A service is a component that runs in the background to perform long-running operations. For example, a service might play music in the background while the user is in a different application.

#### Broadcast Receivers :Broadcast Receivers simply respond to broadcast messages from other applications or from the system

#### Content Providers :A content provider component supplies data from one application to others on request. Such requests are handled by the methods of the ContentResolver class. The data may be stored in the file system, the database or somewhere else entirely.

### A content provider is implemented as a subclass of ContentProvider class and must implement a standard set of APIs that enable other applications to perform transactions.
