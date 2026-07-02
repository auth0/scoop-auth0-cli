[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/auth0/scoop-auth0-cli)

# Auth0 CLI Scoop App Manifest

This repository contains the Scoop app manifest to install the [Auth0 CLI](https://github.com/auth0/auth0-cli).

### Installation

First, add the bucket:

```sh
$ scoop bucket add auth0 https://github.com/auth0/scoop-auth0-cli.git
```

#### Stable

Install the latest stable release:

```sh
$ scoop install auth0
```

#### Beta

A beta track is also available for previewing new features before they land in the stable release. Beta builds are pre-release and may be unstable — do not use them against production tenants.

```sh
$ scoop install auth0-beta
```

Both tracks provide the `auth0` command, so install one or the other — not both at the same time. To switch from stable to beta, uninstall first:

```sh
$ scoop uninstall auth0
$ scoop install auth0-beta
```

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://auth0.com/docs/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional [username/password databases](https://auth0.com/docs/connections/database/custom-db).
* Add support for [linking different user accounts](https://auth0.com/docs/link-accounts) with the same user.
* Support for generating signed [JSON Web Tokens](https://auth0.com/docs/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when, and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://auth0.com/docs/rules/current).

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](https://auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.