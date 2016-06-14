## Soupmix Memcached Cache Adaptor

[![Build Status](https://travis-ci.org/soupmix/cache-memcached.svg?branch=master)](https://travis-ci.org/soupmix/cache-memcached) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/soupmix/cache-memcached/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/soupmix/cache-memcached/?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/f2fd85aaddc44793bfc25020802ee5f2)](https://www.codacy.com/app/mehmet/cache-memcached?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=soupmix/cache-memcached&amp;utm_campaign=Badge_Grade) [![Code Climate](https://codeclimate.com/github/soupmix/cache-memcached/badges/gpa.svg)](https://codeclimate.com/github/soupmix/cache-memcached) 
[![Latest Stable Version](https://poser.pugx.org/soupmix/cache-memcached/v/stable)](https://packagist.org/packages/soupmix/cache-memcached) [![Total Downloads](https://poser.pugx.org/soupmix/cache-memcached/downloads)](https://packagist.org/packages/soupmix/cache-memcached) [![Latest Unstable Version](https://poser.pugx.org/soupmix/cache-memcached/v/unstable)](https://packagist.org/packages/soupmix/cache-memcached) [![License](https://poser.pugx.org/soupmix/cache-memcached/license)](https://packagist.org/packages/soupmix/cache-memcached) [![composer.lock](https://poser.pugx.org/soupmix/cache-memcached/composerlock)](https://packagist.org/packages/soupmix/cache-memcached)


### Installation

It's recommended that you use [Composer](https://getcomposer.org/) to install Soupmix Cache Memcached Adaptor.

```bash
$ composer require soupmix/cache-memcached "~0.1"
```

### Connection
```
require_once '/path/to/composer/vendor/autoload.php';

$config = [];
$config['bucket'] = 'test';
$config['hosts'] = ['127.0.0.1'];
$cache = new Soupmix\Cache\MemcachedCache($config);
```


### Soupmix Memcached Cache API

[See Soupmix Cache API](https://github.com/soupmix/cache-base/blob/master/README.md)
