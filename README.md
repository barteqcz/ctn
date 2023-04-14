## Custom transmitter network for Europe to use with Local Radio Mod by Koenvh.

That's my customized transmitter network for Europe. <br>
In case you found some bug, please open a pull request <br>
Hope you will like the work I've done :) Have fun!

## Usage

### Locally

In this case, the app will simply use the local files.

Download the .zip file from [here](https://github.com/barteqcz/custom-transmitter-network/releases/latest), and unpack it inside the app directory, into a `web` folder. <br>
You can also just download the source code, and do this same, but additionally you can remove this `README.md`. <br>
Then, you'll have to modify the `config.js` which is in the app directory, and change the following lines like this:
```    
"url-prefix": "",
    "ets2": {
        "map": "cities/cities-ets2.js",
        "stations": "stations/stations-europe.js",
},
```

### Online retrieving

In this case, the app will retrieve the data directly from this repository, so no need to re-download the code when an update is released. So, just modify your `config.js` like this:
```    
"url-prefix": "http://barteqcz.github.io/custom-transmitter-network/",
    "ets2": {
        "map": "http://barteqcz.github.io/custom-transmitter-network/cities/cities-ets2.js",
        "stations": "http://barteqcz.github.io/custom-transmitter-network/stations/stations-europe.js",
},
```
