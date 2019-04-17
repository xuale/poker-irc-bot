# Twitch Plays Poker IRC Bot

Repurposed and renamed clone of [Twitch Plays](https://github.com/aidanrwt/twitch-plays).

# Installation

## Credit goes to [original repo](https://github.com/aidanrwt/twitch-plays)

You're going to need to have [pywin32](http://sourceforge.net/projects/pywin32/) installed. If you run into any errors try running this with Python [2.7.x](http://www.python.org/download/releases/2.7/).

Rename `config/config_dist.py` to `config/config.py`, and replace the username/password there with your Twitch username and [OAuth token](http://www.twitchapps.com/tmi/). Feel free to modify the start throttle here aswell.

After you've set that up, open up your terminal and type `python serve.py`. If your username/password is wrong you will be notified.

Whilst the script is running make sure you have your emulator in focus as your primary window. If you click onto another window, the script won't work. If you're not able to stay focused on one window as you need to do other things with your computer, you could try running all of this from within a virtual machine.
