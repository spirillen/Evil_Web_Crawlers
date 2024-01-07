A little repo for listing evil cooperative crawlers to add into Nginx $http_user_agent returning 444

Let's start learning some real C++

## Steps
1. Learn to read-in `.yml`
2. Learn to convert yaml to json
3. Output the yam to `.json` file
4. Output to `.conf` files to be included in nginx as snippets

Bot Crawler source

- `https://github.com/matomo-org/device-detector/blob/master/regexes/bots.yml`

Collection line:

```shell
sudo grep -i "bot" /var/log/nginx/access.log | grep -vE "AhrefsBot|Rogerbot|DotBot|YandexBot|Googlebot|Facebot Twitterbot"
```
