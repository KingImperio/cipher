# Cipher

A secure password generator with strength analysis, batch generation, and clipboard management.

## What it does

Cipher generates cryptographically secure passwords using crypto.getRandomValues(). It features a 4-segment strength meter that analyzes length, character variety, dictionary patterns, and predictable sequences. Users can generate up to 10 passwords at once, customize character sets, exclude ambiguous characters, and copy individual or all passwords to clipboard. Built for anyone who needs strong, customizable passwords without cloud storage or accounts.

## Tech

- HTML / CSS / JavaScript (Vanilla)
- Satoshi font from Fontshare CDN
- JetBrains Mono from Google Fonts for password display
- Web Crypto API for secure randomness

## Run locally

Download or clone the repo. Open index.html in a browser. No build step required.

## Live demo
https://kingimperio.github.io/cipher/

## Part of

Built as part of a frontend portfolio series. Component styling draws from [black.ui](https://github.com/KingImperio/black.ui).
