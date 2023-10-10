<h2 align="center">
  codebase - A code review dog who keeps your codebase healthy.
</h2>

<div align="center">
  <a href="./LICENSE">
    <img alt="LICENSE" src="https://img.shields.io/badge/license-MIT-blue.svg?maxAge=43200">
  </a>
  <a href="https://godoc.org/github.com/khulnasoft/codebase">
    <img alt="GoDoc" src="https://img.shields.io/badge/godoc-reference-4F73B3.svg?label=godoc.org&maxAge=43200&logo=go">
  </a>
  <a href="./CHANGELOG.md">
    <img alt="releases" src="https://img.shields.io/github/release/khulnasoft/codebase.svg?logo=github">
  </a>
  <a href="https://github.com/khulnasoft/nightly">
    <img alt="nightly releases" src="https://img.shields.io/github/v/release/codebase/nightly.svg?logo=github">
  </a>
</div>

<div align="center">
  <a href="https://github.com/khulnasoft/codebase/actions?query=workflow%3AGo+event%3Apush+branch%3Amaster">
    <img alt="GitHub Actions" src="https://github.com/khulnasoft/codebase/workflows/Go/badge.svg">
  </a>
  <a href="https://github.com/khulnasoft/codebase/actions?query=workflow%3Acodebase+event%3Apush+branch%3Amaster">
    <img alt="codebase" src="https://github.com/khulnasoft/codebase/workflows/codebase/badge.svg?branch=master&event=push">
  </a>
  <a href="https://github.com/khulnasoft/codebase/actions?query=workflow%3Arelease">
    <img alt="release" src="https://github.com/khulnasoft/codebase/workflows/release/badge.svg">
  </a>
  <a href="https://travis-ci.org/khulnasoft/codebase"><img alt="Travis Status" src="https://img.shields.io/travis/khulnasoft/codebase/master.svg?label=Travis&logo=travis"></a>
  <a href="https://circleci.com/gh/khulnasoft/codebase"><img alt="CircleCI Status" src="http://img.shields.io/circleci/build/github/khulnasoft/codebase/master.svg?label=CircleCI&logo=circleci"></a>
  <a href="https://codecov.io/github/khulnasoft/codebase"><img alt="Coverage Status" src="https://img.shields.io/codecov/c/github/khulnasoft/codebase/master.svg?logo=codecov"></a>
</div>

<div align="center">
  <a href="https://gitlab.com/khulnasoft/codebase/pipelines">
    <img alt="GitLab Supported" src="https://img.shields.io/badge/GitLab%20-Supported-fc6d26?logo=gitlab">
  </a>
  <a href="https://github.com/haya14busa/action-bumpr">
    <img alt="action-bumpr supported" src="https://img.shields.io/badge/bumpr-supported-ff69b4?logo=github&link=https://github.com/haya14busa/action-bumpr">
  </a>
  <a href="https://github.com/khulnasoft/.github/blob/master/CODE_OF_CONDUCT.md">
    <img alt="Contributor Covenant" src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg">
  </a>
  <a href="https://somsubhra.github.io/github-release-stats/?username=khulnasoft&repository=codebase&per_page=30">
    <img alt="GitHub Releases Stats" src="https://img.shields.io/github/downloads/khulnasoft/codebase/total.svg?logo=github">
  </a>
  <a href="https://starchart.cc/khulnasoft/codebase"><img alt="Stars" src="https://img.shields.io/github/stars/khulnasoft/codebase.svg?style=social"></a>
</div>
<br />

khulnasoft provides a way to post review comments to code hosting service,
such as GitHub, automatically by integrating with any linter tools with ease.
It uses an output of lint tools and posts them as a comment if findings are in
diff of patches to review.

codebase also supports run in the local environment to filter an output of lint tools
by diff.
