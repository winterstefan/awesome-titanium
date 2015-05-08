# awesome-titanium
> Interesting facts and links for the Titanium framework

# Topics
- [Before starting](#before-starting)
- [Developing your app](#developing-your-app)
- [Debugging tips](#debugging-tips)
- [App contribution](#app-contribution)



# Before starting

> A must-read for all newcomers. Mobile development with Titanium differs a lot from native Android and iOS development. Be sure to follow these basic steps.


## Slideshows

- [Best practices #1](http://de.slideshare.net/alessioricco/best-practices-in-apps-development-with-titanium-appcelerator) <br>
Fundamental DOs and DON'Ts, useful for every developer
- [Ten rules for better Titanium apps](http://de.slideshare.net/jamessugrue/10-golden-rules-for-outstanding-titanium-app) <br>
Further details about some learnings
- [Thread maintainance](http://www.slideshare.net/ronaldtreur/titanium-making-the-most-of-your-single-thread) <br>
Making the most of your single thread
- [Ultimate toolchain](http://fokkezb.nl/2014/10/18/the-ultimate-titanium-cli-toolchain/) <br>
Get used to some tools and tips for developing Titanium apps.
- [Keep your app responsive](http://www.tidev.io/2014/02/17/keeping-your-app-responsive-part-1/) <br>
Three part document for how to keep app response times small


## Development Environment
- [TiShadow](http://tishadow.yydigital.com/) <br>
The complete toolset for rapid titanium app development on multiple platforms (deploy, test and much more)
- [Alloy-Bootstrap](https://github.com/xavierlacot/Alloy-Bootstrap) <br>
Grunt setup with selective compilation to speedup the compilation und some other tool sets
- [ti-i18n](https://www.npmjs.com/package/ti-i18n) <br>
Add and manage your internationalization strings
- [ti-stealth](https://www.npmjs.com/package/ti-stealth) <br>
Remove console output before deploying



## Definitions

- [Proper logging](https://github.com/appcelerator/alloy/blob/master/Alloy/logger.js) <br>
A possible logger implementation with severities and color support
- [Logging source code location](http://www.tidev.io/2014/10/08/where-does-that-log-come-from/) <br>
Creating a logger with information about the current controller / widget
- [Proper string substitution](http://www.tidev.io/2015/01/26/formatting-strings-the-correct-way-using-an-old-friend-printf/) <br>
A prototyped printf function, that allows parameterized substitution: ``` greeting.printf({ name : 'John Doe', gender : 'male' }); ```
- [Globals in alloy.js](http://www.tidev.io/2014/10/15/managing-alloy-js-global-objects/) <br>
How to define variables inside your alloy.js



# Developing your app

> Common resources and tipps about the development process. No need for re-inventing the wheel!

## Find modules, widgets & controls

- [gitTio](http://gitt.io/) <br>
Leading resource for Titanium modules and Alloy widgets
- [UX Mobile Patterns](http://www.uxmobilepatterns.com/templates/) <br>
Example views and widgets for common UI problems
- [Titanium Controls](http://titaniumcontrols.com/) <br>
Visual control elements for Titanium
- [AlloyLove](http://alloylove.com/#) <br>
Small listing of Alloy-related modules


## Awesome resources

### Modules / Widgets

- [Wriststrap](https://github.com/TNuzzi/wriststrap) <br>
A Bootstrap-like implementation of UI building (grid system, helper classes, image & button styling, icon, ...)
- [TiLogCatcher](https://github.com/dbankier/TiLogCatcher) <br>
Listen to and handle Titanium errors
- [PullToRefresh](https://github.com/FokkeZB/nl.fokkezb.pullToRefresh) <br>
Refresh a table / list view by pulling on the top


# Debugging tips

> Your app doesn't work as expected? Take a look in here for tipps and guidelines.

- [Memory management](http://docs.appcelerator.com/titanium/3.0/#!/guide/Managing_Memory_and_Finding_Leaks-section-29004941_ManagingMemoryandFindingLeaks-Examplesourcesofmemoryleaks) <br>
How to debug your code and find possible memory leaks (Android & iOS)
- [Remote error reporting](https://github.com/FokkeZB/UTiL/tree/master/reporter) <br>
On App errors, open email dialog with all important debug information



# App contribution

> The app is ready for the world? Some adjustments have to be made for both the Apple app store & Google Play store.

## Icon and Splash Screen

- [Icon and Splash Screen definition](http://docs.appcelerator.com/titanium/latest/#!/guide/Icons_and_Splash_Screens) <br>
Appcelerator information about the different screen sizes and their image resolutions
- [Icon and Splash Screen generator](http://ticons.fokkezb.nl/) <br>
Generates the app images for all platforms
- [Icon and Splash Screen details](http://blog.mattstephens.co.uk/post/42021515092/splash-screen-launcher-icon-sizes-appcelerator-titanium) <br>
More details about these images and automated deployment

## Misc

- [Proper versioning](http://www.tidev.io/2014/10/29/versioning-builds-and-releases/) <br>
If you contribute the app, you'll need a fixed versioning system.


# Find inspirations

> Out there are lots of cool apps, designs and patterns. Feel free to take a look at these examples.

## Example projects

- [Dragon Shout App](https://github.com/rblalock/dragon_shout_app_open_source) <br>
Open source app for the game Skyrim
- [KitchenSink](https://github.com/Mindelusions/KitchenSink) <br>
Titanium self-made example app for Android & iOS with lots of UI elements / basic features. Useful to check if a feature is working on a device.
- [Android ActionBar](https://github.com/adampax/AlloyActionJackson) <br>
How to implement a proper ActionBar for Android users
- [Movie app](https://github.com/appcelerator/movies) <br>
Appcelerators open-source demo app for a video streaming app
- [Corporate Directory](https://github.com/appcelerator-se/corporate-directory) <br>
Appcelerators open-source demo app for browsing through business contacts


## Example screens
- [UI Pattern list](http://www.pttrns.com/) <br>
Dozens of iOS and Android screenshots from cool and inspirational apps

## Developers
- [Ben Bahrenburg](https://github.com/benbahrenburg?tab=repositories)
- [Fokke Zandbergen](http://fokkezb.nl/)
