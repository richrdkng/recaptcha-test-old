recaptcha-test
==============

A website to test basic reCAPTCHA functionality with callbacks.

Usage
=====

To handle possible reCAPTCHA events, override one or more of the following:

```javascript
// fired, when the reCAPTCHA is loaded
function onCaptchaLoad() {
    console.log('onCaptchaLoad')
}

// fired, when the user submits a successful reCAPTCHA response
function onCaptchaSuccess(token) {
    console.log('onCaptchaSuccess', token)
}

// fired, when the reCAPTCHA response expires and the user needs to re-verify
function onCaptchaExpired() {
    console.log('onCaptchaExpired')
}

// fired, when the reCAPTCHA encounters an error
function onCaptchaError() {
    console.log('onCaptchaError')
}
```

Contribution
============

**Any contribution is appreciated**. 
Thank you, have fun!

License
=======

[MIT](LICENSE.md) @ [Richard Szakacs](https://www.github.com/richardszkcs)
