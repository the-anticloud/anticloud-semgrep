# SEMGREP

> Anticloud offline package — upstream: semgrep/semgrep @ `develop`.

## What This Project Does

Lightweight static analysis for many languages. Find bug variants with patterns that look like source code.

**Topics:** c, go, java, javascript, python, r2c, ruby, sast, semgrep, static-analysis, static-code-analysis, typescript

## Upstream README

<br />
<p align="center">
  <a href="https://semgrep.dev">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="images/semgrep-logo-light.svg">
      <source media="(prefers-color-scheme: dark)" srcset="images/semgrep-logo-dark.svg">
      <img src="https://raw.githubusercontent.com/semgrep/semgrep/develop/images/semgrep-logo-light.svg" height="100" alt="Semgrep logo"/>
    </picture>
  </a>
</p>
<h2 align="center">
  Code scanning at ludicrous speed.
</h2>
<p align="center">
  <a href="https://formulae.brew.sh/formula/semgrep">
    <img src="https://img.shields.io/homebrew/v/semgrep?style=flat-square" alt="Homebrew" />
  </a>
  <a href="https://pypi.org/project/semgrep/">
    <img alt="PyPI" src="https://img.shields.io/pypi/v/semgrep?style=flat-square&color=blue">
  </a>
  <a href="https://semgrep.dev/docs/">
      <img src="https://img.shields.io/badge/docs-semgrep.dev-purple?style=flat-square" alt="Documentation" />
  </a>
  <a href="https://go.semgrep.dev/slack">
    <img src="https://img.shields.io/badge/slack-3.5k%20members-green?style=flat-square" alt="Join Semgrep community Slack" />
  </a>
  <a href="https://github.com/semgrep/semgrep/issues/new/choose">
    <img src="https://img.shields.io/badge/issues-welcome-green?style=flat-square" alt="Issues welcome!" />
  </a>
  <a href="https://github.com/semgrep/semgrep#readme">
    <img src="https://img.shields.io/github/stars/semgrep/semgrep?label=GitHub%20Stars&style=flat-square" alt="Star Semgrep on GitHub" />
  </a>
  <a href="https://hub.docker.com/r/semgrep/semgrep">
    <img src="https://img.shields.io/docker/pulls/semgrep/semgrep.svg?style=flat-square" alt="Docker Pulls" />
  </a>
  <a href="https://hub.docker.com/r/semgrep/semgrep">
    <img src="https://img.shields.io/docker/pulls/semgrep/semgrep.svg?style=flat-square" alt="Docker Pulls (Old)" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=semgrep">
    <img src="https://img.shields.io/twitter/follow/semgrep?label=Follow%20semgrep&style=social&color=blue" alt="Follow @semgrep on Twitter" />
  </a>
</p>
</br>

Semgrep is a fast, open-source, static analysis tool that searches code, finds bugs, and enforces secure guardrails and coding standards. Semgrep [supports 30+ languages](#language-support) and can run in an IDE, as a pre-commit check, and as part of CI/CD workflows.

Semgrep is semantic grep for code. While running `grep "2"` would only match the exact string _2_, Semgrep would [match `x = 1; y = x + 1` when searching for _2_](https://semgrep.dev/playground/s/5rKgj). Semgrep rules look like the code you already write; no abstract syntax trees, regex wrestling, or painful DSLs.

Note that in security contexts, Semgrep Community Edition will miss many true positives as it can only analyze code within the boundaries of a single function or file. If you want to use Semgrep for security purposes (**SAST**, **SCA**, or **secrets scanning**), the Semgrep AppSec Platform is strongly recommended s

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
