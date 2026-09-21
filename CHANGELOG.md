# Changelog

Since we follow [Conventional
Commits](https://decisions.seedcase-project.org/why-conventional-commits/),
we're able to automatically create formal "releases" of the website based on our
commit messages. Releases in the context of websites are simply snapshots in
time of the website content. We use
[Cocogitto](https://decisions.seedcase-project.org/why-semantic-release-with-cocogitto/)
to be able to automatically create these releases, which uses
[SemVar](https://semverdoc.org) as the version numbering scheme, and
[git-cliff](https://decisions.seedcase-project.org/why-changelog-with-git-cliff/)
to generate the changelog based on the commit messages.

Because releases are created based on commit messages, a new release is created
quite often---sometimes several times in a day. This also means that any
individual release will not have many changes within it. Below is a list of the
releases we've made so far, along with what was changed within each release.

Commits from bots, like `dependabot` or `pre-commit-ci`, are not included in the
changelog.

## [0.3.0](https://github.com/dp-next/wp3-d-clin-dmp/compare/0.2.0..0.3.0) - 2026-09-21

### ✨ Features

- Add section on data and metadata sharing
  [#6](https://github.com/dp-next/wp3-d-clin-dmp/pull/6) by
  [`@Davads123`](https://github.com/Davads123)
  ([966b544](https://github.com/dp-next/wp3-d-clin-dmp/commit/966b5441c62f4f28456a2b119d974a3bdd20ccf4))

## [0.2.0](https://github.com/dp-next/wp3-d-clin-dmp/compare/0.1.0..0.2.0) - 2026-09-19

### ✨ Features

- Move over sections from ON-LiMiT DMP
  [#1](https://github.com/dp-next/wp3-d-clin-dmp/pull/1) by
  [`@Davads123`](https://github.com/Davads123)
  ([49144b8](https://github.com/dp-next/wp3-d-clin-dmp/commit/49144b8e7e6a7cc058f535c2d9567c4b0170ea1b))

### 👩‍💻 Miscellaneous

- Ignore URL checks of pre-commit.ci
  [#22](https://github.com/dp-next/wp3-d-clin-dmp/pull/22) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([457c0da](https://github.com/dp-next/wp3-d-clin-dmp/commit/457c0daf3a1b7f46596317f6e30c4e55bd4eba6c))
- Fix Quarto website build with correct project type
  [#23](https://github.com/dp-next/wp3-d-clin-dmp/pull/23) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([a36a959](https://github.com/dp-next/wp3-d-clin-dmp/commit/a36a959318c7516df13035a56b3d6703e79ce569))

### ❤️ New contributors

- `@dependabot[bot]` started making automated contributions

## 0.1.0 - 2026-09-19

### ✨ Features

- Add ethical, legal, and privacy section
  [#3](https://github.com/dp-next/wp3-d-clin-dmp/pull/3) by
  [`@Davads123`](https://github.com/Davads123)
  ([915fda8](https://github.com/dp-next/wp3-d-clin-dmp/commit/915fda8032722b72820c1440340affe0c282e5d2))

### 📝 Documentation

- Update README from template
  [#11](https://github.com/dp-next/wp3-d-clin-dmp/pull/11) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([f56acbf](https://github.com/dp-next/wp3-d-clin-dmp/commit/f56acbfedfd6f24c42a62b72c3055b67f619cb36))
- Add community health files (from template)
  [#12](https://github.com/dp-next/wp3-d-clin-dmp/pull/12) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([ec7c984](https://github.com/dp-next/wp3-d-clin-dmp/commit/ec7c9843e89ef2323473d8d3e72c0d9307926c4e))

### 👷 CI/CD

- Add or update workflows from template
  [#15](https://github.com/dp-next/wp3-d-clin-dmp/pull/15) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([81b8704](https://github.com/dp-next/wp3-d-clin-dmp/commit/81b87043652b1bdfc4f91718c9bf48129f83b10a))
- Add continuous release workflows
  [#14](https://github.com/dp-next/wp3-d-clin-dmp/pull/14) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([bcb101f](https://github.com/dp-next/wp3-d-clin-dmp/commit/bcb101fc1ee59a582a0e460ea2f105b1b7cb7393))

### 👩‍💻 Miscellaneous

- Created from template by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([6ba2bae](https://github.com/dp-next/wp3-d-clin-dmp/commit/6ba2baea7dfae76af35916e4d6ce56d46389118f))
- Add developer experience config and build files
  [#13](https://github.com/dp-next/wp3-d-clin-dmp/pull/13) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([a17bdb5](https://github.com/dp-next/wp3-d-clin-dmp/commit/a17bdb5ac9a16ea8564ff07c2a7df3031873e9ee))
- Update Quarto config files and add theme
  [#10](https://github.com/dp-next/wp3-d-clin-dmp/pull/10) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([5fe03b2](https://github.com/dp-next/wp3-d-clin-dmp/commit/5fe03b2a97ec615536187e80f0a20b4aed3e17c5))

### ❤️ New contributors

- `@github-actions[bot]` started making automated contributions

- [`@Davads123`](https://github.com/Davads123) made their first contribution in
  [#3](https://github.com/dp-next/wp3-d-clin-dmp/pull/3)

- [`@lwjohnst86`](https://github.com/lwjohnst86) made their first contribution
  in [#14](https://github.com/dp-next/wp3-d-clin-dmp/pull/14)
