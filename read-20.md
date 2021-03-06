# RecyclerView

### The RecyclerView is a widget that is more flexible and advanced version of GridView and ListView. It is a container for displaying large datasets which can be scrolled efficiently by maintaining limited number of views. You can use RecyclerView widget when you have data collections whose elements change at runtime depend on network event or user action.

### If you want to use a RecyclerView, you will need to work with the following:

#### RecyclerView.Adapter - To handle the data collection and bind it to the view

#### LayoutManager - Helps in positioning the items

### RecyclerView provides these built-in layout managers:

#### LinearLayoutManager shows items in a vertical or horizontal scrolling list.

#### GridLayoutManager shows items in a grid.

#### StaggeredGridLayoutManager shows items in a staggered grid.

### Using a RecyclerView has the following key steps:

#### 1. Add RecyclerView AndroidX library to the Gradle build file

#### 2. Define a model class to use as the data source

#### 3. Add a RecyclerView to your activity to display the items

#### 4. Create a custom row layout XML file to visualize the item

#### 5. Create a RecyclerView.Adapter and ViewHolder to render the item

#### 6. Bind the adapter to the data source to populate the RecyclerView
