[![https://telrgram.me/umbrellacopy](https://img.shields.io/badge/👥_Umbrella-Copy-blue.svg)](https://telrgram.me/umbrellacopy)

An Other Project Of Umbrella Copy

save bot

id bot : @saverobot

Installation
------------
In botbase.lua set your token in field *bot_api_key* and set your id as sudo in field *bot_sudo*
```bash
sudo apt-get install lua5.2 liblua5.2-dev
git clone https://github.com/keplerproject/luarocks.git
cd luarocks
./configure
make build && make install
sudo luarocks install luasocket
sudo luarocks install luasec
sudo luarocks install redis-lua
sudo luarocks install fakeredis
sudo luarocks install serpent
cd ..
git clone https://github.com/umbrellacopy/saverobot.git
cd saverobot
sudo chmod 777 launch.sh
./launch.sh
```
