# PHP Container

![GitHub License](https://img.shields.io/github/license/anthochamp/container-php?style=for-the-badge)
![GitHub Release](https://img.shields.io/github/v/release/anthochamp/container-php?style=for-the-badge&color=457EC4)
![GitHub Release Date](https://img.shields.io/github/release-date/anthochamp/container-php?style=for-the-badge&display_date=published_at&color=457EC4)

Container images based on the [official PHP image](https://hub.docker.com/_/php), pre-configured with the production PHP configuration (`php.ini-production`).

## How to use this image

```shell
docker run -p 80:80 -v ./app:/var/www/html anthochamp/php:latest-apache
```

## Details

This image differs from the official PHP image in one way: `php.ini-production` is activated instead of `php.ini-development`. This makes it suitable for production use without any additional configuration.

All environment variables from the official PHP image are supported. Refer to the [official PHP Docker image documentation](https://hub.docker.com/_/php) for details.

## References

- [Official PHP Docker Hub image](https://hub.docker.com/_/php)
- [PHP configuration documentation](https://www.php.net/manual/en/configuration.php)
