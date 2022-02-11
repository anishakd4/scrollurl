## Usage

If you for some reason do want to use this project in your own website, here's a quick guide to using it.

### Define the Script Tag

```html
<script type="text/javascript" src="https://jfenn.me/Scrurl/scrurl.js"></script>
```

### Start the Scrolly Thing

```javascript
Scrurl.display("a bunch of text", {
  "scrolldelay": 200, //the delay (in ms) between each scroll update
  "scrollamount": 1,  //the amount of characters to scroll on each update
  "direction": "left" //the direction to scroll through the characters in
});
```

### Stop the Scrolly Thing
This will stop the url from scrolling, but will not remove it from the address bar, because frankly I'm just too lazy to do that, and I don't think anyone will use it if I do.

```javascript
Scrurl.display(null);
```