# ToastyPlugin

* cordova plugin for creating toast masseges

* Usege:
window.plugins.toastyPlugin.show('YOUR TEXT HERE', 'long'/'short', succes func, error func)

For Example:
```js
window.plugins.toastyPlugin.show('It feels toasty in here!', 'long', function() {
        console.log('Excelsior!');
      }, function(err) {
        console.log('Uh oh... ' + err);
      });
```
