# Sormagec MongoDB Cacheable

**Sormagec MongoDB Cacheable** is a granular, intuitive, and fluent caching system for eloquent models. Simple, but yet powerful, plug-n-play with no hassle.


What this package do -technically- caching eloquent query passing through the `get` method, whatever it is and it's smart enough to indicated any conditions, limit, offset, wheres, orders, groups, ..etc and take that criteria into account when caching and checking for cached version. Also by default any create, update, or delete event will flush all cache for that specific model. It uses default Laravel caching system, and utilizes whatever cache driver you are using. Awesome, right?


## Installation & Usage

1. Install the package via composer:
    ```shell
    composer require sormagec/laravel-cacheable
    ```

2. Use the `\Sormagec\Cacheable\CacheableEloquent` in your desired model, and you're done!

3. Seriously, that's it!

Check the [`CacheableEloquent`](src/CacheableEloquent.php) source code for more awesome stuff if you need advanced control.


## Optional Features

You can optionally override model caching behaviour per model as follows:

```php
    /**
     * Indicate if the model cache clear is enabled.
     *
     * @var bool
     */
    protected $cacheClearEnabled = true;

    /**
     * The model cache driver.
     *
     * @var string
     */
    protected $cacheDriver = 'memcached';

    /**
     * The model cache lifetime.
     *
     * @var int
     */
    protected $cacheLifetime = -1;
```

## License

This software is released under [The MIT License (MIT)](LICENSE).

(c) 2016-2019 Rinvex LLC, Some rights reserved.
