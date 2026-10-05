<!-- tyhp-readme:start -->
# tyhpdef/symfony-password-hasher

Tyhp type definitions for `symfony/password-hasher` `7.4.8`.

```bash
composer require --dev tyhpdef/symfony-password-hasher:7.4.8
```

This is a metapackage. Composer also installs `tyhpdef/symfony-password-hasher-impl` (type files).
Require **this** name, not `tyhpdef/symfony-password-hasher-impl`.

See https://tyhplang.com.

## Maintain `symfony/password-hasher`? Ship the types yourself

If you are a Packagist maintainer of `symfony/password-hasher`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-password-hasher-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/password-hasher` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-password-hasher": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/password-hasher` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/password-hasher` with a real constraint,
   `"replace": { "tyhpdef/symfony-password-hasher": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/password-hasher` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-password-hasher` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
