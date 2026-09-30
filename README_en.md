<p align="center">
  <b>Ocean Needle</b>
  <br>
  <a href="README.md">中文</a> | English | <a href="README_ja.md">日本語</a>
  <br>
  Sifting genuinely useful AI Skills out of the open internet.
  <br>
  Scanned every Wednesday · compiled on the 29th · up to 20 entries per issue
  <br><br>
  <a href="https://github.com/gu-reni/ocean-needle/stargazers"><img src="https://img.shields.io/github/stars/gu-reni/ocean-needle.svg?style=popout-square" alt="GitHub stars"></a>
  <a href="https://github.com/gu-reni/ocean-needle/issues"><img src="https://img.shields.io/github/issues/gu-reni/ocean-needle.svg?style=popout-square" alt="GitHub issues"></a>
</p>

## Introduction

**Ocean Needle** (Chinese: 大海捞针, literally *"fishing a needle out of the ocean"* — a needle in a haystack) is a monthly digest of **practical, ready-to-use AI Skills**: skill packages you can install today, curated skill collections, and the tooling that grows around them — managers, optimizers and security scanners.

It draws on GitHub, dedicated Skill directories, Chinese AI communities and industry feeds. Each issue is compiled by hand from a deduplicated pool accumulated over the preceding month.

- **Scanned every Wednesday** — anything already covered is filtered out through a dedupe ledger
- **One issue per month**, published on the 29th
- **At most 20 entries per issue** — quality over quantity, never padded to fill a quota
- Every issue ships as both **Markdown source** and a **rendered web page**

## Content

| :card_index: | :jack_o_lantern: | :beer: | :fish_cake: | :octocat: |
| ------- | ----- | ------------ | ------ | --------- |
| [Issue 01](/reports/en/01.md) | | | | |

> Click an issue number for the Markdown source. To read it in a browser, change the `.md` suffix to `.html`.
>
> Issue 01 is a re-compilation of the original issues 01 and 02, which is why it exceeds the usual entry limit.

## How each issue is organised

Entries are grouped by category. Each one carries the **project name, repository URL, star count, what it does, and the date of its latest commit**:

| Category | What it covers |
|---|---|
| **AI Skill** | Individual skill packages you can install and use right away |
| **Skill repos & tooling** | Curated skill collections, plus managers, optimizers and security scanners |

Some issues close with a **"Not recommended"** entry — a project that looks popular but turns out to be immature or abandoned, with a plain explanation of **why you should skip it**. Star count alone is never the basis for selection.

## How entries are chosen

Three criteria, all of them required:

1. **Actually useful** — it solves a real problem once installed, not a concept demo
2. **Still alive** — commits landed recently, rather than months ago
3. **Explainable** — worth 2–3 concrete sentences about when to use it, not a vague "it's great"

**Star counts and last-commit dates are queried live from the GitHub API** — never filled in from memory, and never taken from numbers quoted in search summaries. Some entries carry **security-risk and dependency information**.

## Repository layout

| Path | Description |
|---|---|
| `README.md` / `README_en.md` / `README_ja.md` | Chinese / English / Japanese documentation |
| `reports/NN.md` | Issue NN, Chinese (Markdown source) |
| `reports/NN.html` | Issue NN, Chinese (rendered web page) |
| `reports/en/NN.md` | Issue NN, English (Markdown source) |
| `reports/en/NN.html` | Issue NN, English (rendered web page) |
| `state/seen.tsv` | Dedupe ledger: unique keys of everything already covered |
| `scripts/report-header.html` | Stylesheet template used when rendering |
