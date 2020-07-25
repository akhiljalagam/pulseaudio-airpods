<!-- ![Mastodon Follow](https://img.shields.io/mastodon/follow/28693?domain=https%3A%2F%2Fmastodon.online&style=flat-square) -->
<!-- ![Keybase PGP](https://img.shields.io/keybase/pgp/akhiljalagam?style=flat-square)
![Keybase BTC](https://img.shields.io/keybase/btc/akhiljalagam?style=flat-square)
 -->
# pulseaudio-airpods 💃🕺
a shell script for managing airpods and airpods pro on linux.  

## Dependencies
```
sudo add-apt-repository ppa:smoser/bluetooth  
sudo apt-get install ofono-phonesim ofono  
git clone https://github.com/rilmodem/ofono.git /opt/ofono  
```

## Tweak the script for first time
replace MAC and card name in the script
```
AIRPODS_MAC='4C:6B:E8:80:46:84' # it should be somewhere in blueman-manager  
AIRPODS_NAME='bluez_card.4C_6B_E8_80_46_84' # you can find this using 'pactl list cards' command  
```

## Usage
```
pusleaudio-airpods connect/toggle_profile/disconnect
```
## Note
you should first pair your airpods using blueman and trust them to use this script

## Contributions are welcome

## Say thanks:
  
  Just letting me know you're enjoying this plugin is a great way to say thanks!
  
  You can do so by staring the GitHub repo.
  
## Troubles?
  
  If you have any kind of trouble with it, just let me now by raising an issue on
  the GitHub issue tracker here:

  It should be there 👆 👀
