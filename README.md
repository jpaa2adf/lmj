[![Build Status](https://travis-ci.org/rkatic/p.png?branch=master)](https://travis-ci.org/rkatic/p)

<a href="http://promises-aplus.github.com/promises-spec">
    <img src="http://promises-aplus.github.com/promises-spec/assets/logo-small.png"
         alt="Promises/A+ logo" title="Promises/A+ 1.0 compliant" />
</a>

#P

A simple Promises/A+ library.

- Implements a subset of the the [Q](https://github.com/kriskowal/q) API.
- Passing the [Promises/A+ Compliance Test Suite](https://github.com/promises-aplus/promises-tests).
- Cross-Browser, Node.js and RequireJS ready.
- Supports domains.
- Small.
- Simple.
- [Fast](http://jsperf.com/davy-jones-benchmark/32).

##API

P implements a subset of the [Q](https://github.com/kriskowal/q) API.

- `P(val)`
- `P.reject(reason)`
- `P.defer()`
- `P.all(promises)`
- `P.allSettled(promises)`
- `P.spread(promises, onFulfilled, onRejected)` :new:
- `P.onerror`
- `P.longStackSupport` :new:
- `P.nextTick(callback)`
- `deferred.promise`
- `deferred.resolve(value)`
- `deferred.reject(reason)`
- `promise.then(onFulfilled, onRejected)`
- `promise.done(onFulfilled, onRejected)`
- `promise.fin(callback)` :new:
- `promise.spread(onFulfilled, onRejected)`
- `promise.all()`
- `promise.allSettled()`
- `promise.timeout(ms, opt_timeoutMsg)`
- `promise.delay(ms)`
- `promise.inspect()`
- `promise.promised(aFunction)`
- `promise.nodeify(nodeback)` :new:
- `promise.denodeify(aFunction)` :new:
