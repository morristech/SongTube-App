# SongTube 3.3.0:

- Reworked MusicPlayer with Customization Options
- Improved Songs Thumbnail and Artwork Quality
- Fixed some Songs not using the correct Thumbnail/Artwork
- Added a new "Album Folder" that organizes your song downloads by song album name in your download path.
- Fixed Artwork flickering in the MusicPlayer Notification
- UI Look/Animations Improvements
- Updated YoutubeExplode Library (A few videos that weren't loading now loads)
- Improved Video loading Speed

# SongTube 3.0.0:

- Fixed Restore/Backup Options
- Fixed default downloads folder not getting created
- Fixed issue which allowed to set audio/video downloads folder to null
- README.md Updated
- Removed unused Variables/Imports
- Added Package string_validator (to check if text is url)
- Implemented QuickSearch on the App's HomeScreen
- Implemented custom-animated searchBar
- Added package keyboard_visibility (To check if keyboard is visible)
- Changed (almost) all the App's UI BorderRadius of Containers and Images from 20 to 10
- Added Shimmer to SearchPage
- Removed Floating Widget for Music
- Implemented an Slidable Bar above the BottomNavigationBar for Now Playing Music
- Forked youtube_player_flutter and modified to allow Background Playback
- Changed Native language from Java to Kotlin
- Song Artwork is now Cut in a square before applying it to a Song
- Song Artwork can now be changed before downloading (From Gallery, for now)
- Added Package rxdart to replace StreamControllers with BehaviorSubjects
- Changed Library Navigation to TabBarView (With swipe to switch pages disabled)
- Video Page is now dismissible to the right, doing this will return you to the HomePage QuickSearch
- Download list is now reversed to show recent downloads first
- Make sure our Audio/Video folders exist, if they don't then create them recursively
- Implemented a new Introduction Page for those who installs the App for the first time
- The App now doesn't force Storage Permissions, instead, asks for it when needed
- Adjusted almost all the App's UI to have a more plain design and softer shadows
- Download Page now only shows ongoing and finished downloads
- Implemented new "Media" page where you can find all your device Songs, Videos, and Downloads by the App
- Improved the App's AudioPlayer Service
- Implemented an In-App Video Player
- Replaced Youtube WebView Page with a Custom SearchPage that is faster and more customizable
- Fixed issues in Android 8 and bellow about Settings not persisting or black screen
- Implemented a Color Picker (In settings) that allows you to change the whole App's AccentColor
- Improved/Added new Animations on the whole App
- Added and Optimized the Songs Thumbnails & Artwork generator
- Changed the App SplashScreen Logo
- Enabled DayNight Theme (Allows the SplashArt to theme itself based on the System Theme)
- Fixed (almost) all bugs and Improved stability