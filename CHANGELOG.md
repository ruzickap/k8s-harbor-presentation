# Changelog

## [1.1.0](https://github.com/ruzickap/k8s-harbor-presentation/compare/v1.0.3...v1.1.0) (2024-07-02)


### Features

* **gh:** add default GitHub repo files ([#31](https://github.com/ruzickap/k8s-harbor-presentation/issues/31)) ([5734a58](https://github.com/ruzickap/k8s-harbor-presentation/commit/5734a589b62eb73377a4d98f41cca8f3f3e72073))
* **gha:** remove/fix non-working github actions ([#32](https://github.com/ruzickap/k8s-harbor-presentation/issues/32)) ([60bc1fa](https://github.com/ruzickap/k8s-harbor-presentation/commit/60bc1fab63bef39bfd14787cb102d9696dc702d2))
* **gha:** unify GHA - renovate, megalinter, markdown, and others ([#28](https://github.com/ruzickap/k8s-harbor-presentation/issues/28)) ([0608421](https://github.com/ruzickap/k8s-harbor-presentation/commit/0608421b6f5b89a8a9198042bc6e2859e459da92))


### Bug Fixes

* **renovate:** disable autoupdate for git-submodules ([#30](https://github.com/ruzickap/k8s-harbor-presentation/issues/30)) ([ae2c6cc](https://github.com/ruzickap/k8s-harbor-presentation/commit/ae2c6ccc466282d008a9cd02e7fa32a4568e31ee))

## [v1.0.3](https://github.com/ruzickap/k8s-harbor-presentation/compare/v1.0.2...v1.0.3) (2021-12-20)

- Improve GH Action files [`#25`](https://github.com/ruzickap/k8s-harbor-presentation/pull/25)
- Fix linter issues [`#24`](https://github.com/ruzickap/k8s-harbor-presentation/pull/24)
- Upgrade GH Actions versions [`#23`](https://github.com/ruzickap/k8s-harbor-presentation/pull/23)
- Upgrade action-my-broken-link-checker [`#22`](https://github.com/ruzickap/k8s-harbor-presentation/pull/22)
- Fix My Broken Link Checker parameter [`#21`](https://github.com/ruzickap/k8s-harbor-presentation/pull/21)

## [v1.0.2](https://github.com/ruzickap/k8s-harbor-presentation/compare/v1.0.1...v1.0.2) (2020-09-17)

- Add actions/checkout with gh-page to periodic-broken-link-checks.yml [`#19`](https://github.com/ruzickap/k8s-harbor-presentation/pull/19)
- Replace markdown link checker by action-my-markdown-link-checker [`#18`](https://github.com/ruzickap/k8s-harbor-presentation/pull/18)
- Replace markdown linter [`#17`](https://github.com/ruzickap/k8s-harbor-presentation/pull/17)
- Revert "Bump revealjs from `00b0ace` to `5e49cbd`" [`#13`](https://github.com/ruzickap/k8s-harbor-presentation/pull/13)

## [v1.0.1](https://github.com/ruzickap/k8s-harbor-presentation/compare/v1.0.0...v1.0.1) (2020-05-11)

- Ignore CHANGELOG.md when doing markdown checks [`876f3b8`](https://github.com/ruzickap/k8s-harbor-presentation/commit/876f3b8675a921d0ba39ed9f17127782d594b055)
- Add .release-it.yml to .gitignore [`3d9a8e5`](https://github.com/ruzickap/k8s-harbor-presentation/commit/3d9a8e501c020d870e6a68fd1fdfe53ca5004a4c)
- Update ubuntu from ubuntu-18.04 -&gt; ubuntu-latest [`b45468a`](https://github.com/ruzickap/k8s-harbor-presentation/commit/b45468a6674a3464e212c898854b817d97f70cdd)
- Update github-action-markdown-link-check to version v1 [`7d2c6e6`](https://github.com/ruzickap/k8s-harbor-presentation/commit/7d2c6e6002d9ab68ccb947635452a95e526fc9be)
- Increase version of markdown-link-check and use action-yamllint with tag [`e878c36`](https://github.com/ruzickap/k8s-harbor-presentation/commit/e878c3692fcd878f1e9f6b0c83fe3aaced7b25dc)
- Add comments to .yamllint.yml [`5ee9425`](https://github.com/ruzickap/k8s-harbor-presentation/commit/5ee9425535e3f212382b23a52e17c997a0260d45)
- Add comment to .markdownlint.yml [`b1a59e0`](https://github.com/ruzickap/k8s-harbor-presentation/commit/b1a59e04786c14610309ea35bfb44b38a32c574a)
- Periodic broken link checker improved [`6514687`](https://github.com/ruzickap/k8s-harbor-presentation/commit/6514687ef8e4be2b8ea750ea84b0d9e0acc8e6bc)
- Fix running periodic-broken-links-check [`0a1f528`](https://github.com/ruzickap/k8s-harbor-presentation/commit/0a1f52844af867fdf0341a86fa292c2020b04607)
- Fix parameter `-exclude` -&gt; `--exclude` + add .gitignore pre-commit [`aaa2c7f`](https://github.com/ruzickap/k8s-harbor-presentation/commit/aaa2c7ff8eb9b5cc97bfdd65553ea4a88077ed95)
- Fix tests to let them run only on master branch [`b296791`](https://github.com/ruzickap/k8s-harbor-presentation/commit/b296791805e590028207193f94e308465dde603d)
- Fix mdspell [`e31f5ff`](https://github.com/ruzickap/k8s-harbor-presentation/commit/e31f5ff52ec45a84597170b1a7b62a483ce0716e)
- Aadd GitHub Actions [`a5ba7a5`](https://github.com/ruzickap/k8s-harbor-presentation/commit/a5ba7a54ee7a3e3e6197a41031e49a35f22496e3)
- Adding "Automerged updates" by Dependabot [`0f2c86d`](https://github.com/ruzickap/k8s-harbor-presentation/commit/0f2c86d495c9dccc2cd3fba11a74249483208782)

## [v1.0.0](https://github.com/ruzickap/k8s-harbor-presentation/compare/v0.0.2...v1.0.0) (2019-11-01)

- Remove "Installation" from Agenda slide [`171c131`](https://github.com/ruzickap/k8s-harbor-presentation/commit/171c1315622fae9f7e2f8420a0187eb213bafd6b)
- Disable "Future plans for Harbor 1.9" slide [`5a7c715`](https://github.com/ruzickap/k8s-harbor-presentation/commit/5a7c715fdf7450f519faa4d26984a3cc203b6657)
- Added "Print" section into README [`d5e0ce6`](https://github.com/ruzickap/k8s-harbor-presentation/commit/d5e0ce67e057ca77a574375d77e8b0ad36cb10ac)

## [v0.0.2](https://github.com/ruzickap/k8s-harbor-presentation/compare/v0.0.1...v0.0.2) (2019-07-23)

- Move "Harbor - livecycle" slide behind Agenda [`abb7735`](https://github.com/ruzickap/k8s-harbor-presentation/commit/abb77359047f03437c266cd09e0146ca342f6695)
- Fix HTML attributes data-src -&gt; src and adding alt attributes [`c5f4360`](https://github.com/ruzickap/k8s-harbor-presentation/commit/c5f4360d64c1045dbc09ac53b2a4b45b38f41409)
- Adding Agenda slide [`09404f2`](https://github.com/ruzickap/k8s-harbor-presentation/commit/09404f2e6081f1227d921fd257b037a6b64ffa1a)
- Harbor demo architecture changed - external PostgreSQL removed [`745265a`](https://github.com/ruzickap/k8s-harbor-presentation/commit/745265ac4b6a18e02653a6f89e6fe4d1ef75a4a1)
- Adding links to last (Thank you) slide [`752b666`](https://github.com/ruzickap/k8s-harbor-presentation/commit/752b6665f66c6af7cef4e8aa30be6347f086eedb)

## v0.0.1 (2019-06-25)

- Add new architecture diagram with one harbor instance [`d80ad8c`](https://github.com/ruzickap/k8s-harbor-presentation/commit/d80ad8c5304e2079dec158db92027bd121a41275)
- Fix "Docker Hub" -&gt; "Docker Registry" [`d2925e3`](https://github.com/ruzickap/k8s-harbor-presentation/commit/d2925e3c0265dbe35748bc355f145ff73d948eea)
- Image link changed, webhook feature added [`1f3e9b4`](https://github.com/ruzickap/k8s-harbor-presentation/commit/1f3e9b41c3dcb6a2a4542562e218751d21d8660e)
- Adding container registries examples [`c2727af`](https://github.com/ruzickap/k8s-harbor-presentation/commit/c2727af3f6625319c17f60a22a464372fc85ef10)
- Fix missing link [`9218387`](https://github.com/ruzickap/k8s-harbor-presentation/commit/9218387dc05d9e89eeffe3047ce15ad8825ccd97)
- Optimized for FullHD [`f60e5c4`](https://github.com/ruzickap/k8s-harbor-presentation/commit/f60e5c451eab417b0a41fd02bd8601eacf7ae679)
- Sizing fixed [`59024ce`](https://github.com/ruzickap/k8s-harbor-presentation/commit/59024ce5c2880b16c966d675283e7dd244770401)
- Adding few more slides, changing size of slides, adding notes [`abf4a07`](https://github.com/ruzickap/k8s-harbor-presentation/commit/abf4a075f998080282e1fc8842ddbe9aa93660bf)
- Adding more slides + css improvements [`f3cb05d`](https://github.com/ruzickap/k8s-harbor-presentation/commit/f3cb05dda61fe91384dd8f5af232fbf60ad95d3f)
- Adding gruntfile.js to use 'npm start' easily [`1fb52cf`](https://github.com/ruzickap/k8s-harbor-presentation/commit/1fb52cfaf0ee251bc38fe8e8c00dbaf8a9aa5963)
- Adding nodejs files [`847d686`](https://github.com/ruzickap/k8s-harbor-presentation/commit/847d6864fed60181f929d830844ab95193567470)
- .gitignore added for nodejs [`db90cc3`](https://github.com/ruzickap/k8s-harbor-presentation/commit/db90cc397767885c3f07c8b3edd89e70f65629a1)
- Adding new slides [`337093b`](https://github.com/ruzickap/k8s-harbor-presentation/commit/337093b22720c64151789aa0cb085490cc9110c3)
- README.md updated with URLs and few notes [`83bc1de`](https://github.com/ruzickap/k8s-harbor-presentation/commit/83bc1de0d4b262e10cd7130771019ffd504aec1e)
- Adding initial index.html [`a01d144`](https://github.com/ruzickap/k8s-harbor-presentation/commit/a01d1447504ac9ea45a71237b7a790e718071fe2)
- Adding reveal.js [`f1c32c6`](https://github.com/ruzickap/k8s-harbor-presentation/commit/f1c32c6608b6956e2cac50bfd45a3cadfa9e14e8)
- Initial commit [`fc994af`](https://github.com/ruzickap/k8s-harbor-presentation/commit/fc994af2856b0528daf85d4cd90ae2687e1e00c4)
