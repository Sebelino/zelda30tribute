## Zelda 30 Year Tribute

#### A free HTML5/WebGL remake of Nintendo's original Legend of Zelda. This time in 3D!


## How to Play

Although you may no longer play on [zelda30tribute.com](http://www.zelda30tribute.com), you can play it off a
localhost webserver or your own webserver.

#### Running on your local machine.

Download the www/ folder and all of its contents. Start up a local webserver and open index.html in a browser.

**Note**: You also need to download the missing assets and place them in their respective directories. Make sure that you have Python 2.7 installed and use the CLI script `manage_assets.py` to download the assets from an external mirror and "unpack" them, like so:
```bash
python2 manage_assets.py download
python2 manage_assets.py unpack
```
If you are running Windows and are clueless on how to do this, simply follow these steps:

1. Create a file named `getassets.bat` in the same folder as `manage_assets.py`.
2. Copy and paste the two lines above into it.
3. You may need to replace `python2` with `python` or even with the full path (e.g. `C:\Python27\python.exe`).
4. Double-click on the newly created file.

#### In your own site

Upload the www/ folder and all of its contents to your FTP server, then open
index.html in a browser.



## Legal

This is released under the [MIT License](http://mit-license.org/) (see [License.txt](LICENSE.txt)). 

The Zelda 30 Year Tribute project launched in April 2015. It got a bunch of press coverage and saw half a million unique visitors in 3 days. Nintendo shut the site down with a DMCA complaint (no action was taken against the authors, GitHub, or other hosting websites). So we took it down and open sourced it here. Enjoy!

**Note**: This fork and every revision therein is purged of any copyright-infringing assets (obvious ones, anyway). That includes PNGs, MP3s, and other binaries.
