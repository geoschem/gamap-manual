# Security Policy

This repository contains only the static HTML, CSS, JavaScript, and image files for the archived [GAMAP manual pages](https://geoschem.github.io/gamap-manual). It has no server-side code, database, user accounts, or authentication, and it does not contain the GAMAP source code. Relevant concerns here are mainly things like cross-site scripting opportunities in page content or in `doc/expanding_menu.js`, outbound links to expired domains that could be taken over by a third party, or credentials committed by mistake.

## Supported Versions

There is only one deployed version of these pages, served from the `main` branch by GitHub Pages. Security fixes are applied there; there are no older versions to maintain. GAMAP itself is no longer actively maintained, so vulnerabilities in the GAMAP IDL code are out of scope.

## Reporting a Vulnerability

Please **do not** open a public GitHub issue for a suspected security vulnerability.

Instead, report it privately using [the GitHub private security advisories form](https://github.com/geoschem/gamap-manual/security/advisories/new) for this repository. We will acknowledge your report and work to address confirmed issues.

For non-security problems with these pages, such as broken links, see [SUPPORT.md](SUPPORT.md) instead.
