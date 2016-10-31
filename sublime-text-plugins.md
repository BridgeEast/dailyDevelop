## My sublime text plugins

`https://packagecontrol.io/`

### install package control
```
ctrl + `
```
then 

```
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

- AngularJs
	- AngularJS code completion, snippets, go to definition, quick panel search, and more.

- AutoFileName
	- Sublime Text plugin that autocompletes filenames

- Babel

- Better CoffeeScript
	- Bracket and tag highlighter for Sublime Text 
- CoffeeCompile
	- Preview compiled CoffeeScript in your editor!
- CoffeeComplete Plus(Autocompletion)

- Color Highlighter
- ColorPicker
- ConvertToUTF8
- Csscomb
- DeleteBlankLines
- DocBlockr
- Elementor
- Emmet
- Git
- GitGutter-Edge
- HTMLBeautify
- Jade
- Jade Snippets
- Markdown Extended
- Markdown Preview
- Material Theme
- Package Control
- Pretty JSON
- Python Completions
- PyV8
- React ES6 Snippets
- react-native-snippets
- ReactJS