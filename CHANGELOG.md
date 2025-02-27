# Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.1.4](https://github.com/bjerkio/oidc-react/compare/v1.1.3...v1.1.4) (2020-12-19)


### Bug Fixes

* Including 'Log' in export ([#383](https://github.com/bjerkio/oidc-react/issues/383)) ([1f10c07](https://github.com/bjerkio/oidc-react/commit/1f10c075f90dcf0e2abb3d48ea768c38164f2f74))

## [1.1.3](https://github.com/bjerkio/oidc-react/compare/v1.1.2...v1.1.3) (2020-10-24)


### Bug Fixes

* Remove react-router 🤷 ([527bcd3](https://github.com/bjerkio/oidc-react/commit/527bcd3a9d07fd3097924d022b13d31afb7d2dcf))

## [1.1.2](https://github.com/bjerkio/oidc-react/compare/v1.1.1...v1.1.2) (2020-10-24)


### Bug Fixes

* Move react, react-dom to peerDependencies ([b4fd437](https://github.com/bjerkio/oidc-react/commit/b4fd437dfb81248766cb5be59b2bd684e95dcf7e)), closes [#301](https://github.com/bjerkio/oidc-react/issues/301)

## [1.1.1](https://github.com/bjerkio/oidc-react/compare/v1.1.0...v1.1.1) (2020-10-09)


### Bug Fixes

* change callback method to allow other sign in method ([c497f49](https://github.com/bjerkio/oidc-react/commit/c497f49ddbca100ff5f52419ce07ac64c00d2656))

# [1.1.0](https://github.com/bjerkio/oidc-react/compare/v1.0.1...v1.1.0) (2020-09-26)


### Features

* add auto silent renew option ([6bb2df5](https://github.com/bjerkio/oidc-react/commit/6bb2df5e1c7c8b9f12fc220bcd51c1eac4890fe4))

## [1.0.1](https://github.com/bjerkio/oidc-react/compare/v1.0.0...v1.0.1) (2020-08-21)


### Bug Fixes

* this._signinStart is not a function ([20b1e57](https://github.com/bjerkio/oidc-react/commit/20b1e57b1b8a15276a04498081560ccce03e0c73)), closes [#173](https://github.com/bjerkio/oidc-react/issues/173)

# 1.0.0 (2020-08-20)


### Bug Fixes

* Autosignin on expired user ([d5dce04](https://github.com/bjerkio/oidc-react/commit/d5dce04f51bdfcff49ab622f60875aedfe17fdb5))
* Fix withAuth export ([4e0e2e1](https://github.com/bjerkio/oidc-react/commit/4e0e2e11675eda83fc543779d53f51f2ff96284e))
* Package size and target ([b9c8205](https://github.com/bjerkio/oidc-react/commit/b9c820524cd34f030d823af867df3d51ad2d2bd7))
* Useless conditional ([6cf9dda](https://github.com/bjerkio/oidc-react/commit/6cf9ddad48728b50c4f17ce7ade18f67ee1faccf))
* Variable 'user' cannot be of type null ([0d8a0c3](https://github.com/bjerkio/oidc-react/commit/0d8a0c3110aec43b4e8c22b6385df8fcbd64147d))


### Code Refactoring

* Improve createContext setup ([6b715f5](https://github.com/bjerkio/oidc-react/commit/6b715f5ad8f78fdb1306cfc399b5f26a2bdc5a14))


### Features

* add client_secret ([151a494](https://github.com/bjerkio/oidc-react/commit/151a494a0faf48483086ce75435ab033335c54ca))
* Add improved API layout ([1e3d66a](https://github.com/bjerkio/oidc-react/commit/1e3d66a1d336d6f0e6e6310e33b4061e9c50e46a)), closes [#36](https://github.com/bjerkio/oidc-react/issues/36)
* Add onBeforeSignIn hook ([e2f609e](https://github.com/bjerkio/oidc-react/commit/e2f609ef205cc05f4040a6281460ccd2a2441e35))
* add option to use signoutRedirect ([9ca3ada](https://github.com/bjerkio/oidc-react/commit/9ca3ada0e2ef1fdba81397ec2044928cc5844a87))
* add option to use signoutRedirect ([d2c4278](https://github.com/bjerkio/oidc-react/commit/d2c42782edd676ae68ccedf45dde18d696f32447))
* Add responseType and scope properties ([e00454a](https://github.com/bjerkio/oidc-react/commit/e00454a50606d287063a3134cfe3740e2ee360f8))
* Add withAuth higher order component ([9f2cea8](https://github.com/bjerkio/oidc-react/commit/9f2cea8c74476a7e74490cd8ae18e82a832d18e0))
* First implementation ([071d311](https://github.com/bjerkio/oidc-react/commit/071d311b7bd4810648c7a18150e2d98e23328258))
* re-export User and UserManager ([a2fdf39](https://github.com/bjerkio/oidc-react/commit/a2fdf39c88dadfe28e8f605ddfc5825c294a017b))


### BREAKING CHANGES

* Typescript users might not expect the Context to be 'null'. Now you have to check
it.

# [1.0.0-alpha.7](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.6...v1.0.0-alpha.7) (2020-05-15)


### Bug Fixes

* Useless conditional ([6cf9dda](https://github.com/bjerkio/oidc-react/commit/6cf9ddad48728b50c4f17ce7ade18f67ee1faccf))
* Variable 'user' cannot be of type null ([0d8a0c3](https://github.com/bjerkio/oidc-react/commit/0d8a0c3110aec43b4e8c22b6385df8fcbd64147d))


### Code Refactoring

* Improve createContext setup ([6b715f5](https://github.com/bjerkio/oidc-react/commit/6b715f5ad8f78fdb1306cfc399b5f26a2bdc5a14))


### Features

* Add improved API layout ([1e3d66a](https://github.com/bjerkio/oidc-react/commit/1e3d66a1d336d6f0e6e6310e33b4061e9c50e46a)), closes [#36](https://github.com/bjerkio/oidc-react/issues/36)
* add option to use signoutRedirect ([d2c4278](https://github.com/bjerkio/oidc-react/commit/d2c42782edd676ae68ccedf45dde18d696f32447))


### BREAKING CHANGES

* Typescript users might not expect the Context to be 'null'. Now you have to check
it.

# [1.0.0-alpha.6](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.5...v1.0.0-alpha.6) (2020-05-15)


### Features

* add option to use signoutRedirect ([9ca3ada](https://github.com/bjerkio/oidc-react/commit/9ca3ada0e2ef1fdba81397ec2044928cc5844a87))

# [1.0.0-alpha.5](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.4...v1.0.0-alpha.5) (2020-04-21)


### Bug Fixes

* Autosignin on expired user ([d5dce04](https://github.com/bjerkio/oidc-react/commit/d5dce04f51bdfcff49ab622f60875aedfe17fdb5))
* Fix withAuth export ([4e0e2e1](https://github.com/bjerkio/oidc-react/commit/4e0e2e11675eda83fc543779d53f51f2ff96284e))

# [1.0.0-alpha.4](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.3...v1.0.0-alpha.4) (2020-04-16)


### Features

* Add onBeforeSignIn hook ([e2f609e](https://github.com/bjerkio/oidc-react/commit/e2f609ef205cc05f4040a6281460ccd2a2441e35))
* Add withAuth higher order component ([9f2cea8](https://github.com/bjerkio/oidc-react/commit/9f2cea8c74476a7e74490cd8ae18e82a832d18e0))

# [1.0.0-alpha.3](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.2...v1.0.0-alpha.3) (2020-04-09)


### Bug Fixes

* Package size and target ([b9c8205](https://github.com/bjerkio/oidc-react/commit/b9c820524cd34f030d823af867df3d51ad2d2bd7))

# [1.0.0-alpha.2](https://github.com/bjerkio/oidc-react/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2020-04-09)


### Features

* Add responseType and scope properties ([e00454a](https://github.com/bjerkio/oidc-react/commit/e00454a50606d287063a3134cfe3740e2ee360f8))

# 1.0.0-alpha.1 (2020-04-09)


### Features

* First implementation ([071d311](https://github.com/bjerkio/oidc-react/commit/071d311b7bd4810648c7a18150e2d98e23328258))
