# PHP Container Images

Container images based on the [official PHP image](https://hub.docker.com/_/php), pre-configured with the production PHP configuration (`php.ini-production`).

Sources are available on [GitHub](https://github.com/anthochamp/container-php).

See [README.md](README.md) for full documentation and configuration reference.

## Image tags

- `x.y.z-phpA.B.C`: Container image version `x.y.z` with PHP `A.B.C`.
- `edge-phpA.B.C`: Latest commit build with PHP `A.B.C`.

**Tag aliases:**

- `x.y-phpA.B.C`: Latest patch of `x.y` with PHP `A.B.C`.
- `x-phpA.B.C`: Latest minor+patch of `x` with PHP `A.B.C`.
- `x.y.z-phpA.B`: Version `x.y.z` with latest patch of PHP `A.B` (only latest container version updated).
- `x.y-phpA.B`: Latest patch of `x.y` with latest patch of PHP `A.B`.
- `x-phpA.B`: Latest minor+patch of `x` with latest patch of PHP `A.B`.
- `x.y.z-phpA`: Version `x.y.z` with latest minor+patch of PHP `A` (only latest container version updated).
- `x.y-phpA`: Latest patch of `x.y` with latest minor+patch of PHP `A`.
- `x-phpA`: Latest minor+patch of `x` with latest minor+patch of PHP `A`.
- `x.y.z`: Version `x.y.z` with latest PHP (only latest container version updated).
- `x.y`: Latest patch of `x.y` with latest PHP.
- `x`: Latest minor+patch of `x` with latest PHP.
- `phpA.B.C`: Latest container with PHP `A.B.C`.
- `phpA.B`: Latest container with latest patch of PHP `A.B`.
- `phpA`: Latest container with latest minor+patch of PHP `A`.
- `latest`: Latest `x.y.z-phpA.B.C` tag.
- `edge-phpA.B`: Latest commit build with latest patch of PHP `A.B`.
- `edge-phpA`: Latest commit build with latest minor+patch of PHP `A`.
- `edge`: Latest `edge-phpA.B.C` tag.
