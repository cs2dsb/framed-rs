# Release process

1. Check build locally with `bin/build_local`.
1. Check [Travis build][travis]: [![Build Status](https://travis-ci.org/fluffysquirrels/framed-rs.svg)][travis].
   [travis]: https://travis-ci.org/fluffysquirrels/framed-rs
1. Increment version number in Cargo.toml (major version if breaking changes).
1. Add a git tag for the new version number. Push it to [github][github].
   [github]: https://github.com/fluffysquirrels/framed-rs
1. Publish with `bin/publish`.
1. Check new version appears on
   [![Crate](https://img.shields.io/crates/v/framed.svg)][crates]
   and
   [![Documentation](https://docs.rs/framed/badge.svg)][docs]

   [crates]: https://crates.io/crates/framed
   [docs]: https://docs.rs/framed