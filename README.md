# IframeRefresh

Full page iframe that will automaticly refresh every set duration (default 5000 milliseconds or 5 seconds)

## Usage

Open iframe.html and change the two variables on lines 6 and 7.
```javascript
var  source = "http://milligram.cc"; 
var  refreshTime = 5000; 
```

Change the `source` variable to the link of the website you want the iframe to constantly refresh to.

The `refreshTime` variable is the time in milliseconds between refreshes. So if you want to refresh the iframe ever 7 seconds you would change it to
```javascript
var  refreshTime = 7000; 
```
