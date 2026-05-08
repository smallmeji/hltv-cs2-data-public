# hltv-cs2-data-public

Static JSON export for `hltv-cs2-data`.

This repository contains generated CS2 data snapshots exported from the maintained HLTV-derived database. It is a data distribution repository only. It does not contain the skill instructions, private database credentials, prediction logic, betting logic, or collector runtime.

## Entry Points

- Raw manifest: `https://raw.githubusercontent.com/smallmeji/hltv-cs2-data-public/main/manifest.json`
- Compatibility manifest: `https://raw.githubusercontent.com/smallmeji/hltv-cs2-data-public/main/latest/manifest.json`
- GitHub Pages compatibility path, if Pages is enabled: `https://smallmeji.github.io/hltv-cs2-data-public/latest/manifest.json`

Consumers should read `manifest.json` first, then follow exact JSON paths listed in the manifest. Do not fetch a directory URL as if it were JSON.

## Update Model

The database is maintained separately. Daily or event-specific exports update this repository without changing the `hltv-cs2-data` skill package. Users only need to update the skill when the instructions or data contract changes.

