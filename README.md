## Custom Europe Transmitter Network for Local Radio Mod by Koenvh.

That's my customized transmitter network for Europe. <br>
In case you found some bug, which is related to the cities and/or the stations, please open a pull request.<br>

### What does this include?

Updated and cleaned `cities-ets2.js` file: Added new locations, removed some maps, sorted the cities to the appropiate variables etc. This configuration, by default, supports all the DLCs, and additionally rusMap, Promods and Promods Middle East. <br>
Updated and cleaned `stations-europe.js` file: Added many new stations, updated some streams, logos and the main point is that **local stations** are added.

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

Hope you will like the work I've done, and mainly, Have fun!
