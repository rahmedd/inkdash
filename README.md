# inkdash
This is a simple clock for e-ink readers such as the Nook or Kindle.

## Kindle details
 - The Kindle supports most of the ES5 spec.
 - The kindle browser is based on an old version of WebKit. It's similar to Safari 5 which is easier to debug than the kindle browser.
 - The Kindle browser uses UTC and the local timezone must be set manually.

## Known Issues
The Kindle may lose the configuration cookies when exiting the browser. On the Nook this isn't a problem, but I plan to store the config in the URL parameters.

### Credits
Form serialization library - 
https://github.com/defunctzombie/form-serialize
