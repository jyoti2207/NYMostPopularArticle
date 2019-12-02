New York Most Popular Article Project

It is a simple app to hit the NY Times Most Popular Articles API and show a list of articles,
that shows details when items on the list are tapped (a typical master/detail app)

The code uses [Most popular article of NewYork API) to load and display articles with their description.

Most Popular Article Api: https://api.nytimes.com/svc/mostpopular/v2/viewed/7.json?api-key=sample key

You can replace the sample key with your key that you got from the below link:

LINK:
https://developer.nytimes.com/get-started.
# Requirements

As this code uses Jetpack, you will need Android Studio 3.2+.

Libraries used on the project
AppCompat, CardView, RecyclerView as DesignLibrary
Data binding
Retrofit 
Junit
Livedata
Espresso
Design Pattern used in the project
MVVM design pattern is used .
Installing project on Android Studio
 
Steps:
1.Download the  project Zip from Github account. Don't use VCS in android studio.\
2.(Optional)Copy the folder extracted into your AndroidStudioProjects folder which must contain the hidden .git folder.\
3.Open Android Studio-> File-> Open->Existing android studio -> Select android  project directory.\
4.Project is imported in your android studio.\

Running the tests\
To use JUnit tests for your Android application, you need to add it as dependency to your Gradle build file.\

 
// For espresso test cases
androidTestImplementation ('com.android.support.test.espresso:espresso-core:3.0.2', {
   exclude group: 'com.android.support', module: 'support-annotations'
})
// For recycler view actions
androidTestImplementation ('com.android.support.test.espresso:espresso-contrib:2.0') {
   exclude group: 'com.android.support', module: 'appcompat'
   exclude group: 'com.android.support', module: 'support-v4'
   exclude module: 'recyclerview-v7'
}
 
// For espresso activity rule
androidTestImplementation "com.android.support.test:rules:1.0.2"
androidTestImplementation "com.android.support.test:runner:1.0.2"
Using Android Studio
To run a unit test, right-click on your test class in the Project window and select Run.

Location of Test Report
The Test reports are created in the app/build/reports/tests/debug/ directory. The index.html gives an overview and links to the individual test pages.
Coverage Report to be generated
Lastly, in the latest Android Studio, you should be able to run your JUnit-Run Configuration by clicking on the 'Run with Coverage' button.
In Android Studio 2.1.3 the is label Run Unit tests with Coverage where Unit test is the name of your test configuration as shown in the following screenshot:

Authors
JYOTI DAHIYA- Senior Android Developer.



