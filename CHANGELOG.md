# Changelog

# [0.10.0](https://github.com/saltstack-formulas/firewalld-formula/compare/v0.9.0...v0.10.0) (2020-04-02)


### Bug Fixes

* **zone.xml:** adjust whitespacing to pass tests & macro at top of file ([d8f0f47](https://github.com/saltstack-formulas/firewalld-formula/commit/d8f0f47a5408bde763050c457269ef129a48b050))


### Features

* allow rich_rules to be specified as a dict ([cd4cec0](https://github.com/saltstack-formulas/firewalld-formula/commit/cd4cec008983943213ac3bb721ab69c3a5214c54))


### Styles

* **zone.xml:** remove all trailing whitespaces ([204efe5](https://github.com/saltstack-formulas/firewalld-formula/commit/204efe5fc7065a2c2f4f55aa0138bf98675cba4e))


### Tests

* **zones_spec:** check content of rendered zone files ([6ebfc6f](https://github.com/saltstack-formulas/firewalld-formula/commit/6ebfc6f20cfd72c2785514ab35484c9575401648))

# [0.9.0](https://github.com/saltstack-formulas/firewalld-formula/compare/v0.8.0...v0.9.0) (2020-02-12)


### Features

* **zone.xml:** allow more services definition inside zone ([8d0172f](https://github.com/saltstack-formulas/firewalld-formula/commit/8d0172f5c7e0e1a2856dbbc0bf149ee8ddfd225a))

# [0.8.0](https://github.com/saltstack-formulas/firewalld-formula/compare/v0.7.0...v0.8.0) (2020-02-12)


### Continuous Integration

* workaround issues with newly introduced `amazonlinux-1` [skip ci] ([ace3433](https://github.com/saltstack-formulas/firewalld-formula/commit/ace343353d2c7b183b424e8a3f08b575417add3f))
* workaround issues with newly introduced `amazonlinux-1` [skip ci] ([b5a95f3](https://github.com/saltstack-formulas/firewalld-formula/commit/b5a95f35ab98b872be852597d046d8d25f06b08b))
* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([908f5df](https://github.com/saltstack-formulas/firewalld-formula/commit/908f5df86cd69f28ef4e48fbde13c35eb003b627))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([0b82e43](https://github.com/saltstack-formulas/firewalld-formula/commit/0b82e43a1507bb748adefd13a0412ef7ccae8eb7))
* **travis:** apply changes from build config validation [skip ci] ([6e1b876](https://github.com/saltstack-formulas/firewalld-formula/commit/6e1b876298c2d782b132c1571d1f20564fb01bf1))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([70dc9aa](https://github.com/saltstack-formulas/firewalld-formula/commit/70dc9aa3b4e299b6f8553132cd9d4401f4635f97))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([97afbb1](https://github.com/saltstack-formulas/firewalld-formula/commit/97afbb157557ec3096cc8a8de48f737960dfda4e))
* **travis:** run `shellcheck` during lint job [skip ci] ([d8bede7](https://github.com/saltstack-formulas/firewalld-formula/commit/d8bede7082130445461f990346f64d4db22e4bd2))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([b96cc56](https://github.com/saltstack-formulas/firewalld-formula/commit/b96cc569fe9a68deb2eb78974c216eb736d3b57b))
* **travis:** use build config validation (beta) [skip ci] ([07e7900](https://github.com/saltstack-formulas/firewalld-formula/commit/07e79001cddc4918f6ace716b15cf0658e09d374))


### Features

* standardize license and hand over to saltstack formulas ([20cb8a6](https://github.com/saltstack-formulas/firewalld-formula/commit/20cb8a60d362a7484892fc6703de954c67fb8763))

# [0.7.0](https://github.com/saltstack-formulas/firewalld-formula/compare/v0.6.2...v0.7.0) (2019-11-09)


### Bug Fixes

* **map.jinja:** fix `salt-lint` errors ([de4e191](https://github.com/saltstack-formulas/firewalld-formula/commit/de4e1915fb17b2278132076c7946539191f1e018))
* **rubocop:** add fixes using `rubocop --safe-auto-correct` ([8136b75](https://github.com/saltstack-formulas/firewalld-formula/commit/8136b75fa0266dc8d849a40a1fdb77129d6da31f))
* **yamllint:** fix all errors ([0f808d6](https://github.com/saltstack-formulas/firewalld-formula/commit/0f808d6afb383c56abfa439fde0fab46374ea2d7))


### Documentation

* **readme:** modify according to standard structure ([3df11fc](https://github.com/saltstack-formulas/firewalld-formula/commit/3df11fc75cade2d801183c3ae110821d2842f53f))
* **readme:** move to `docs/` directory ([d47265f](https://github.com/saltstack-formulas/firewalld-formula/commit/d47265f9743195a96565701e758789fbc14e3084))


### Features

* **semantic-release:** implement for this formula ([c5f114d](https://github.com/saltstack-formulas/firewalld-formula/commit/c5f114d8863f6763c49cc08c723924649c8c1ed3))
