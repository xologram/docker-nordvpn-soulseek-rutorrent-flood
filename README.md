# File sharing system

Goal of this is to deploy torrent and soulseek clients that are accessible via web browser.
Both of these are set up to use NordVPN so ISP can't see what are you doing.

Before you deploy this please edit docker-compose.yml and add your NordVPN user and password. 

You can download directly to your normal download folders by adding them to `volumes` section in docker-compose.yml

To access torrent client try:

https://localhost:9443

To access soulseek try:

http://localhost:6080

##### Using Docker Compose
```
docker-compose up -d

