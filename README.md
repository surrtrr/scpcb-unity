# SCP - Containment Breach (Unofficial Unity Port) - Bug Tracker

This is where bugs in the unofficial Unity port of SCP - Containment Breach v1.3.11 are reported and tracked.

## [Report a bug](../../issues/new/choose)

Click the link above, pick a form and fill it in. It takes about a minute and needs a free GitHub account.
No account? Leave a comment on the game's itch.io page instead and it will be added here for you.

## See what is already known

| | |
|---|---|
| [Open bugs](../../issues?q=is%3Aissue+is%3Aopen) | Everything reported and not fixed yet |
| [Fixed, arriving with the next update](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22fixed+in+next+update%22) | Already fixed, the fix is in the next download |
| [Fixed](../../issues?q=is%3Aissue+is%3Aclosed+label%3Afixed) | Fixed in the current download |
| [Kept on purpose](../../issues?q=is%3Aissue+label%3A%22original+game+behaviour%22) | The original game does it too, so the port does it too |

Before reporting, a quick search of the [existing reports](../../issues?q=is%3Aissue) saves you the typing. If your bug is already there, add a thumbs-up or a comment to it.

## What the labels mean

| Label | Meaning |
|---|---|
| `needs triage` | New report, not looked at yet |
| `confirmed` | Reproduced - it is a real bug in the port |
| `needs info` | More details are needed from the person who reported it |
| `fixed in next update` | Fixed already; you get the fix with the next download |
| `fixed` (issue closed) | Fixed in the current download |
| `original game behaviour` | Not a port bug: the original v1.3.11 behaves the same way |
| `mod loader` | About the Modded build, the Mods menu or the ModKit |

## "The original game does this too"

The goal of this port is to feel exactly like the original v1.3.11 - including its bugs and quirks. So a bug that also exists in the original is kept on purpose and is closed with the `original game behaviour` label. Anything that is **different** from the original (and is not listed as a deliberate change in License.txt) is a port bug and will be fixed.

## Where is the log file?

A log makes crashes far easier to fix. It is replaced every time the game starts, so grab it before you launch again.

- **Windows:** press Win+R and paste `%USERPROFILE%\AppData\LocalLow\DefaultCompany\SCP - Containment Breach` - the file is `Player.log`
- **Windows, Modded build:** `%USERPROFILE%\AppData\LocalLow\DefaultCompany\SCP - Containment Breach (Modded)`
- **Mac:** in Finder press Cmd+Shift+G and paste `~/Library/Logs/DefaultCompany/SCP - Containment Breach` (Modded build: the same with ` (Modded)` at the end)
- **Modded build only:** also attach `mod_report.txt` from the game's `Mods` folder

---

This project is unofficial and is not endorsed by the original developers. SCP - Containment Breach and this port are licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
