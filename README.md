# update-ddnss

Small script to update ddnss.de domain.

Inspired from here:
https://github.com/M0ses/ddnss-update

## Usage
```
ddnss-update <KEY> <HOST>
```
Or create files
```
mkdir ~/.ddnss-update
touch ~/.ddnss-update/keyauth
touch ~/.ddnss-update/hostname
echo KEY > ~/.ddnss-update/keyauth
echo HOST > ~/.ddnss-update/hostname
```
Then you can invoke `ddnss-update` without parameters.