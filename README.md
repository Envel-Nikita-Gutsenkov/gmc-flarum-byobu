# Byōbu by FriendsOfFlarum

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/FriendsOfFlarum/byobu/blob/master/LICENSE)

Private discussions for your forum. Allows you to select specific recipients for your discussions.

## Goals

- Create discussions only specific users or groups can participate in.
- Force new posts in these private discussions to show real-time.

## Installation
```sh
cd /var/www/flarum/packages
git clone https://github.com/Envel-Nikita-Gutsenkov/gmc-flarum-byobu
cd /var/www/flarum/
sudo composer config repositories.0 path "packages/*"
sudo composer require gmc/byobu *@dev
```
