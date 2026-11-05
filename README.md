# GitHub

Sign in to PeltyCMS with GitHub

Official single sign-on for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **GitHub**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **GitHub** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-github) inside Pelty Admin → Addons.
2. Open Pelty Admin → Authentication, create a GitHub app, paste client id/secret, and enable the SSO button.
3. Customers hit checkout / login / order flow as usual — GitHub runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working GitHub credentials
- Outbound HTTPS from your panel

## Get it

**[GitHub on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-github)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
