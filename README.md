# GitHub

Sign in to PeltyCMS with GitHub

Official **single sign-on** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `sso-github`.

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **GitHub**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **GitHub** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-github) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your GitHub credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use GitHub automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid GitHub API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to GitHub

## Get it

[GitHub on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-github)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/sso-github
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
