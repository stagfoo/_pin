# 🌄 _pin 
decenteralised mood board

# Why did you make this?
I use Pinterest for mood boards for my projects but:
- its central and controlled by pinterest
- Pinterest can remove my pins
- is not tightly connected to my code project
- no permissions control like git

Inspired by [TiddlyWiki](https://tiddlywiki.com/) a single file wiki system, I want a single file mood board system.

# How to I add/edit the board
currently you need to disable CORS locally, here are some easy extension
- [Chrome Addon](https://chrome.google.com/webstore/detail/easy-cors/gcdaaelgdlicnnichhholnoagafangej)
- [Firefox Addon](https://addons.mozilla.org/en-US/firefox/addon/cors-everywhere/)
- you can ALWAYS view the images even offline, its only ADDING images that requires a CORS disabled browser
- the whole image is stored in the html

# How do I use it?
- open the index.html in your browser
- copy a url of an image and paste it into the prompt
- save the html file with ctrl + s ~ (eg: board-cool-stuff.html)
- all the code to expand the board is stored in the html so open it again with a CORS disabled browser and continue editing.

# Can I update an old board to a new version?
- yes, kinda, by default the app part of the file is at the bottom of the html and you can swap it out for a new version.
- the ui is inside the `ui` div so you can swap that out too

```html
<body>
 <div id="ui">...</div>
 <div id="board">...</div>
 <!------------------------ SYSTEM ------------------------------------>
 ...app logic to replace
 <!------------------------ SYSTEM ------------------------------------>
</body>
```

# Planned features
- tags
- tag searching
- grid settings
- build in pinterest searching?
- CORS fixes/wrapper application?
- theming

# Whats inside
- HTML - no framework
- JS - no framework
- CSS - no framework