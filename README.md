# hyper-rustls
This is an integration between the [rustls TLS stack](https://github.com/ctz/rustls)
and the [hyper HTTP library](https://github.com/hyperium/hyper).

[![Build Status](https://travis-ci.org/ctz/hyper-rustls.svg?branch=master)](https://travis-ci.org/ctz/hyper-rustls)
[![Build Status](https://dev.azure.com/ctz99/ctz/_apis/build/status/ctz.hyper-rustls?branchName=master)](https://dev.azure.com/ctz99/ctz/_build/latest?definitionId=4&branchName=master)
[![Crate](https://img.shields.io/crates/v/hyper-rustls.svg)](https://crates.io/crates/hyper-rustls)

[API Documentation](https://docs.rs/hyper-rustls/)

By default clients verify certificates using the `rustls-native-certs` crate, which uses
the platform's root CAs.

# Release history
- Next release (0.19.0):
  * First release with async/await support
  * Alphas are available: https://crates.io/crates/hyper-rustls/0.19.0-alpha.3
- 0.18.0 (2019-11-23)
  * Uses [rustls-native-certs](https://crates.io/crates/rustls-native-certs)
    instead of compiled-in root certificates.
- 0.17.1 (2019-08-19)
  * Fix accidental use of sync read/write.
- 0.17.0 (2019-08-11)
  * Update dependencies.

# License
hyper-rustls is distributed under the following three licenses:

- Apache License version 2.0.
- MIT license.
- ISC license.

These are included as LICENSE-APACHE, LICENSE-MIT and LICENSE-ISC
respectively.  You may use this software under the terms of any
of these licenses, at your option.

