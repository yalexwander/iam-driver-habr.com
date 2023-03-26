## Introdution

This is an ItIsAllMail driver for site habr.com.

Supported features:

- fetcher
- poster
- catalog

## Installation:

1) Install ItIsAllMail.
2) Install the driver.

    cd lib/ItIsAllMail/Driver/
    git clone https://github.com/yalexwander/iam-driver-habr.com habr.com

3) Add driver to ItIsAllMail `conf/config.yml`:

```
drivers :
  - "habr.com"
```

2) Add source in `conf/sources.yml`:

```
- url: https://habr.com/ru/post/723286/
  mailbox_base_dir: /tmp
  mailbox: mailbox_habr
```
