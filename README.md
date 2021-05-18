Multipart-async
=========

**NOTE**: pre-alpha software, mostly untested and still in development. Early feedback is welcome, but use at your own risk.

Futures-based client- and server-side abstractions for HTTP file uploads (POST requests with  `Content-Type: multipart/form-data`).

Preliminary support for Hyper 0.13 and async/await; 
requires 1.39 to build (nightly-2019-08-15, will be released to beta on 2019-09-26).

Update
-------

Fault tolerance if an additional header doesn't parse correctly https://github.com/eschudt/multipart-async/blob/master/src/server/field/headers.rs#L254

License
-------

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.
