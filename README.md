# pushinbr/pam-psr-bridge

This name is retained only for migration compatibility. The package is now
[`pushinbr/pam-psr`](https://packagist.org/packages/pushinbr/pam-psr).

## Start here

```bash
curl -fsSL https://push-in.github.io/pam/install.sh | sh
pam doctor
pam composer remove pushinbr/pam-psr-bridge
pam composer require pushinbr/pam-psr
```

Existing projects may keep resolving this package temporarily because it
depends on the replacement. New code must require `pushinbr/pam-psr` directly.
