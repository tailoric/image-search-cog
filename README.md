# image-search-cog
A discord bot cog using different reverse image search sites using the [discord.py](https://github.com/Rapptz/discord.py) commands extension.

## Uses following services:

* [IQDB](http://iqdb.org/)
* [SauceNAO](http://saucenao.com/)
* [TinEye](https://tineye.com/)

## IQDB uses danbooru API

This means that to use the `iqdb` command, a valid Danbooru username and API key is needed.
those should be put into a json file with the following structure:

```json
{
  "user": "Username",
  "api_key": "ValidAPIKey"
}
```

## Requirements

`discord.py` discord API wrapper  
`aiohttp` library  
`bs4` library `BeautifulSoup` more specifically  

