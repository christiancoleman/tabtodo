# Tab-To-Do Chrome Addon

The Tab-To-Do addon \(Id = [pjajmbdjiiboeoaaplgcigkmcljimddm](https://chrome.google.com/webstore/detail/tab-to-do/pjajmbdjiiboeoaaplgcigkmcljimddm)\) has been pulled from the [Chrome Web Store - Main Page](https://chrome.google.com/webstore/category/extensions), and the associated web site - [Tab-To-Do.com](https://tabtodo.com) - also appears to be inaccessible. I really liked this addon mainly because of its dependable ability<b><sup>1</sup></b> to sticky-rename<b><sup>2</sup></b> my Chrome tabs. 

Using the [Wayback Machine](https://archive.org/web/) I was able to look at a very old version of the Tabtodo.com website<b><sup>3</sup></b>. On it<b><sup>4</sup></b>, it had a link to a [Github repository](https://github.com/tabtodo/tabtodo/) that still exists as of 2019-05-08... It just hadn't been updated for roughly 4 years. :thumbsdown:

So this is when I found out that Chrome extensions are stored client-side and therefore the newest version of the addon should be saved locally on my machine.

> C:\Users\\_*\{username\}*_\AppData\Local\Google\Chrome\User Data\Default\Extensions\\_*\{appId\}*_

Extension source-code can be found in this folder location where the _*\{appId\}*_ is the same identifier used in Chrome Web Store i.e. pjajmbdjiiboeoaaplgcigkmcljimddm.

--------------------

# So what are my goals?

* Analyzing the code for v2.1
* Refactoring where possible
* Exploring Chrome extension development options, standards, etc.

--------------------

# Resources
## Chrome Extension Development
* [Chrome Web Store - Main Page](https://chrome.google.com/webstore/category/extensions)
* [Chrome Extension Development - Getting Started Tutorial](https://developer.chrome.com/extensions/getstarted)
* [Extension Overview](https://developer.chrome.com/extensions/overview) - Takes a step back and fills in the blanks after having finished the `Getting Started Tutorial`

## Tab-To-Do (Legacy) Links
* [~Tab-To-Do Extension - Chrome Web Store Link~](https://chrome.google.com/webstore/detail/tab-to-do/pjajmbdjiiboeoaaplgcigkmcljimddm) - `Not Found` as of 2019-05-08
* [~Tab-To-Do.com - Official Web Site~](https://tabtodo.com) - `Looks Like This Domain Isn't Connected To A Website Yet` as of 2019-05-08.
* [Tab-To-Do's Public Github Repo](https://github.com/tabtodo/tabtodo/) - It was a bit out-of-date but any history is better than none

--------------------

<b><sup>1</sup></b> By sticky-rename I mean that the addon could rename a Chrome tab and that name would persist regardless of whether you clicked links within the page or refreshed the browser.

<b><sup>2</sup></b> dependability?? ¯\\_(ツ)_/¯

<b><sup>3</sup></b> Or was it the web store page? I know I looked up both. I just forget which one lead me to it.

<b><sup>4<sup></b> Whatever that was...