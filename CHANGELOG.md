<a name="0.10.3"></a>
## [0.10.3](https://github.com/stephanebachelier/superapi-cache/compare/0.10.3...v0.10.3) (2016-05-17)


### Bug Fixes

* **cache:** do not process HEAD requests ([1d41e98](https://github.com/stephanebachelier/superapi-cache/commit/1d41e98))



<a name="0.10.2"></a>
## [0.10.2](https://github.com/stephanebachelier/superapi-cache/compare/0.10.2...v0.10.2) (2016-05-13)


### Bug Fixes

* **cache:** remove cache entry for non HEAD or GET request ([08b0c2e](https://github.com/stephanebachelier/superapi-cache/commit/08b0c2e))



<a name="0.10.1"></a>
## [0.10.1](https://github.com/stephanebachelier/superapi-cache/compare/0.10.1...v0.10.1) (2016-05-13)


### Bug Fixes

* **cache:** avoid remove item from cache when using HEAD request ([4017289](https://github.com/stephanebachelier/superapi-cache/commit/4017289))



<a name="0.10.0"></a>
# [0.10.0](https://github.com/stephanebachelier/superapi-cache/compare/0.10.0...v0.10.0) (2016-04-25)




<a name="0.9.0"></a>
# [0.9.0](https://github.com/stephanebachelier/superapi-cache/compare/0.9.0...v0.9.0) (2016-04-25)


### Bug Fixes

* **cache:** return promise to not break promise chain ([2724ee7](https://github.com/stephanebachelier/superapi-cache/commit/2724ee7))

### Features

* **cache:** add flag to choose cache strategy if stale ([d228174](https://github.com/stephanebachelier/superapi-cache/commit/d228174))



<a name="0.8.0"></a>
# [0.8.0](https://github.com/stephanebachelier/superapi-cache/compare/0.8.0...v0.8.0) (2016-04-05)


### Features

* **exclude:** regroup all exclusion logic ([3184b20](https://github.com/stephanebachelier/superapi-cache/commit/3184b20))



<a name="0.7.1"></a>
## [0.7.1](https://github.com/stephanebachelier/superapi-cache/compare/0.7.1...v0.7.1) (2016-03-16)


### Features

* **cache:** exclude all non 2xx response from being cached ([0924943](https://github.com/stephanebachelier/superapi-cache/commit/0924943))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/stephanebachelier/superapi-cache/compare/0.7.0...v0.7.0) (2016-03-10)




<a name="0.6.3"></a>
## [0.6.3](https://github.com/stephanebachelier/superapi-cache/compare/0.6.3...v0.6.3) (2016-03-07)


### Bug Fixes

* **e2e:** fix hit cache test ([d58cd9d](https://github.com/stephanebachelier/superapi-cache/commit/d58cd9d))
* **helper:** add missing xhr field ([6f0eb8e](https://github.com/stephanebachelier/superapi-cache/commit/6f0eb8e))
* **helper:** assign result to variable ([5f67e3b](https://github.com/stephanebachelier/superapi-cache/commit/5f67e3b))
* **hydrate:** remove applied default value ([96d7b53](https://github.com/stephanebachelier/superapi-cache/commit/96d7b53))

### Features

* **exclude:** reorganize exclude option ([c4cd458](https://github.com/stephanebachelier/superapi-cache/commit/c4cd458))
* **hydrate:** use empty string as default value ([3c9f0ac](https://github.com/stephanebachelier/superapi-cache/commit/3c9f0ac))
* **readCache:** add test for stale value ([2bec9e7](https://github.com/stephanebachelier/superapi-cache/commit/2bec9e7))



<a name="0.6.2"></a>
## [0.6.2](https://github.com/stephanebachelier/superapi-cache/compare/0.6.2...v0.6.2) (2016-02-22)


### Bug Fixes

* **hydrate:** revert to reading from cached response part ([3a10d8d](https://github.com/stephanebachelier/superapi-cache/commit/3a10d8d))



<a name="0.6.1"></a>
## [0.6.1](https://github.com/stephanebachelier/superapi-cache/compare/0.6.1...v0.6.1) (2016-02-22)


### Features

* **cache:** add support for path exclusion ([bafe512](https://github.com/stephanebachelier/superapi-cache/commit/bafe512))
* **store:** default to memory store ([f7f4d58](https://github.com/stephanebachelier/superapi-cache/commit/f7f4d58))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/stephanebachelier/superapi-cache/compare/0.6.0...v0.6.0) (2016-02-19)


### Features

* **cache:** cleanup cache entry if stale ([8129677](https://github.com/stephanebachelier/superapi-cache/commit/8129677))



<a name="0.5.3"></a>
## [0.5.3](https://github.com/stephanebachelier/superapi-cache/compare/0.5.3...v0.5.3) (2016-02-19)


### Features

* **cache:** add support for expiration ([9809510](https://github.com/stephanebachelier/superapi-cache/commit/9809510))



<a name="0.5.2"></a>
## [0.5.2](https://github.com/stephanebachelier/superapi-cache/compare/0.5.2...v0.5.2) (2016-02-19)


### Features

* **cache:** delete cache for any non get request ([54bccb7](https://github.com/stephanebachelier/superapi-cache/commit/54bccb7))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/stephanebachelier/superapi-cache/compare/0.5.1...v0.5.1) (2016-02-19)


### Features

* **cache:** bypass middleware in case request has a query ([4492c05](https://github.com/stephanebachelier/superapi-cache/commit/4492c05))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/stephanebachelier/superapi-cache/compare/0.5.0...v0.5.0) (2016-02-11)


### Bug Fixes

* **cache:** fix runtime error when no service ([33bda03](https://github.com/stephanebachelier/superapi-cache/commit/33bda03))



<a name="0.5.0"></a>
# 0.5.0 (2016-02-11)


### Bug Fixes

* **cache:** fix agent response override on cache hit ([4822a49](https://github.com/stephanebachelier/superapi-cache/commit/4822a49))
* **hydrate:** support headers serialization from string ([6f3085d](https://github.com/stephanebachelier/superapi-cache/commit/6f3085d))
* **hydration:** do not assume JSON data ([0d97a3a](https://github.com/stephanebachelier/superapi-cache/commit/0d97a3a))
* **middleware:** fix variables shadowing issue ([45dd709](https://github.com/stephanebachelier/superapi-cache/commit/45dd709))
* **serialise:** fix to use response xhr ([e0ceafb](https://github.com/stephanebachelier/superapi-cache/commit/e0ceafb))
* **test:** switch to blue-tape to avoid non ending test ([0fc9d62](https://github.com/stephanebachelier/superapi-cache/commit/0fc9d62))

### Features

* **cache:** add configuration ([cce19ae](https://github.com/stephanebachelier/superapi-cache/commit/cce19ae))
* **cache:** add overridable function to define the cache key ([189ec0e](https://github.com/stephanebachelier/superapi-cache/commit/189ec0e))
* **cache:** add read operation from cache ([c0744af](https://github.com/stephanebachelier/superapi-cache/commit/c0744af))
* **cache:** add response serialization ([1a457d1](https://github.com/stephanebachelier/superapi-cache/commit/1a457d1))
* **cache:** cache response from network ([72a4c97](https://github.com/stephanebachelier/superapi-cache/commit/72a4c97))
* **cache:** caching function is now a separate configuration ([267a9d4](https://github.com/stephanebachelier/superapi-cache/commit/267a9d4))
* **cache:** inject caching handler ([3b77567](https://github.com/stephanebachelier/superapi-cache/commit/3b77567))
* **cache:** intercept the cache error to trigger a network fetch ([1e2db42](https://github.com/stephanebachelier/superapi-cache/commit/1e2db42))
* **cache:** return value from cache if it exists ([a202ddc](https://github.com/stephanebachelier/superapi-cache/commit/a202ddc))
* **cache:** stop cache handling on cache miss ([644cb09](https://github.com/stephanebachelier/superapi-cache/commit/644cb09))
* **example:** add simple example ([9c42154](https://github.com/stephanebachelier/superapi-cache/commit/9c42154))
* **hydrate:** add logic to build response from cache ([4adad10](https://github.com/stephanebachelier/superapi-cache/commit/4adad10))
* **hydrate:** parse JSON-based cache value ([8386519](https://github.com/stephanebachelier/superapi-cache/commit/8386519))
* **hydrate:** throw error on empty cache ([c9c5f5a](https://github.com/stephanebachelier/superapi-cache/commit/c9c5f5a))
* **log:** add configurable log about cache hit/miss ([54b7a1f](https://github.com/stephanebachelier/superapi-cache/commit/54b7a1f))
* **memory:** migrate store to promise ([5794e33](https://github.com/stephanebachelier/superapi-cache/commit/5794e33))
* **middleware:** export default cache read function ([798ce92](https://github.com/stephanebachelier/superapi-cache/commit/798ce92))
* **response:** add logic to build response from serialized response ([8015708](https://github.com/stephanebachelier/superapi-cache/commit/8015708))
* **store:** add memory store ([118d462](https://github.com/stephanebachelier/superapi-cache/commit/118d462))


### BREAKING CHANGES

* cache: caching function should be a function not related to the store



<a name="0.0.0"></a>
# 0.0.0 (2016-02-11)


### Bug Fixes

* **cache:** fix agent response override on cache hit ([4822a49](https://github.com/stephanebachelier/superapi-cache/commit/4822a49))
* **hydrate:** support headers serialization from string ([6f3085d](https://github.com/stephanebachelier/superapi-cache/commit/6f3085d))
* **hydration:** do not assume JSON data ([0d97a3a](https://github.com/stephanebachelier/superapi-cache/commit/0d97a3a))
* **middleware:** fix variables shadowing issue ([45dd709](https://github.com/stephanebachelier/superapi-cache/commit/45dd709))
* **serialise:** fix to use response xhr ([e0ceafb](https://github.com/stephanebachelier/superapi-cache/commit/e0ceafb))
* **test:** switch to blue-tape to avoid non ending test ([0fc9d62](https://github.com/stephanebachelier/superapi-cache/commit/0fc9d62))

### Features

* **cache:** add configuration ([cce19ae](https://github.com/stephanebachelier/superapi-cache/commit/cce19ae))
* **cache:** add overridable function to define the cache key ([189ec0e](https://github.com/stephanebachelier/superapi-cache/commit/189ec0e))
* **cache:** add read operation from cache ([c0744af](https://github.com/stephanebachelier/superapi-cache/commit/c0744af))
* **cache:** add response serialization ([1a457d1](https://github.com/stephanebachelier/superapi-cache/commit/1a457d1))
* **cache:** cache response from network ([72a4c97](https://github.com/stephanebachelier/superapi-cache/commit/72a4c97))
* **cache:** caching function is now a separate configuration ([267a9d4](https://github.com/stephanebachelier/superapi-cache/commit/267a9d4))
* **cache:** inject caching handler ([3b77567](https://github.com/stephanebachelier/superapi-cache/commit/3b77567))
* **cache:** intercept the cache error to trigger a network fetch ([1e2db42](https://github.com/stephanebachelier/superapi-cache/commit/1e2db42))
* **cache:** return value from cache if it exists ([a202ddc](https://github.com/stephanebachelier/superapi-cache/commit/a202ddc))
* **cache:** stop cache handling on cache miss ([644cb09](https://github.com/stephanebachelier/superapi-cache/commit/644cb09))
* **example:** add simple example ([9c42154](https://github.com/stephanebachelier/superapi-cache/commit/9c42154))
* **hydrate:** add logic to build response from cache ([4adad10](https://github.com/stephanebachelier/superapi-cache/commit/4adad10))
* **hydrate:** parse JSON-based cache value ([8386519](https://github.com/stephanebachelier/superapi-cache/commit/8386519))
* **hydrate:** throw error on empty cache ([c9c5f5a](https://github.com/stephanebachelier/superapi-cache/commit/c9c5f5a))
* **log:** add configurable log about cache hit/miss ([54b7a1f](https://github.com/stephanebachelier/superapi-cache/commit/54b7a1f))
* **memory:** migrate store to promise ([5794e33](https://github.com/stephanebachelier/superapi-cache/commit/5794e33))
* **middleware:** export default cache read function ([798ce92](https://github.com/stephanebachelier/superapi-cache/commit/798ce92))
* **response:** add logic to build response from serialized response ([8015708](https://github.com/stephanebachelier/superapi-cache/commit/8015708))
* **store:** add memory store ([118d462](https://github.com/stephanebachelier/superapi-cache/commit/118d462))


### BREAKING CHANGES

* cache: caching function should be a function not related to the store



