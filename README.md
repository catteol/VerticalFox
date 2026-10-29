![](./assets/header.png)

# VerticalFox
Get an Edge like auto-hide vertical tabs bar on Firefox! Powerd by Sidebery, you can have your bookmarks, pinned tabs all in side bar and get a clean, compact look.

<p align='center'>
   <img src='./assets/dark_theme.gif' style='max-height:480px;'/>
</p>
<p align='center'>
   <img src='./assets/light_theme.gif' style='max-height:480px;'/>
</p>

*The auto hide also works on Tree Style Tabs, but you may need to adjust the css to achieve the best look.*


## ⚠️ Currently maintained: Windows only

Only Windows is currently maintained, as I am unable to verify operation on other platforms. As a result, the macOS and Linux versions have not been updated.  
Contributions and test reports from macOS and Linux users are welcome.


## How to apply

1. You need to have [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) installed.
2. Download the files in release according to your operation system. You can also directly use the source files you need.
3. If you haven't customized your Firefox before, check out [this guide](https://www.reddit.com/r/firefox/wiki/userchrome/) for how to set up your Firefox and the profiles. TL;DR version:

   1. Navigate to `about:config` in the address bar and accept the risks.
   2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and toggle it to true (by double clicking on it).
   3. Navigate to `about:support` in the address bar, under **Application Basics**, find **Profile Folder** and open it. You should now see your profile folder.
   4. Inside your profile folder, create a new folder named `chrome` (all lower case).
4. Once you have your `chrome` folder under your profile directory, copy the `userChrome.css` you downloaded into `chrome`. Alternatively you can create a blank `userChrome.css` and paste the code. Restart your browser.
5. Go to the settings of Sidebery, go to **Styles editor**, paste all the code from `sidebery_styles.css`. Please turn on "**Show navigation bar in one line**" under "**Navigation bar**" in the settings.

<p align='center'>
   <img src='./assets/img1.png' style='height:400px;'/>
</p>


Now you can enjoy your new Firefox!

## Frequently Asked
Q: **How to disable sidebar auto-hide?**

A: Open `about:config`, search for `verticalfox.sidebar.autohide`, and if it doesn’t exist, create it as a Boolean and set it to false.
