# **Current version**

# <a id="v0.20.3">0.20.3 - Split pane improvements (Jun 27, 2017)</a>

## Improvements

- (Experimental) Added option to select full content parser
- Improved behavior of article content split pane
  - First article is no longer selected automatically
  - Clicking on article marks it as read
  - When no article is selected the main screen takes full width
  - There is now a button which allows closing split pane
- Added support for playing videos in fullscreen

## Bug fixes

- Fixed crash when switching themes
- Fixed unread counter not updating when marking articles as read in split pane
- Fixed RTL layout in article content split pane

## Other

- Added dialog explaining why there is no Feedly integration
- Updated translations

# **Updates history**

- _[0.20.2 - Mark as read button fix](#v0.20.2)_
- _[0.20.1 - Settings resetting fix](#v0.20.1)_
- [0.20.0 - Tablet layout](#v0.20.0)
- _[0.19.5 - Subscriptions search fix](#v0.19.5)_
- _[0.19.4 - Reappearing ads fix](#v0.19.4)_
- [0.19.3 - Bug fixes and minor features](#v0.19.3)
- _[0.19.2 - Setting changing fix](#v0.19.2)_
- _[0.19.1 - Translations update](#v0.19.1)_
- [0.19.0 - Subscriptions navigation](#v0.19.0)
- [0.18.5 - Freeze fix](#v0.18.5)
- [0.18.4 - Article time fix](#v0.18.4)
- [0.18.3 - Article content rendering fix](#v0.18.3)
- _[0.18.2 - Toolbar behavior fix](#v0.18.2)_
- _[0.18.1 - Article events fixes](#v0.18.1)_
- [0.18.0 - Font customization](#v0.18.0)
- _[0.17.5 - Full content loading crash fix](#v0.17.5)_
- [0.17.4 - Colorful scroll edges](#v0.17.4)
- _[0.17.3 - Android Nougat crash fix](#v0.17.3)_
- _[0.17.2 - Toolbar fixes](#v0.17.2)_
- _[0.17.1 - Rotation crash fix](#v0.17.1)_
- [0.17.0 - Toolbar unread counter](#v0.17.0)
- _[0.16.1 - Performance fix](#v0.16.1)_
- [0.16.0 - Article starring](#v0.16.0)
- _[0.15.1 - Images fixes](#v0.15.1)_
- [0.15.0 - Article list customization](#v0.15.0)
- [0.14.4 - Full content toggle](#v0.14.4)
- _[0.14.3 - Translation fixes](#v0.14.3)_
- _[0.14.2 - Font size fix](#v0.14.2)_
- _[0.14.1 - Setting defaults fix](#v0.14.1)_
- [0.14.0 - Polish translation](#v0.14.0)
- [0.13.1 - Font size](#v0.13.1)
- [0.13.0 - Search screen](#v0.13.0)
- [0.12.0 - Readability mode](#v0.12.0)
- [0.11.3 - FAB animations](#v0.11.3)
- [0.11.2 - Premium color picker](#v0.11.2)
- [0.11.1 - Clean up and error handling](#v0.11.1)
- [0.11.0 - Appearance details](#v0.11.0)
- [0.10.3 - Premium](#v0.10.3)
- [0.10.2 - Advertisements](#v0.10.2)
- [0.10.1 - SwipeActionView separation](#v0.10.1)
- [0.10.0 - Image viewer](#v0.10.0)
- [0.9.0 - Application information screens](#v0.9.0)
- [0.8.0 - Feedly integration](#v0.8.0)
- [0.7.0 - Actions customization](#v0.7.0)
- [0.6.2 - Subscription management polish](#v0.6.2)
- [0.6.1 - Folders](#v0.6.1)
- [0.6.0 - Subscriptions](#v0.6.0)
- [0.5.0 - Color customization](#v0.5.0)
- [0.4.0 - View pager and automatic night mode](#v0.4.0)
- [0.3.0 - Long press actions](#v0.3.0)
- [0.2.0 - Theming and subscriptions list](#v0.2.0)
- [0.1.0 - The beginning](#v0.1.0)

# <a id="v0.20.2">_0.20.2 - Mark as read button fix_</a>
- Fixed incorrect updating of mark as read button
- Fixed Chinese language not working in language setting

# <a id="v0.20.1">_0.20.1 - Settings resetting fix_</a>
- Fixed all settings getting reset to default values

# <a id="v0.20.0">0.20.0 - Tablet layout (Jun 19, 2017)</a>
## Features

- Split screen tablet layout
- Notifications about new articles
- RTL languages support
- Setting to change language

## Improvements

- Redesigned appearance of UI showing that everything has been read
- Updated translations
- Changing "Only unread" or "Oldest first" options from the settings screen now reloads articles
- Re-organized settings screens
- App info screen of Android now has button to access settings

## Bug fixes

- Fixed "Request new integrations" button not working
- Fixed incorrect title in the main toolbar
- Fixed issues with launching image screen not always working
- Many smaller bug and crash fixes

# <a id="v0.19.5">_0.19.5 - Subscriptions search fix (May 3, 2017)_</a>
- Fixed subscriptions search

# <a id="v0.19.4">_0.19.4 - Reappearing ads fix (Apr 21, 2017)_</a>
- Fixed reappearing ads when resetting settings

# <a id="v0.19.3">0.19.3 - Bug fixes and minor features (Apr 19, 2017)</a>
## Features

- RSS links handling - Now when you navigate to RSS feed links from browser you will be automatically redirected to SwipeNews where you can subscribe to them
- "Set tags" as Floating Action Button action in article content screen
- Justified article content text setting
- Shortcut to reset all settings to their default values

## Improvements

- All translators are now listed in a dialog displayed when pressing on "people" icon from About screen
- Improved article sharing to include title and short summary
- Re-ordered items in article long press actions menu to make it easier to access most commonly used actions
- Now it is possible to enable "Refresh content when marking all as read" and "Automatically go to next stream after marking all articles as read" at the same time. One of these behaviors will be used depending on which stream you are currently viewing

## Bug fixes

- Fixed the issue with annoying vibrational sound when navigating articles 
- Articles list is no longer scrolled if you return from content screen without changing article
- Fixed TeslaUnread counter not getting updated when marking all articles as read and leaving application 

# <a id="v0.19.2">_0.19.2 - Setting changing fix_</a>
- Fixed possibility of being unable to change some settings

# <a id="v0.19.1">_0.19.1 - Translations update_</a>
- Updated translations

# <a id="v0.19.0">0.19.0 - Subscriptions navigation (Mar 30, 2017)</a>
## Features
- Subscriptions list as default screen
- Option to disable header images in article content screen
- Automatic navigation between articles
- Option to go to subscription stream from article content screen

## Other
- Updated translations: Arabic, German, Polish
- Added unread counters for streams in the main subscriptions screen

## Bug fixes
- Loading view appearing on device rotation
- Automatic scroll to incorrect article after returning from content screen
- Save to Pocket snackbar not appearing when saving links via long-press
- Rare crash when saving scroll position in content screen
- Crash on Jellybean devices and lower when using one of alternative article layouts
- Crash when scrolling to first unread article
- Article is not getting highlighted as read after opening it and returning

# <a id="v0.18.5">0.18.5</a>
- Fixed freeze issue on some devices

# <a id="v0.18.4">0.18.4</a>
- Fixed incorrectly displayed time on some articles
- Improved performance of unread counts background synchronization

# <a id="v0.18.3">0.18.3</a>
- Fixed article content not rendering on some devices

# <a id="v0.18.2">_0.18.2 - Toolbar behavior fix_</a>
- Fixed toolbar behavior with auto-hide disabled

# <a id="v0.18.1">_0.18.1 - Article events fixes_</a>
- Fixed article gestures and fab events

# <a id="v0.18.0">0.18.0 - Font customization (Feb 12, 2017)</a>
## Features

### Font customization

Option to set different fonts for application interface and article content. In this version, I have added few variations of the Roboto font and Lato font as possible choices. If you know other fonts that can be used then please let me know about them.

### TeslaUnread integration

You can enable this feature to sync unread article counts in the background and display them as application badge. Note that this only works with TeslaUnread. Please send me a message if you are aware of similar "applications" that could be integrated.

### Other

- Option to set toggling of article read state as Floating Action Button action
- Option to autoplay gifs in article list
- Option to automatically check for new content after marking all articles as read

## Improvements

### Better scrolling and toolbar auto-hiding

I've rewritten how the toolbar and header auto-hiding works to fix issues with status-bar. It no longer covers the top of the article content and stays colored after toolbar/header collapses to follow the behavior in other applications.

Another improvement coming from this change is the fixed handling of multiple fingers. Now you should be able to use more than one finger to scroll the content without any issues.

### Other

- Grouped debug options under sub-menu to organize them together
- Added button to request new integrations from login screen
- Saving to Pocket from bottom sheet dialog now shows success message
- Updated translations

## Bug fixes

- Quickly tapping on setting category no longer opens it multiple times
- Fixed crash when trying to send email if user has no email application installed
- Fixed coloring issues of unread badge and text when toolbar is set to light color
- Fixed article list layout issues on Jelly Bean
- Volume controls no longer show if you reach last or first article in content screen when navigating with volume buttons
- Fixed crash when quickly navigating between articles
- Fixed some setting applying issues

# <a id="v0.17.5">_0.17.5 - Full content loading crash fix_</a>
- Fixed crashes when loading full content

# <a id="v0.17.4">0.17.4 - Colorful scroll edges (Jan 29, 2017)</a>
## Improvements

### Colorful scroll edges

Improved all of the scroll edge glow effects. Now they should be colored to match the application theme instead of always being green! (Android Lollipop and higher)

### New articles full content parser

I decided to change the full content parser used by SwipeNews. This new one should give much better results for some of the sites. Thanks for showing me it.

### Better color animations

When changing accent color all the colors are now nicely animating similar to how it's done when changing primary color. In addition, the circles showing currently selected color also animate.

### Link in long-press actions menu

Made the link in long-press actions menu selectable so you cal freely copy just a part of it. Also changed its scroll direction to horizontal which feels much easier to use and improves the look by having its top and bottom always aligned.

### Other improvements

- Improved the screen animations in settings to avoid displaying ugly black background noticeable in light themes

## Bug fixes

- Fixed the long-press highlight hotspot position. Now it should appear inside of the article items when canceling long-press
- Fixed the direction of volume key navigation in article content screen. Pressing volume down should now go to the next instead of the previous article. Similar for volume up button.
- Fixed the issue where marking an article as read when opening in the browser wouldn't update unread counter. This should also fix few other cases where the unread counter is not updated when switching between applications.
- Fixed text wrapping issues in code blocks
- Fixed the default action for swipe left gesture
- Fixed toolbar height in landscape orientation
- Fixed sliders in settings not changing when modifying accent color
- Fixed some issues with loading unread counts

# <a id="v0.17.3">_0.17.3 - Android Nougat crash fix (Jan 23, 2017)_</a>
This a smaller update focused on fixing crash issues on Android Nougat. It took so long due to the fact that these issues required many changes in the way how the core system of managing articles works in SwipeNews. Please report if you run into any issues with incorrectly appearing articles or similar.

## Bug fixes

- Fixed crash issues on Android Nougat
- Fixed incorrect height of toolbar in image screen
- Fixed few memory leaks

# <a id="v0.17.2">_0.17.2 - Toolbar fixes_</a>
- Fixed toolbar collapsing behavior
- Fixed toolbar peek feature not working with auto-hide enabled

# <a id="v0.17.1">_0.17.1 - Rotation crash fix_</a>
- Fixed crash when rotating device

# <a id="v0.17.0">0.17.0 - Toolbar unread counter (Jan 11, 2017)</a>
## Features

### Unread articles count in toolbar

Shows the amount of articles that are unread inside of a badge located in the toolbar. Available both in list and content screens and can be disabled with a setting. 

### Rewrite of article content screen

This is a huge change which took a lot of time for this update. It was done in order to improve the loading and scrolling performance in that screen and also to make it more stable. There is a list of improvements and new features coming with it:

- Better performance when sliding between articles and when scrolling content 
- Improved stability when content contains many images or long content
- Long press and keep holding on toolbar in content screen to peek header 
- Improved header collapsing behavior 
- Got rid of occasional white screen flash before content is loaded in dark themes 

Please report any issues with it as that change required a lot of changes to get it right and I might have missed some bugs. 

### Mark as read on scroll setting split

This option was previously affecting both, scrolling within articles list and content screen. Now you can customize them separately. Note that due to this change the previous option you've selected now affects only articles list and marking as read in content screen is turned on for everyone.

### Volume-keys navigation

Available in 3 options:

- Navigate to next/previous article in list screen
- Navigate to next/previous article in content screen 
- Scroll article content

All of these options are disabled by default. 

## Improvements

- Removed auto full-screen mode when viewing images 
- Read articles are now always visible when viewing tag screens 
- Added counter for starred articles
- When opening articles in browser they are now marked as read
- Allowed setting titles to use more than 1 line
- Updated translations
- Improved changelog rendering on Nougat devices

## Bug fixes

- Fixed text wrapping issues in lists
- Fixed issue where some articles were changing font size of their content

# <a id="v0.16.1">_0.16.1 - Performance fix (Dec 31, 2016)_</a>
This update brings only a single but very important change:

**Fixed terrible performance drop introduced in the latest version.**

 I found out that I've accidentally created an infinite loop on the main screen which was slowing down the whole application. I'm really sorry for that. Hopefully, SwipeNews should be as fast as before.

# <a id="v0.16.0">0.16.0 - Article starring (Dec 9, 2016)</a>
## Features

- Article starring
Comes with a section in navigation drawer to view all starred items, option to select article starring as any article action and also option to select it as action in content screen's floating action button. It's going to be a default action for new users - existing should check the settings to use it.
Additionally, there is now visible a small star indicator which indicates when articles are starred. 

- Grouped tags
Setting which adds special folder grouping all the user tags together.

- Customizing visibility of items in navigation drawer
With it, you can select to either always display all tags or subscriptions in the navigation drawer or even both

## Improvements

- Updated translations. Huge thanks to kontrastylez who keeps German translation up to date :D
- Improved wording for some of the settings and messages

## Bug fixes

- Fixed few bugs

# <a id="v0.15.1">_0.15.1 - Images fixes_</a>
- Fixed incorrect positioning of image when selected middle placement
- Fixed "Load images on Wi-Fi only" setting breaking customization preview screen
- Fixed images not appearing after opening application from background

# <a id="v0.15.0">0.15.0 - Article list customization (Nov 19, 2016)</a>
## Features

- Articles list appearance customization. This is a huge change so if you find any issues or have ideas for improvements then please contact me. You can find all of the customization options under **Settings > Appearance > Articles look**.
- Full German and partial Indonesian and Dutch translations from contributors. Thanks a lot!

## Improvements

- Auto-loading full content is now disabled by default
- Application title bar in overview screen on devices with Android Lollipop and higher is now correctly updated to match selected colors
- Improved the appearance of all read view. It no longer displays useless description but instead shows counts for read/unread articles. The colors for icon and text were also changed to make it less disturbing. In addition, the alignment of mark all as read and refresh buttons should be now correct.
- Inoreader ads can no longer be extracted as header images
- Improved some of the error messages to be more informative
- Display images and load images on Wi-Fi only were moved to the new article list customization screen

## Bug fixes

- Fixed unread counter for main reading list not always updating after refresh
- Fixed crash when clearing read articles
- Fixed crash when loading images for articles list at the same time as leaving application [Android Jellybean]
- Icons behind articles are now always initialized with correct colors
- Fixed being unable to toggle toolbar in full-screen image when it failed to load
- Fixed crash after marking all articles as read

# <a id="v0.14.4">0.14.4 - Full content toggle (Nov 2, 2016)</a>
## Features

- Set tags can now be selected as a gesture action for articles
- Load full article content now works as a toggle
- Made the full changelog text selectable and links clickable

## Improvements

- Improved the stability of the application on devices with android N and higher.

This is done with a temporary workaround required because of some changes in android that result in many crashes. A proper fix for this will be to implement better article storing with offline support but that's something that I'm going to work on much later.

## Bug fixes

- Fixed header image progress wheel not disappearing when header tinting is disabled

# <a id="v0.14.3">_0.14.3 - Translation fixes_</a>
- Updated translations
- Fixed bold tags in message dialogs in Polish translation
- Fixed incorrect title of view subscription action

# <a id="v0.14.2">_0.14.2 - Font size fix_</a>
- Fixed font size loading incorrectly

# <a id="v0.14.1">_0.14.1 - Setting defaults fix_</a>
- Fixed some settings missing their default values

# <a id="v0.14.0">0.14.0 - Polish translation (Oct 29, 2016)</a>
## Features

- Polish translation
- Double tap to load full content
- Separate font size setting for article list and article content screens

## Improvements

- Improved article full content loading indicator. It now is located inside of article header instead of under it.
- Improved the look of article headers while top image is being loaded. They are now fully colored and contain loading indicator.
- Changelog should now be dismissed when pressing on read more button.
- Improved custom tabs opening to always display a matching color of the toolbar.
- Dependency updates

## Bug fixes

- Fixed crash that happened for some users when entering setting screens with switches
- Fixed settings titles missing trailing 3 dots when too long
- Fixed padding around text in all read view as it was too close to the edges of the screen.
- Fixed toolbar buttons in article content appearing under the status bar on some devices.
- Fixed swipe back gesture disturbing in updating slider settings
- Fixed being able to accidentally open browser multiple times when pressing on article header

# <a id="v0.13.1">0.13.1 - Font size (Oct 19, 2016)</a>
## Features 

- Font size customization

## Improvements 

- Improved the debug option to report article problems.
- Improved accessibility in many parts of the application.
- Search instructions now disappear when errors happen to not take valuable space.
- Open in browser action which was displayed in the dialog which allows you to either view link or image is now easier to understand.
- All progress wheels should now use correct theme colors.
- Better toolbar coloring for image activity and custom tabs.

## Bug fixes

- Fixed crash that could happen on Nougat devices when loading full content for many articles.
- Fixed crash that happened if server rejected connection while launching the application.
- Fixed missing selection highlight in some dialogs when using dark blue, sepia or AMOLED themes.
- Fixed issue where all items would disappear from the navigation drawer when marking all articles from single subscriptions or folder as read.
- Fixed pocket authentication dialog not respecting user theme.

# <a id="v0.13.0">0.13.0 - Search screen (Oct 9, 2016)</a>
## Features

- Open in browser by tapping on article header
- Better search screen


## Improvements

- Added premium entry to about screen
- Removed premium entry from drawer for users that already own it
- Improved sepia theme colors

## Bug fixes

- Fixed small click targets in dialogs

# <a id="v0.12.0">0.12.0 - Readability mode (Sep 29, 2016)</a>
## Features

- Readability article full content loading
- Support for RTL layout

## Improvements

- Removed unnecessary toast message appearing when offline
- Indicate in confirm dialog for which stream mark all as read action will be executed
- Clear settings action no longer requires manual application restart
- Material design progress wheel on FAB for pre-Lollipop devices
- There is no longer unnecessary empty space under article content if fab is not visible

## Bug fixes

- Fixed naming inconsistencies in settings
- Fixed disappearing refresh indicator
- Fixed drawer not closing when clicking on add subscription button
- Fixed toolbar title not always updating when navigating through settings
- Fixed inconsistencies in application name
- Fixed crash when expanding some licenses
- Fixed colors of search result cards
- Fixed FAB progress bar appearing out of place
- Few more crash fixes

# <a id="v0.11.3">0.11.3 - FAB animations (Sep 24, 2016)</a>
## Features

- Progress animation on FAB when marking all as read or saving to pocket

## Improvements

- Double tap and drag image zoom for pre-KitKat devices

## Bug fixes

- Fixed disappearing subscriptions when deleting folders
- Fixed crash when changing gesture settings
- Fixed subscription listing error for new Inoreader accounts

# <a id="v0.11.2">0.11.2 - Premium color picker (Sep 21, 2016)</a>
## Features

- Extended color picker for premium users

## Improvements

- Reorganized bottom sheets
Changed the order to make it easier to find actions and added dividers to separate sections.
- Made floating action button in subscriptions list always visible
- Added space in subscription list to prevent floating action button from overlapping subscriptions or folders
- Improved look of navigation drawer
- Improved sepia and dark blue themes
- Made search screen to return more results
- Updated licenses
- Articles are now loaded when returning to application instead of incorrectly displaying all read screen

## Bug fixes

- Fixed blank screens when returning to application
- Fixed incorrect highlights for dark blue and sepia themes
- Fixed feedback email body

# <a id="v0.11.1">0.11.1 - Clean up and error handling (Sep 19, 2016)</a>
Slowly preparing for open alpha. This is a small update focused on error handling and bug fixes.

___

## Features

- Option to reset dismisses

## Improvements

- Made floating action button always appear when reaching bottom in content screen
- Automatic batch marking as read 
- Error handling
- Better retry button behavior in error screens
- Better pocket login button

## Bug fixes

- Fixed broken search screen
- Fixed articles becoming un-swipeable after showing pocket authentication dialog
- Fixed refresh indicator not appearing
- Fixed incorrect unread counts after marking all as read
- Fixed ads appearing for premium users
- Fixed few memory leaks
- Fixed empty article author
- Fixed crash when sharing link to subscribe
- Fixed incorrect highlight for search screen
- Fixed wrong button colors in dialogs
- Fixed pocket auth not working in content screen
- Fixed automatic night mode switching not working correctly

# <a id="v0.11.0">0.11.0 - Appearance details (Sep 12, 2016)</a>
## Features 

- Setting article tags from content screen
- Link in actions dialog is now scrollable so it is possible to read it when it's too long
- Swiping back from anywhere when viewing first article
- Easily accessible debug options
- Improved theme engine

## Improvements 

- Much better error handling with understandable responses
- Reworked accent color theme code to make sure that all places around the application are colored
- Improved theme engine to make sure everything properly switches when changing themes/auto night mode
- Improved fonts management to use Roboto font everywhere
- Main toolbar button now animates when changing between drawer and arrow icons
- Toolbars and floating action buttons in article content screen are now separated
- Progress animation is now displayed when performing subscription/folder actions
- Once again improved main screen navigation behavior. This time, it shouldn't freeze when quickly navigating 
- Better floating button auto-hiding behavior
- Image view now takes color for its toolbar from the previous screen 
- Made drawer accounts list remember its expanded state on orientation 
- Folders open state is now remembered

## Bug fixes

- Unread counts didn't update on folders/tags
- Fixed situations where loaded articles would be lost
- Fixed many crashes when offline
- Fixed other cases where some data wouldn't be restored
- Fixed navigation drawer entries not getting highlighted
- Fixed situation where multiple loading icons would be displayed together
- Scroll position is now saved when navigating in about screen
- Fixed icons disappearing when navigating settings
- Fixed new lines not working in article content code blocks
- It should be no longer possible to accidentally open image multiple times
- Background behind ad is no longer transparent
- Fixed link opening not working for some articles
- Fixed some links crashing application
- Fixed swiping back getting disturbed when article content loads images 
- Fixed navigation drawer closing on orientation change

# <a id="v0.10.3">0.10.3 - Premium (Aug 29, 2016)</a>
Another update focused on bug fixes and improvements, with few bonus features. One of them is quick theme switcher which allows for easy changing of themes from main screen and another one is subscribing to feeds by sharing links from other applications.

Work on premium features also started and now there is a special screen dedicated for them.

___ 

## Features 
- Quick theme switcher
- Premium features screen
- Subscribe from other applications
- Dialog which makes it possible to either view image or open link corresponding to it

## Improvements
- Input validation
- Debug actions
- Reduced max limit of articles to load at once
- Improved Feedly sorting to display folders at top and tags at bottom of list

## Bug fixes 
- Fixed broken folder arrow animations
- Fixed reading list not getting highlighted when returning to application
- Fixed subscriptions not getting highlighted
- Fixed missing selected account information
- [Inoreader] Fixed unread counter not working for reading list
- Fixed infinite progress animation when not authenticated with pocket

# <a id="v0.10.2">0.10.2 - Advertisements (Aug 22, 2016)</a>
Small version which focuses on improvements. Main change is a new screen navigation behavior which makes sure that you are always able to go back to previous screens.
___ 
## Features 

- New screen navigation behavior.
Now it remembers how you navigate and allows you to easily step back.
- Advertisements
Not a cool feature but something to earn money. In-App purchases and premium features coming soon!

## Improvements

- Improved many error messages
- Added more screen animations
- Improved feedback when performing various actions
- Added link to request features and report bugs
- Improved loading of header images

## Bug fixes

- Fixed some subscribing errors
- Fixed incorrect subscription details when there was no author
- Fixed broken toolbar icon

# <a id="v0.10.1">0.10.1 - SwipeActionView separation (Aug 17, 2016)</a>
Small update which focuses on code improvements for articles swiping. The code which was used for it has been moved to separate library (soon to be open source). This will make it possible from other people to contribute and improve it.

New screen switching animations have been added as a bonus feature.
___ 

## Features 

- Animations when switching screens
- Progress animation when saving to pocket from articles list
- Subscription actions button

## Bug fixes

- Fixed floating action button in article content screen getting incorrectly re-positioned when snackbar is visible
- Images are no longer displayed when they are invalid
- Fixed crash when renaming tags
- Fixed mark above/below as read marking all articles when performing it on read article
- Subscriptions list is now correctly updated after unsubscribing from folder

## Improvements

- Improved auto-scrolling behavior when returning from article content screen
- Improved article content parsing
- Seed improvements
- Improved look of toolbar in search screen
- SwipeActionView is now a separate library

# <a id="v0.10.0">0.10.0 - Image viewer (Jul 30, 2016)</a>
#### Features 

- **Article tagging**
- **Image viewer**
- Help items in articles list

#### Improvements 

- Improved the look of buttons used to create new accounts
- Loading animation is now displayed while subscribing to website
- Subscriptions are now reloaded after subscribing
- Filter out action for subscription is no longer displayed when you are viewing single subscription stream
- Added icon to navigation drawer header which displays type of currently selected account
- Feedly now displays precise number in unread counts

#### Bug fixes

- Fixed the issue where incorrect articles would appear when switching to different subscription or folder
- Fixed crash when switching Floating Action Button actions for main screen
- Fixed unread count not getting displayed for reading list
- Fixed subscriptions appearing both in root view and child folder when added to one
- Fixed bug causing some subscriptions to disappear

# <a id="v0.9.0">0.9.0 - Application information screens (Jul 17, 2016)</a>
This version is about displaying application information to the user. I've new screens with changelogs, library licenses and useful links. In addition there are some bug fixes for annoying issues.

___ 

#### Features 

- **Changelog cards**
 Displayed in two version. Short one appears after each update at the top of articles list and can be easily dismissed. Detailed changelogs are displayed inside of about screen.
- **About screen**
 Contains basic information about the application, changelog, useful links and licenses for used libraries.
- Option to change number of articles to load at once

#### Bug fixes

- Fixed few issues with padding and sizes of some elements
- Divider is no longer displayed after last item in the articles list
- Fixed returning from subscription search to management not working
- Fixed toolbar icons not getting colored in some cases
- Made sure to hide empty header when loading of image fails
- Colored text in navigation drawer header to stay visible
- Colored subscription search text to stay visible
- Fixed few crashes

# <a id="v0.8.0">0.8.0 - Feedly integration (Jul 6, 2016)</a>
In this version I've focused on adding integration with Feedly service and implemented OAuth2 for Inoreader. Bonus new features that are now available are multiple accounts support and subscriptions search.

___ 

##### Features
- **Multiple accounts support**
Now you can have as many accounts as you want and they all can be from different news services.
- **Feedly (sandbox) integration**
Test version of Feedly integration. Correct one will be added once it'll possible again to get access to the api for new developers.
- Better login screen with support for selecting existing account
- Optional exit confirmation dialog
- **Subscriptions search screen**
Powered by Feedly integration.

#### Improvements 
- Preview images in articles list are no longer animated. This reduces lag
- OAuth2 for Inoreader
- Removed logout action from navigation drawer.
It is now possible to remove any selected account which works just like logging out.
- Bottom sheet for folders now has a header which tells the name of selected folder
- Dividers in navigation drawer now have padding as per material design specification
- Navigation drawer header is now colored to match application color
- Navigation drawer now has shadow on earlier android versions
- You can now see when you don't have any subscriptions
- Using back button when returning from subscription management screen now returns to previously selected stream instead of always to default

#### Bug fixes
- Fixed articles list failing to change when selecting new subscription
- Unread articles no longer appear as read
- Fixed subscriptions appearing multiple times when they were added to more than one folder
- All read view is now always correctly updated to display correct read state information
- Unread counts are correctly reloaded when marking all articles as read
- You now get friendly error message when you try to mark as unread article, for which it's impossible to do
- When you delete folder empty subscriptions shouldn't incorrectly appear in navigation drawer anymore
- Fixed few issues with renaming of folders and subscriptions

# <a id="v0.7.0">0.7.0 - Actions customization (Jun 1, 2016)</a>
The version which finally implements the main component of this application called customizability. You are now able to specify what happens when performing gestures on articles and floating action buttons. 

#### Features 

- **Customizable article and floating button actions!**
- Added confirmation dialog for marking all articles as read
For these who like to accidentally click on floating action buttons. For others it can be easily turned off.
- New action to open subscription web page in browser
If you ever wanted to access specific subscription in browser you can finally do that!
- Added an option to select in what order articles should be loaded by default (oldest/newset first)
- Added an option to select if read articles should be loaded by default
- Article author is displayed together with time and subscription title
- Added share menu to custom tabs
- Actions to mark all articles above or under of specific article as read

#### Improvements 

- Improved the look of settings screen.
 - It is now divided into main categories with short description for each.
 - All settings were given short descriptions
 - Updated the positions of icons to stay aligned with toolbar back button
 - Updated the size of clickable are for preferences to take whole available width
- Added short error message telling the users when they aren't allowed anymore to mark article as unread
Before that articles were secretly marked as unread but then didn't appear when refreshing as they weren't actually marked as unread.
- Removed snackbar message after marking all articles as read
There was no need for it since you can already tell if it worked seeing disappearing articles.
- Action to toggle article as read is now always visible as first item in toolbar
This makes it easy to toggle read state of articles when needed and removes the need to add additional button at the bottom of the article content.
- Indicator when unread counts are still loading

#### Bug fixes

- Made the mark all articles as read actions finally wor
- Fixed the unread counts not getting cleared when marking all articles as read or when refreshing them
- Fixed article content having annoying horizontal scroll when it contained very long word that wasn't wrapped
- Disabled settings now have correct colors indicating their state
- Fixed restoring of open state for folders

#### Other

- Removed copy link text action from long press menu
It was very easy for it to work incorrectly and the gain in having it available was really low.

# <a id="v0.6.2">0.6.2 - Subscription management polish (May 21, 2016)</a>
Another version which focuses on improving the subscriptions and folders management screen. This time the primary improvements are listening to users sort order when displaying subscriptions and highlight of currently viewed items in the navigation drawer. 

#### Features 
- Subscriptions are now appearing in correct order specified by user
- Added indication showing which entry from navigation drawer is currently selected
- Added option to load articles in reverse order (starting from oldest to newest)
- Added swipe gestures for subscriptions

#### Improvements
- Renamed subscriptions navigation drawer entry to make it clear that it is clickable
- Added margin under navigation drawer header
- Added dividers in subscriptions list to indicate where start and end open folders
- Article images in articles list now have placeholder indication
- Changed the look of mark as (un)read icons
- Added refresh action to toolbar in subscriptions list
- Switching between articles now makes the floating action button to appear
- Added pressed state indication for articles
- Improved the look of navigation drawer to further follow material design specification

#### Bug fixes
- Fixed error view not appearing when returning from content activity
- Fixed subscription editing entry in navigation drawer not getting un-highlighted after returning to reading list
- Fixed icons in settings screen not changing their color when changing accent color
- Fixed articles that were scrolled out of view and marked as read not look as read when showing them again
- Fixed some crashes when having connection issues

# <a id="v0.6.1">0.6.1 - Folders (May 13, 2016)</a>
This version brings more improvements to the subscription management screen, focusing mostly on folders and tags.

#### Features:

- Option to unsubscribe from all subscriptions in a folder
- Option to select in which folders specific subscription should be displayed
  - This also brings an option to create a new folder
- And more additional options that can be performed on folders

#### Improvements:

- Improved scrolling behavior:
  - When opening folders they are scrolled to top
  - Auto-scroll when returning from article content now should always display last viewed article
- Empty folders are now displayed as tags
- Unread articles and all articles are now merged into single reading list entry
  - With this change the only way to see read articles is to enable the option from more actions menu
  - In addition it's now displayed whether you are viewing only unread articles or all in the toolbar subtitle
- Subscriptions without icons now display placeholder icon to stay consistent with rest of subscriptions
- Subscriptions screen is now correctly updated when performing various actions
  - This removes the need to reload all subscriptions and folders after each change
- Swipe refresh animation is now colored to match selected theme colors

#### Bug fixes:

- Fixes some cases where articles has big empty space withing their content
- Toolbar shadow now behaves correctly
- Fixed marking of multiple articles at once as read
- When reaching max unread count limit + now appears correctly
- Subscriptions in navigation drawer should now stay up-to-date with each change performed on subscriptions
- Fixed situation where icons in toolbar weren't colored
- Fixed special symbols not appearing correctly for subscription titles

# <a id="v0.6.0">0.6.0 - Subscriptions (Apr 21, 2016)</a>
This version focuses on subscriptions and folders. Now you are able to see in which folder each subscription is located and also load articles that come only from single subscription. 

Another big new feature is option to see read articles. This comes with few easy ways to switch between whether they are loaded or not and also remove all read items currently loaded. 

- **View articles only from specific subscription**
- **See subscriptions and their unread counts in navigation drawer**
- **View read articles**
- See subscription folders 
- Option to display images in article list only when connected to Wi-Fi 
- Article times in main list are now updated when returning to the applications to always stay correct 
- Fixed few issues where swiping articles didn't work correctly 
- Changed some of action icons to make them clearer 
- Long pressing floating action button now shows helpful toast about action that will be performed with it 
- Articles list now has dividers between articles to make it easier to view 
- Toolbar in article content activity now displays shadow even on pre lollipop devices 
- Article content activity toolbar also displays title even when collapsed
- Long pressing article title copies it to clipboard 
- Improved auto hiding of floating action button 
- Subscription actions 
 - Rename 
 - Mark all as read 
 - Unsubscribe 
 - Manage folders 
 - Share link 
 - Copy link
- Folder actions
 - Rename
 - Mark all as read
 - Delete
- Many smaller improvements and bug fixes

# <a id="v0.5.0">0.5.0 - Color customization (Mar 29, 2016)</a>
This versions brings new color customization settings and a new feature which colors background behind article titles to use colors extracted from images. 

- **Colored article content headers**
 - Article content looks now much better thanks to the improved look of headers which can automatically use colors extracted from images. 
- Dark blue theme
- Sepia theme
- **Colors customization**
- Pocket authentication dialog 
 - Makes it easier to understand how pocket integration works and how to integrate with it. In addition now it's to possible to authenticate from the article content activity and re-attempt to add selected article to pocket without any issues.
- Ability to logout from pocket
- Simple news aggregator selection screen 
 - Preparing for the moment when it'll be possible to use service different than Inoreader.
- Scrollbars in article content activity 
 - Now it is possible to see when you are reaching end of the content. 
- Fixed FAB not hiding fully on some devices 
- **Activity swipe back action** 
 - Quickly return to main feed by swiping from the left edge of the screen.
- Toolbar in article content screen now respects auto hiding setting 
- Subscriptions list now displays little icons 
- Fixed not being able to access article content when loaded many articles 
- Rotating screen shouldn't make content to get loaded again 
- Saving articles to pocket from content activity now actually saved correct article and not its friends
- Scroll position when rotating screen while reading article is now restored

# <a id="v0.4.0">0.4.0 - View pager and automatic night mode (Mar 19, 2016)</a>
This version adds new way to navigate between articles from within the article details activity. In addition there is now support for automatic night mode that changes theme based on time of the day. The header in article details was also improved.

- **Horizontal articles navigation**
  - Loads more articles when you reach far right
  - Makes sure to go to current position after returning to main feed
  - Respects mark as read on scroll user setting
- **More advanced theme selection screen**
  - Allows you to select whether automatic night mode is enabled and which themes should be used with or without it
- Automatic night mode
- Amoled theme
- New article details header
  - Transparent toolbar above header image
  - Header is locked in position giving cool effect when scrolling content
- Removed big empty space that could appear in some articles

# <a id="v0.3.0">0.3.0 - Long press actions (Mar 15, 2016)</a>
- Logout confirmation
- Option to disable images visibility in main feed
- User information in navigation drawer
- Time and subscription in article activity
- Video playing
- Theme improvements
- **Article actions bottom sheet**
- Article swipe action icons now change correctly
- Long press actions for article content view link
- Subscriptions now refresh after adding new
- Pull to refresh in subscription list
- Error messages when failed to (un)subscribe to new feed

# <a id="v0.2.0">0.2.0 - Theming and subscriptions list (Mar 11, 2016)</a>
Improved look and basic subscription list.

Features:

- Look improvements to follow material design guidelines
- Dark theme
- Simple error view
- Unread articles count inside of navigation drawer
- Subscription list
- Way to add new subscription
- Subscriptions removing feature
- Option to disable toolbar hiding
- Bug fixes

# <a id="v0.1.0">0.1.0 - The beginning (Mar 6, 2016)</a>
First private version of the application. 

Main features:

- List of all unread articles 
- Toggling read state of article 
- Saving article to Pocket 
- Error view 
- Simple all read view 
- Basic article content activity with images 
- Mark articles as read on scroll
- Opening articles with Custom Tabs