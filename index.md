---
layout: home
home_img: /img/logo-text.svg
home_primary_btn:
  name: Get Started
  href: /intro/
home_secondary_btn:
  name: View the Docs
  href: https://api.qunitjs.com
---

<section class="grid grid--small home-highlights">
  <div>
    <h2>Easy</h2>
    <p>Easy, zero configuration setup for any Node.js project and minimal configuration for Browser-based projects.</p>
  </div>

  <div>
    <h2>Universal</h2>
    <p>Tests can be run anywhere; Node, your browser, even inside a Web Worker. Test your code where it runs.</p>
  </div>

  <div>
    <h2>Extensible</h2>
    <p>Flexible APIs for custom assertions, runners, and reporters mean you can extend QUnit to fit your needs.</p>
  </div>
</section>

---

## A Quick Example

```js
const add = (a, b) => a + b;
QUnit.module('add', function() {
  QUnit.test('should add two numbers', function(assert) {
    assert.equal(add(1, 1), 2, '1 + 1 = 2');
  });
});
```

<div class="grid grid--split" markdown="1">

<div class="example-result" markdown="1">

### Browser Result

<iframe loading="lazy" title="The example test code running in the browser" src="/resources/example-add.html"></iframe>

</div>

<div class="example-result" markdown="1">

### CLI Result

```
TAP version 13
ok 1 add > should add two numbers
1..1
# pass 1
# skip 0
# todo 0
# fail 0
```

</div>

</div>

---

## Current Release

<p class="lead lead--center">v2.13.0 (<a href="https://github.com/qunitjs/qunit/blob/2.13.0/History.md">changelog</a>)</p>

These are the officially supported download channels for QUnit releases:

* npm: `npm install --save-dev qunit`
* Yarn: `yarn add --dev qunit`
* Bower: `bower install --save-dev qunit`
* CDN: [`qunit-2.13.0.js`](https://code.jquery.com/qunit/qunit-2.13.0.js) & [`qunit-2.13.0.css`](https://code.jquery.com/qunit/qunit-2.13.0.css)

---

## Join the Community

<p class="lead lead--center" markdown="1">Join us on [Mastodon](https://mastodon.technology/@qunitjs), [Twitter](https://twitter.com/qunitjs), or [Gitter chat](https://gitter.im/qunitjs/qunit).</p>

To contribute:

* [Watch the repository](https://github.com/qunitjs/qunit) to learn about release, new requests, or bug reports.
* The source of this website, is in the [qunitjs.com](https://github.com/qunitjs/qunitjs.com) repository.
* The source of the Documentation site, is in the ["docs/" directory](https://github.com/qunitjs/qunit/tree/master/docs).

---

<p class="cta">What are you waiting for? <a href="{% link intro.md %}" class="button">Get started!</a></p>
