# Changelog

## [7.0.0](https://github.com/npm/npm-profile/compare/v6.2.1...v7.0.0) (2022-09-30)

### ⚠️ BREAKING CHANGES

* `npm-profile` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

* [`e16befb`](https://github.com/npm/npm-profile/commit/e16befb96a182525432f4023952033f759f8c814) [#68](https://github.com/npm/npm-profile/pull/68) postinstall for dependabot template-oss PR (@lukekarrys)

## [6.2.1](https://github.com/npm/npm-profile/compare/v6.2.0...v6.2.1) (2022-08-02)


### Bug Fixes

* cancel opener promise if web login fails ([#57](https://github.com/npm/npm-profile/issues/57)) ([cdc4acb](https://github.com/npm/npm-profile/commit/cdc4acb81d28924bdc8f5503f2eb2515884b6478))
* remove `npm-use-webauthn` header ([#53](https://github.com/npm/npm-profile/issues/53)) ([b701df2](https://github.com/npm/npm-profile/commit/b701df2630c12de0db555138238eb24a026a438b))

## [6.2.0](https://github.com/npm/npm-profile/compare/v6.1.0...v6.2.0) (2022-07-12)


### Features

* Add export for `webauthCheckLogin` ([#54](https://github.com/npm/npm-profile/issues/54)) ([05a7811](https://github.com/npm/npm-profile/commit/05a78112a4a5c473813cb1f26be346452687899b))

## [6.1.0](https://github.com/npm/npm-profile/compare/v6.0.3...v6.1.0) (2022-06-08)


### Features

* Allow web-login donecheck to cancel opener promise ([#50](https://github.com/npm/npm-profile/issues/50)) ([aa82de0](https://github.com/npm/npm-profile/commit/aa82de07a3c2e5adf90c79d6401dba7b9705da27))
* set 'npm-use-webauthn' header depending on option ([#48](https://github.com/npm/npm-profile/issues/48)) ([6bdd233](https://github.com/npm/npm-profile/commit/6bdd2331b988d981be58953b28ec93a2c3412b58))

### [6.0.3](https://github.com/npm/npm-profile/compare/v6.0.2...v6.0.3) (2022-04-20)


### Dependencies

* update npm-registry-fetch requirement from ^13.0.0 to ^13.0.1 ([#34](https://github.com/npm/npm-profile/issues/34)) ([a444b51](https://github.com/npm/npm-profile/commit/a444b5149653e7cfba2cdbcd8e31bb12d97bc152))

### [6.0.2](https://www.github.com/npm/npm-profile/compare/v6.0.1...v6.0.2) (2022-02-15)


### Dependencies

* bump npm-registry-fetch from 12.0.2 to 13.0.0 ([#28](https://www.github.com/npm/npm-profile/issues/28)) ([7c01310](https://www.github.com/npm/npm-profile/commit/7c0131079fb3ab955b304f34e28374f0c1321565))

### [6.0.1](https://www.github.com/npm/npm-profile/compare/v6.0.0...v6.0.1) (2022-02-14)


### Bug Fixes

* Modify logincouch target ([#27](https://www.github.com/npm/npm-profile/issues/27)) ([1889375](https://www.github.com/npm/npm-profile/commit/1889375c240f85fbb2d38b72c2dda7e5a73bf9f0))


### Dependencies

* update npm-registry-fetch requirement from ^12.0.0 to ^12.0.2 ([82b65f8](https://www.github.com/npm/npm-profile/commit/82b65f8fef07497c116a64f141e275c173cb8cf1))
* use proc-log instead of process.emit ([fe2b8f3](https://www.github.com/npm/npm-profile/commit/fe2b8f3988578661d688415feb4c37dd1aa8b82d))

## [6.0.0](https://www.github.com/npm/npm-profile/compare/v5.0.4...v6.0.0) (2022-01-19)


### ⚠ BREAKING CHANGES

* this drops support for node<=10 and non-LTS versions of node12 and node14

### Features

* move to template-oss ([3f668be](https://www.github.com/npm/npm-profile/commit/3f668be0e12b4752fe87f7410cdb5ae6a97eef70))


### Documentation

* Update README.md ([#14](https://www.github.com/npm/npm-profile/issues/14)) ([531e352](https://www.github.com/npm/npm-profile/commit/531e35262bec5bb8f3611f774bc87cbd42437c3f))


### dependencies

* npm-registry-fetch@12.0.0 ([852b3f0](https://www.github.com/npm/npm-profile/commit/852b3f07b56c9c0a10efacde841d5c6172f87c5c))
