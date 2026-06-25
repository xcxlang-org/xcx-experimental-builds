# XCX Experimental Builds

This repository hosts experimental and research builds of the XCX compiler and runtime.

## ⚠️ Important

These builds are **not officially supported**. They may be unstable, incomplete, or abandoned at any time without notice. Do not use in production.

## Available Builds

| Platform | Version | Notes |
|----------|---------|-------|
| FreeBSD 15.0 (amd64) | 4.1-experimental | JIT disabled (mmap permissions). Interpreter fallback only. Use `--no-jit` flag |

## Reporting Issues

Found a bug or platform-specific issue? **Open an issue in this repository** — feedback from experimental builds helps improve multi-platform support in future XCX releases.

> [!IMPORTANT]
> **Please do not open issues about experimental builds in the [main repository](https://github.com/xcxlang-org/xcx).** Use this repository's issue tracker instead.

Please include:
- Platform and OS version
- XCX build version
- Steps to reproduce
- Output / error message

For stable releases, visit [xcxlang.com](https://xcxlang.com) or the [main repository](https://github.com/xcxlang-org/xcx).
