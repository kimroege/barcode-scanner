# barcode-scanner

https://www.teknologisk.dk/ydelser/brug-af-mobiltelefoner-i-supermarkeder/stregkoder-2d-barcodes-qr-code-smartphones/28676



```javascript
<script type="text/javascript">
	function barcode() {
	var url = 'https://cors-anywhere.herokuapp.com/http://www.rema1000.dk/JSONHandler.ashx?EAN=5700426293929';
	var xhttp = new XMLHttpRequest();
	xhttp.onreadystatechange = function() {
	    if (this.readyState == 4 && this.status == 200) {
	       console.log(JSON.parse(xhttp.responseText));
	    }
	};
	xhttp.open("GET", url, true);
	xhttp.send();
}
barcode();
</script>
```


![alt text][barcode]

[barcode]: https://www.teknologisk.dk/_/media/39531_barcode.jpg "Logo Title Text 2"
