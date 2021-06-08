# Intent Filters

### The intent is a messaging object which tells what kind of action to be performed. The intent’s most significant use is the launching of the activity. Intent facilitates the communication between the components.

### use case of Intents:

#### 1. Starting Activity

#### 2. Starting a Service

#### 3. Delivering a Broadcast

### Intent Type :

#### 1. Explicit intent: Explicit intent can do the specific application action which is set by the code like changing activity, In explicit intent user knows about all the things like after clicking a button which activity will start and Explicit intents are used for communication inside the application

#### 2. Implicit Intent: Implicit intents do not name a specific component like explicit intent, instead declare general action to perform, which allows a component from another app to handle.

### Implicit intent uses the intent filter to serve the user request.

### The intent filter specifies the types of intents that an activity, service, or broadcast receiver can respond.

### Intent filters are declared in the Android manifest file.

### Intent filter must contain <action>

### Intent filter are describe by:

#### 1. <action>,

#### 2. <category> and

#### 3. <data>.

### Examples of common action:

#### 1. ACTION_VIEW: Use this action in intent with startActivity() when you have some information that activity can show to the user like showing an image in a gallery app or an address to view in a map app

#### 2. ACTION_SEND: You should use this in intent with startActivity() when you have some data that the user can share through another app, such as an email app or social sharing app.
