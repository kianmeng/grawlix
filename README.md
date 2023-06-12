# grawlix
![GitHub release](https://img.shields.io/github/v/release/jo1gi/grawlix)
![GitHub top language](https://img.shields.io/github/languages/top/jo1gi/grawlix)
![License](https://img.shields.io/github/license/jo1gi/grawlix)
[![Donate using Ko-Fi](https://img.shields.io/badge/donate-kofi-00b9fe?logo=ko-fi&logoColor=00b9fe)](https://ko-fi.com/jo1gi)

CLI ebook downloader

## Supported services
grawlix currently supports downloading from the following sources:
- [eReolen](https://ereolen.dk)
- [Flipp](https://flipp.dk)
- [Internet Archive](https://archive.org)
- [Manga Plus](https://mangaplus.shueisha.co.jp)
- [Nextory](https://nextory.com)
- [Royal Road](https://www.royalroad.com)
- [Saxo](https://saxo.com)
- [Webtoons](https://webtoons.com)

## Installation
```shell
git clone https://github.com/jo1gi/grawlix.git
cd grawlix
python3 setup.py install
```

## Authentication
Some sources require authentication, which can be done either with cli arguments
or a config file.

**Cli example**
```shell
grawlix --username "user@example.com" --password "SuperSecretPassword" <url>
```

**Config file example**
```toml
[sources.name]
username = "user@example.com"
password = "SuperSecretPassword"
```

## Download books
To download a book run:
```shell
grawlix [options] <book url>
```
