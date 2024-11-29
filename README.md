"# Github-App" 

How to clone this project
Generate your GitHub token here and replace this code with your token at [root]/local.properties

kotlin
Copy code
GITHUB_API_KEY="<<REPLACE WITH YOUR GITHUB TOKEN>>"
How to contribute
I am open for everyone who wants to improve this app. Feel free to pull-req this repository or contact me personally via email at dharmayudistira2000@gmail.com.

Features
Search User: Searching GitHub users using the GitHub API.
Details User: Show details of a user using the GitHub API.
Favorite User: Add/remove users to/from your favorite list.
Settings: Change app theme (dark mode / light mode / follow system).
Tech Stack
Programming Language: Kotlin
Architecture:
Clean Code Architecture by Uncle Bob
Jetpack MVVM - Repository Pattern
Modularization
Dynamic Feature
Jetpack Components:
Datastore
Preference
Room
Lifecycle (LiveData & ViewModel)
Navigation Component
Drawer Layout
Material Design Components
ViewPager2
ViewBinding
Networking:
Retrofit
OkHttp
Gson Converter
Other Libraries:
AndroidVeil - show a list with shimmer animation.
Kotlin Flow - reactive data stream.
Kotlin Coroutines - concurrency that simplifies asynchronous API consumption.
Koin V3 - dependency injection.
Lottie Animation - cool & smooth animation.
Coil - image loader.
What's next?
Features:
 Reminder using WorkManager.
 Localization for English and Indonesian.
 Login.
App:
 Migrate to Moshi converter.
 Implement pagination using Paging 3.
 Add CI using CircleCI.
