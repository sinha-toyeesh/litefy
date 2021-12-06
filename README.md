<img src="src/assets/logo.png" alt="drawing" width="200"/>

![GitHub language count](https://img.shields.io/github/languages/count/mathkruger/litefy)
[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[![Open Source Helpers](https://www.codetriage.com/mathkruger/litefy/badges/users.svg)](https://www.codetriage.com/mathkruger/litefy)

# Litefy

A lightweight Spotify client for low-end smartphones (KaiOS included [not yet]) and computers.
The project is being designed with Angular 10, using the [Spotify API](https://developer.spotify.com/documentation/web-api/reference-beta/) and [Web Playback SDK](https://developer.spotify.com/documentation/web-playback-sdk/quick-start/).

## Development server

Run `npm install` && `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### If you run into problems like "ERR_OSSL_EVP_UNSUPPORTED" error when using the ng serve or the ng build command, try using an older version of node (< 17) as this could be due an application or a module we’re using is attempting to use an algorithm or key size which is no longer allowed by default with OpenSSL 3.0, after the new update.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Contribute

If you wanna contribute with this project, just fork it, create a new branch with your modification and submit a pull request.
