# ctx-guard installer

```bash
curl -fsSL https://raw.githubusercontent.com/ctx-guard/install/main/get.sh | bash
```

`get.sh` downloads the latest [ctx-guard](https://github.com/viktor-tapovski/ctx-guard) release tarball, checks its SHA-256 against the value written into the script, and refuses to install on a mismatch. To review it first, read [`get.sh`](get.sh), then run `bash get.sh`.

Pass options after `bash -s --`, for example `--agents claude-code,codex-cli` or `--yes`.

This repo is updated automatically by each ctx-guard release. Report issues in the [main repo](https://github.com/viktor-tapovski/ctx-guard/issues).
