## Custom Europe Transmitter Network for Local Radio Mod by Koenvh.

### What does this include?

Updated and cleaned `cities-ets2.js` file: Added new locations, removed some maps, sorted the cities to the appropiate variables etc. This configuration, by default, supports all the DLCs, and additionally rusMap, Promods and Promods Middle East. <br>
Updated and cleaned `stations-europe.js` file: Added many new stations, updated some streams, logos and the main point is that **local stations** are added.

## Usage

Firstly, download the [Koenvh's Local Radio app](https://github.com/koenvh1/ets2-local-radio)

Download the .zip file from [here](https://github.com/barteqcz/custom-transmitter-network/releases/latest), and unpack it inside the app directory, into a `web` folder. While copying the files, It'll ask you if it should replace the files - **YES, ALWAYS REPLACE ALL** <br>
You can also just download the [source code](https://github.com/barteqcz/ctn/archive/refs/heads/main.zip), and do this same. <br>

## Downloader/updater tool

To make it easier to keep the files updated, or generally download them, I wrote a simple program in Python that automatically downloads the files from this repo, and replaces the outdated ones with 'em. I wanna keep my whole work open-source, so there is a mini-repo with the code of this tool: [downloader tool](https://github.com/barteqcz/ctndownloader). It's very ease to use - just double-click it and it will download up-to-date files from this repo :)

## Why online data retrieving doesn't work?

The app, currently, doesn't fully support HTTPS connection for the data retrieving. Mostly it worked, everything was okay, but the data wasn't downloaded correctly, so, for example, in-game overlay didn't work. I can't use HTTP since I'd be using GitHub domain, which is enforcing HTTPS. As soon as the app starts using HTTPS, I will update this readme. 

## Reporting issues/bugs

In case you found some bug, which is related to the cities and/or the stations, please open a pull request.<br>
Hope you will like the work I've done, and mainly, Have fun!
