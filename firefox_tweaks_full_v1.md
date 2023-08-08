# Quicklist

|     |     |
| --- | --- |
| browser.bookmarks.openInTabClosesMenu | false |
| browser.tabs.loadBookmarksInTabs  <br>browser.tabs.loadBookmarksInBackground | true |
| browser.download.lastDir.savePerSite | false |
| browser.download.folderList | 2   |
| layout.spellcheckDefault | 2   |
| browser.urlbar.maxRichResults | 17  |
| browser.tabs.tabMinWidth | 110 |
| browser.search.openintab | true |
| browser.sessionstore.interval | 35000 (35 Seconds) |
| browser.cache.disk.capacity | 512000 |
| security.dialog\_enable\_delay | 0   |
| security.notification\_enable\_delay | 0   |
| view\_source.editor.external  <br>view\_source.editor.path | true  <br>C:\\Users\\futur\\AppData\\Local\\Programs\\Microsoft VS Code\\Code.exe |

# about:config Essential Tweaks

| Prefer | Setting | Default | Value | Description |
| --- | --- | --- | --- | --- |
| ✔   | `browser.bookmarks.openInTabClosesMenu` | true | false |     |
| ✔   | `browser.tabs.loadBookmarksInTabs`  <br>`browser.tabs.loadBookmarksInBackground` | false | true | Always open bookmarks in new tabs. |
| ✔   | `browser.download.lastDir.savePerSite` | \-  | false |     |
| ✔   | `browser.download.folderList` | 1   | 2   | By default, Firefox downloads go to the Windows “Downloads” folder, but you can change this by tweaking `browser.download.folderList`.  <br>  <br>**0** – Saves all downloads to the desktop  <br>**2** – Saves to the same location as the previous download |
| ✖   | `browser.search.openintab`  <br>`browser.urlbar.openintab` | false | true |     |
| ✔   | `layout.spellcheckDefault` | 1   | 2   | To enable Firefox Spell Checker in all text boxes, search for: `layout.spellcheckDefault` and set its value to 2. Now, to make those lines more noticeable, change their value as follows:  <br>  <br>**0** no highlighting  <br>**1** dotted line  <br>**2** long dots  <br>**3** single straight line  <br>**4** double underline  <br>**5** default squiggly line |
| ✖   | `config.trim_on_minimize` | false | true | [http://kb.mozillazine.org/Config.trim\_on\_minimize](http://kb.mozillazine.org/Config.trim_on_minimize) |
| ✖   | `dom.max_script_run_time` | 10  |     | [http://kb.mozillazine.org/Dom.max\_script\_run\_time](http://kb.mozillazine.org/Dom.max_script_run_time) |
| ✖   | `browser.tabs.insertRelatedAfterCurrent` | true | false | Normally every new tab appears adjacent to the current tab, If you would like new tabs to open at the end of all the tabs, set this. |
| ✖   | `extensions.checkCompatibility` | \-  | false | Disable Compatibility Checking for Extensions |
| ✖   | `browser.tabs.animate`  <br>`browser.panorama.animate_zoom`  <br>`browser.fullscreen.animateUp` | \-  | false | To disable animations for new tabs, and Firefox’s “Tab Groups” feature. |
| ✔   | `browser.urlbar.maxRichResults` | 10  | 20  | Adjust the Smart Location Bar’s Number of Suggestions. When you start typing in the location bar, a drop-down list of suggested sites will be shown.  <br>  <br>If you want it to show more (or less) than ten suggestions, you can adjust the `browser.urlbar.maxRichResults` keys and get it to show the number you want. |
| ✖   | `browser.urlbar.quickactions.enabled` | \-  | true | Enables Quick Actions in Firefox. in the address bar, type `>` and use the `Spacebar` to activate Quick Actions mode. |
| ✖   | `toolkit.cosmeticAnimations.enabled` | true | false | Disable Unnecessary Animations. Animations in Firefox Quantum are not a bad thing, **but if you have an old PC** where every MB of RAM counts or simply don’t need these animated flourishes, you can disable them. |
| ✖   | `browser.tabs.animate` | \-  | false | Disable Tab Animation |
| ✔   | `browser.panorama.animate_zoom` | \-  | false | Disable Panorama Animation |
| ✖   | `browser.display.show_image_placeholders` | true | false | Show / Hige Image Placeholders |
| ✔   | `browser.tabs.tabMinWidth` | 76  | 100/125/150 | The default tab width is now `76` pixels, whereas before it was `100`. To adjust this, go to `browser.tabs.tabMinWidth`. |
| ✔   | `browser.sessionhistory.max_total_viewers` | \-1 (adaptable) | 10 / 16 / 20 | Firefox may slow down your PC with the default settings. This could be in part because of how it stores Web pages in its short-term memory (or RAM), which you can access using the Back and Forward buttons.  <br>  <br>`browser.sessionhistory.max_total_viewers`:  <br>Set to any number, reflecting the number of pages you want to store. (We recommend less than 4 if your PC is struggling for speed, while those with 4GB plus can go for 8 or more.) |
| ✔   | `browser.sessionhistory.max_entries` | 50  | 70 / 80 / 100 | Effects how many pages each tab stores in its Back/Forward history altogether. |
| ✔   | `browser.search.openintab` | false | true | Open New Tab for Search Box Results. By default, the things you search for in the Firefox search box open in the current tab. To open in a new tab instead, you’ll need to modify `browser.search.openintab`. |
| ✔   | `browser.sessionstore.interval` | 15000 (15 Seconds) | 35000 (35 Seconds) | Firefox saves your session every 15 seconds by default, but you can change the value of `browser.sessionstore.interval`so that Firefox will save the session at a longer interval. |
| ✖   | `browser.link.open_newwindow.restriction` | 2   | 0   | When you come across a site that executes javascript to open a new window, and if the pop-up window is without all the usual window features, e.g. back/forward/reload buttons, status bar, etc., Firefox will automatically treat it as a pop-up and will not open it as a new tab.  <br>  <br>However, if you find this to be a nuisance and want to open all new windows in new tabs, you can specify it via the browser.link.open\_newwindow.restriction setting.  <br>  <br>**0** Open all links the way you have Firefox handle new windows  <br>**1** Do not open any new windows  <br>**2** Open all links the way you have Firefox handle new windows unless Javascript specifies how to display the window |
| ✔   | `browser.cache.disk.capacity` | 256000 (KB) | 512000 (KB) | **0** - Disable disk caching  <br>Any value **lower than 50000** reduces the disk cache  <br>Any value **higher than 50000** increases the disk cache |
| ✔   | `browser.cache.offline.capacity` | 512000 (KB)  <br>(512 MB) | 1024000  <br>(KB)  <br>(1024 MB) | If you do not have access to the Internet most of the time, you may want to increase the offline cache so that you can continue to work offline.  <br>  <br>By default, Firefox caches 500MB of data from supported offline web apps. You can change that value to any amount you like. |
| ✔   | `security.dialog_enable_delay` | 1000 | 0   | Every time you install a Firefox add-on, you will have to wait for several seconds before the actual installation starts. To cut down on this waiting time, you can turn the preference `security.dialog_enable_delay` off so that the installation will begin immediately. |
| ✔   | `security.notification_enable_delay` | 500 | 0   | Suppress delay for main action in popup notifications. |
| ✔   | `dom.event.contextmenu.enabled` |     | false | Don't allow websites to prevent use of right-click,  <br>or otherwise messing with the context menu. |
| ✔   | `view_source.editor.external`  <br>`view_source.editor.path` | false  <br>&lt;blank&gt; | true  <br>&lt;file path to your editor here&gt; | This is very useful for developers who are always using the “`view source`” function. This tweak allows you to view the source code of a given website in an external editor.  <br>  <br>**Note: Don't include quotes in the file path to your editor.** |
| ✔   | `Browser.download.saveLinkAsFilenameTimeout` | 4000 (4 seconds) | 6000 / 8000 (6 or 8 seconds) | When you right-click and select “Save Link As … ” the browser will request the content disposition header from the URL to determine the filename.  <br>  <br>If the URL does not deliver the header within one second, Firefox will issue a timeout value. This could happen very frequently in a slow network connection environment. To prevent this issue from happening frequently, you can increase the timeout value to reduce the possibility of a timeout. |
| ✔   | `network.http.version`  <br>`network.http.pipelining`  <br>`network.http.pipelining.maxrequests`  <br>`network.http.pipelining.ssl`  <br>`network.http.proxy.pipelining` | `1.1`  <br>`Unset`  <br>`Unset`  <br>`Unset`  <br>`Unset` | `1.1`  <br>`true`  <br>`8`  <br>`true`  <br>`true` | **Enable pipelining:** By applying these changes, Firefox is configured to enable the pipelining feature of the http 1.1 protocol and send eight simultaneous http requests to the website.  <br>  <br>This increases your browsing speed, provided your Internet connection is fast enough to handle these simultaneous requests. Going beyond eight will not help since it is the maximum limit for Firefox. |
| ✖   | config.trim\_on\_minimize | \-  | `true` | Configure Firefox to use 10 MB RAM when minimised |
| **✖** | **dom.ipc Reccomendation 1**  <br>dom.ipc.processCount  <br>dom.ipc.processCount.webIsolated | 8  <br>4 | 12  <br>6 | Each content process is listed as firefox.exe on Windows with no distinguishing information-  <br>  <br>Firefox runs as many content processes as you see listed there, provided that multi-process use is enabled in the browser.  <br>  <br>Please note that it will use more memory when you increase the number of content processes in multi-process Firefox, and less memory if you reduce the number.  <br>  <br>Mozilla ran some memory benchmarks recently and found out that multi-process Firefox will use between 10% to 20% more memory initially with one content process enabled, and about double the memory with 8 content processes. |
| **✔** | **dom.ipc Reccomendation 2**  <br>dom.ipc.processCount  <br>dom.ipc.processCount.webIsolated | 8  <br>4 | 1  <br>1 | By default Firefox launches as many processes as you got CPU cores. This is highly counter productive, as this leads to much more memory usage as necessary. In addition switching tabs may now result not only in having to load the content back from the swap into memory, but also swapped in duplicated libraries etc. |
| ✖✖✖ | dom.ipc.processCount.extension | 1   | 1   | **DO NOT TOUCH. EXTENSIONS WILL BREAK** |
| ✔   | network.captive-portal-service.enabled |     | false | Don't try to find captive portals |
| ✔   | network.notify.checkForProxies |     | false | Don't try to find proxies |
|     |     |     |     |     |

# Browser Cache

| Prefer | Setting | Default Value | Tweaked Value | Description |
| --- | --- | --- | --- | --- |
| ✔   | `browser.cache.disk.capacity`  <br>Depends on:  <br>`browser.cache.disk.smart_size.enabled` | 256000 KB (256 MB),  <br>True | 8,192,000 KB (8gb),  <br>False | Smart Size:  <br>Sets disk cache size according to the available disk space. We want this **off** to utilize `browser.cache.disk.capacity`.  <br>  <br>**0** - Disable disk caching  <br>Any value **lower than 50000** reduces the disk cache  <br>Any value **higher than 50000** increases the disk cache |
| ✔   | `browser.cache.offline.capacity` | 512000 (KB)  <br>(512 MB) | 1536000 (KB)  <br>(1536 MB) | If you do not have access to the Internet most of the time, you may want to increase the offline cache so that you can continue to work offline.  <br>  <br>By default, Firefox caches 500MB of data from supported offline web apps. You can change that value to any amount you like. |
| ✔   | `browser.cache.frecency_half_life_hours` | 6 (Hours) | 12 (Hours) | The ‘least used’ entries are recognized by the lowest value of frequency we re-compute for each entry on its every access.  <br>  <br>The decay time is controlled by the `browser.cache.frecency_half_life_hours` preference and defaults to 6 hours. The best decay time will be based on results of an experiment.  <br>  <br>TLDR: Lower cache sweep intervals. |
| ✔   | `browser.cache.max_shutdown_io_lag` | 2   | 4 / 8 / 12 / 16 | Let the browser finish more IO on shutdown.  <br>[https://bugzilla.mozilla.org/show\_bug.cgi?id=913822](https://bugzilla.mozilla.org/show_bug.cgi?id=913822) |

# Memory Caching

For the disk cache entries we keep some of the most recent and most used cache entries’ meta data in memory for immediate zero-thread-loop opening. The default size of this meta data memory pool is only 250kB and is controlled by a new `browser.cache.disk.metadata_memory_limit` preference. When the limit is exceeded, we purge (throw away) first **expired** and then **least used** entries to free up memory again.

| Prefer | Setting | Default | Tweaked | Description |
| --- | --- | --- | --- | --- |
| ✔   | `browser.cache.memory.capacity` | \-1 | 2097152 | Fixed maximum 2 GB in memory cache |
| ✔   | `browser.cache.memory.max_entry_size` | 5120 | 10240 / 15360 /   <br>30720 / 327680 | Maximum size of in memory cached objects |
| ✔   | `browser.cache.disk.metadata_memory_limit` | 250 | 500 /   <br>1000 /  <br>3000 /  <br>6000 /  <br>15360 | increase size (in KB) of "Intermediate memory caching of frequently used metadata (a.k.a. disk cache memory pool)" |

# Google Safe Browsing

1\. Disable Google Safe Browsing and malware and phishing protection.  
2\. Stop sending links and downloading lists from google.  
3\. Security risk, but privacy improvement.  
4\. Note: this list may be incomplete as firefox updates, be sure to search for browser.safebrowsing.provider.google\*  
5\. Also simply setting safebrowsing.\*.enabled to false should make setting the URL's to blank redundant, but better to be safe.  
6\. If you see anything pointing google, probably best to nuke it.

| Prefer | Setting | Recommended Value |
| --- | --- | --- |
| ✔   | `browser.safebrowsing.enabled` | false |
| ✔   | `browser.safebrowsing.phishing.enabled` | false |
| ✔   | `browser.safebrowsing.malware.enabled` | false |
| ✔   | `browser.safebrowsing.downloads.enabled` | false |
| ✔   | `browser.safebrowsing.provider.google4.dataSharing.enabled` | blank |
| ✔   | `browser.safebrowsing.provider.google4.updateURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.reportURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.reportPhishMistakeURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.reportMalwareMistakeURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.lists` | blank |
| ✔   | `browser.safebrowsing.provider.google4.gethashURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.dataSharingURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.dataSharing.enabled` | false |
| ✔   | `browser.safebrowsing.provider.google4.advisoryURL` | blank |
| ✔   | `browser.safebrowsing.provider.google4.advisoryName` | blank |
| ✔   | `browser.safebrowsing.provider.google.updateURL` | blank |
| ✔   | `browser.safebrowsing.provider.google.reportURL` | blank |
| ✔   | `browser.safebrowsing.provider.google.reportPhishMistakeURL` | blank |
| ✔   | `browser.safebrowsing.provider.google.reportMalwareMistakeURL` | blank |
| ✔   | `browser.safebrowsing.provider.google.pver` | blank |
| ✔   | `browser.safebrowsing.provider.google.lists` | blank |
| ✔   | `browser.safebrowsing.provider.google.gethashURL` | blank |
| ✔   | `browser.safebrowsing.provider.google.advisoryURL` | blank |
| ✔   | `browser.safebrowsing.downloads.remote.url` | blank |

&nbsp;