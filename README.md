# pid-spoon-mechanical

## Purpose

Mechanical work for PID Spoon: CAD exports, drawings, analysis, and the bill of materials.

The project charter, interface index and decision record are in [pid-spoon-hub](https://github.com/IEEE-USF-EXO/pid-spoon-hub).

## Scope

In this repo: neutral-format CAD exports, drawings, analysis notes, the BOM, reviewed test summaries.

Not in this repo: firmware (pid-spoon-controls), schematics and PCB (pid-spoon-electrical), native SOLIDWORKS files (Drive).

## Owner

Team lead: @layanbargouthi. Org team: `pid-spoon-mechanical`.

## Folder map

| Path | Holds |
| --- | --- |
| `modules/` | TODO: fill at kickoff |
| `analysis/` | TODO: fill at kickoff |
| `bom/` | TODO: fill at kickoff |
| `docs/` | Reviewed notes, test summaries |

The folder map is provisional. It follows the structure used by the matching EXO repo and will be adjusted once `docs/CHARTER.md` in pid-spoon-hub defines the scope.

## How to contribute

1. Pull `main` before you start: `git pull origin main`.
2. Branch: `git checkout -b <your-name>/<short-description>`.
3. Commit in small steps with a message that says what changed.
4. Push: `git push -u origin <branch>`.
5. Open a pull request and fill in all four sections of the template.
6. One teammate reviews and approves, then you merge. Nobody pushes to `main` directly.

## What never goes here

- Passwords, tokens, API keys, personal email addresses, phone numbers. This repo is public. Deleting a file does not remove it from history; a committed secret must be rotated.
- On-body sensor data, and any data from a person wearing part of a device. Gate S2 is open. Nothing of that kind goes into this repo or into Drive until a written faculty or PI determination exists.
- Native CAD binaries and raw bench logs. Those stay in Drive. Commit a summary, not the raw file.

## Drive folder

[CAD](https://drive.google.com/drive/folders/1a1LPEQUeCjfbkV6nDJag9Hsq55-Go0J8)

Raw files stay in Drive. A short summary goes in `docs/` and names the Drive file and the date. If the link says you need access, use Request access or ask a Project Lead.

## Board

PID Spoon organization board: to be added once the board is created.

## Related repos

- https://github.com/IEEE-USF-EXO/pid-spoon-hub
- https://github.com/IEEE-USF-EXO/pid-spoon-controls
- https://github.com/IEEE-USF-EXO/pid-spoon-electrical
