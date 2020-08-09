# Restyle NTULearn
Improves aesthetic of NTULearn (Blackboard) with Stylus extension. 

![NTULearn Redesign](https://beverleyy.github.io/images/website/ntulearn.png)

## Features

* Colorful dark interface is easier on the eyes
* Reduced clutter from school advertisement spam
* Remove all unnecessary ads/notices (!)
* Learn some CSS and improve your NTULearn experience! Easy to edit from the Stylus GUI.

## How to use
1. Install the Stylus extension:
   * [Chrome or Brave](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
   * [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
   * [Opera](https://addons.opera.com/en/extensions/details/stylus/)
2. Make a new style (under Manage)
3. Import Mozilla Format code from the [`import.css`](https://raw.githubusercontent.com/beverleyy/ntulearn-restyle/master/import.css) file
4. Save and exit, or customize the colors and images in the code (CSS)

## Frequently-asked
### Q: Can I change the colors and background?
A: **Yes! If you have some basic CSS knowledge, it is easy.** The background image needs to be uploaded to a host, and you will replace the direct link to the background-image property under `body`. For the colors, you can change them with a Ctrl+F once identified. I am working on making a GUI for customization soon.

### Q: If I already have the Stylish extension, do I still need to install Stylus?
A: No, this style works also with Stylish browser extension. However, you may want to read [these](https://www.alphr.com/security/1009689/stylish-spyware-google-chrome-extension) [articles](https://www.ghacks.net/2018/08/17/stylish-add-on-returns/) about why I recommend users to use Stylus over Stylish.

### Q: Does this work with Blackboard from other universities?
A: During my study abroad at Purdue, I tested the extension out-of-the-box on the Purdue Blackboard - the key finding is that every university organizes and tweaks Blackboard in a different way, so you would need to edit the code to make it compatible with another university's version.

### Q: Does this work with Instructor Blackboard?
A: With the old Blackboard, I had gotten access to the instructor version through some connections. However, my access is limited as I am only a student, so it may not work for everything. It is functional, however.

### Q: I already have the NTULearn Tweak by ZaynJarvis, will this still work?
A: **No, this code does not work** with the [NTULearn Tweak](https://chrome.google.com/webstore/detail/ntulearn-tweak-ntu/gnpfhhfeloajnenikhgdoagcfalofnjb). If you would like to use this, please uninstall the extension first.

## Updates
Updates will be committed to the `import.css` file in this repository as soon as they are available. Bear in mind that I myself am a student and this is only a side project. 

Also, this plugin will be maintained up until my graduation in (hopefully) July 2021.

## To-do list
* Make this a proper Chrome/Firefox extension (then, I can introduce some Javascript-only features too!)
* Create a proper GUI for easier editing/change background/change color scheme
* Improve Instructor Blackboard features/layout
* Add a light mode

## Changelog
* 9 Aug 2020:
  * Introduced sticky sidebars on course pages
  * Updated Instructor Blackboard code to resolve new artefacts
* 8 Jun 2020: 
  * Upgraded code for NTULearn 2.0 after returning from study abroad
  * Initial code upload to Github
* 25 Jan 2019: 
  * Fixed artefacts on Instructor Blackboard
