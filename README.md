Sublime text 2 Config
=====================
My [Sublime Text 2](http://www.sublimetext.com/2) preferences.  

Package list
------------
[Package Control](http://wbond.net/sublime_packages/package_control)  
[All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete)  
[jQuery](https://github.com/SublimeText/jQuery)  
[JsFormat](https://github.com/jdc0589/JsFormat)  
[Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)  
[Search WordPress Codex](https://github.com/welovewordpress/SublimeWordPressCodex)  
[SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)  
[Stylus](https://github.com/billymoon/Stylus)  
[Wordpress](https://github.com/purplefish32/sublime-text-2-wordpress)  
[ApacheConf.tmLanguage](https://github.com/colinta/ApacheConf.tmLanguage)  
Install package control
-----------------------
Install package control in Sublime Text 2 by pasting the following command into the console.  
```import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print('Please restart Sublime Text to finish installation')```
Install Theme
-------------
I use [artillery](http://blog.benjaminwiederkehr.com/all/downloads/textmate-theme) which was originally created for Textmate but those themes ports nicely to sublime text 2. Just drop the unzipped ```Artillery.tmTheme``` file into sublimes ```packages```directory.
Preferences Location
--------------------
`~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/Preferences.sublime-settings`