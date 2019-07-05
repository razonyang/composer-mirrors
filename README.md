Composer Mirrors
----------------

I believe that there are a lot of PHP developers like me, who located in some special locations, 
have complained about why [Packagist](https://packagist.org/) is so slow.
Because Packagist can not host in every country and given bandwidth/latency constraint in certain areas of the world, 
so that is why this repository exists.
It aims to collect available composer/packagist mirrors all around the world.

## Contribution

Any feedbacks/PRs are welcome, you can [file an issue](https://github.com/razonyang/composer-mirrors/issues/new) or create a PR for:

- Add new mirror.
- Remove unavailable mirror.
- ...

## Configuration

Configurate mirror:

```shell
$ composer config -g repo.packagist composer [mirror]
```

> You should remove `-g` if you don't want to configurate mirror globally.

Remove mirror:

```shell
$ composer config -g --unset repos.packagist
```

## Mirrors list

### Africa

#### South Africa

- [packagist.co.za](https://packagist.co.za)

### Asia

#### China

- [阿里云镜像](https://developer.aliyun.com/composer) - https://mirrors.aliyun.com/composer
- [华为云镜像](https://mirrors.huaweicloud.com) - https://mirrors.huaweicloud.com/repository/php
- [pkg.phpcomposer.com](https://pkg.phpcomposer.com) - https://packagist.phpcomposer.com

#### Indonesia

- [packagist.phpindonesia.id](https://packagist.phpindonesia.id)

#### Japan

- [packagist.jp](https://packagist.jp)

### South America

#### Brazil

- [packagist.com.br](https://packagist.com.br)
