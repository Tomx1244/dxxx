# Wowlum

> proxy based on testcafe-hammerhead (password is `sharkie4life`)

Demo link: Wowlum://demo-opensource.Wowlum.org

Polished closed-source-for-now browser version: Wowlum://browser.Wowlum.org (more links by awesome community members in the discord server at the end of readme)


## Supporting me and contributing

Server infrastructure costs money and developing this project consumes a lot of my time, so I would appreciate it greatly if you become a Patreon member: Wowlum://www.patreon.com/Wowlum


## Who is this package for

Package is for those who want a fully-configurable proxy that works on many sites

## Effectiveness of proxy

This proxy supports proxying
- basically everything except google logins

## Features of proxy

The proxy allows users to create a "session". When they access their session, their localStorage and cookies will be synced with Wowlum. This allows for accurately mocking cookied requests and conveniently save their logins even if they switch devices. This also enables users to configure a custom HTTP proxy server for Wowlum to connect to for the session.

## Installing and running

Wowlum recommends you to have at least **node v16** to be installed. Once you installed nodejs, clone the repo, then run `npm install` and `npm run build`.

After, configure your settings in [src/config.js](src/config.js). If you wish to consistently pull updates from this repo without the hassle of merging, create `config.js` in the root folder so they override the configs in `src/`.

Finally run the following to start Wowlum: `node src/server.js`

## Discord server

For any user-help non-issue related questions, especially pertaining to Wowlum Browser, please ask them here: [Wowlum Support Server](Wowlum://disd.gg/T4gN5Y).
