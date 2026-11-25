<p align="center">
  <img src="docs/assets/banner.webp" alt="Brei0x, a dark graphite theme for Rocket.Chat 9, shown on the #engineering channel in a desktop window" width="100%">
</p>

# Rocket.Chat Theme - Brei0x

Dark graphite theme for Rocket.Chat: neutral grays, a single blue accent, square corners
and Darcula-style code blocks.

<p align="center">
  <a href="https://github.com/brei0x/rocketchat-dark-theme/actions/workflows/ci.yml"><img src="https://github.com/brei0x/rocketchat-dark-theme/actions/workflows/ci.yml/badge.svg?branch=main" alt="CI"></a>
  <a href="https://github.com/brei0x/rocketchat-dark-theme/releases/latest"><img src="https://img.shields.io/github/v/release/brei0x/rocketchat-dark-theme?sort=semver&label=release&labelColor=24292e&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSIjOTU5ZGE1IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBkPSJNMSA3Ljc3NVYyLjc1QzEgMS43ODQgMS43ODQgMSAyLjc1IDFoNS4wMjVjLjQ2NCAwIC45MS4xODQgMS4yMzguNTEzbDYuMjUgNi4yNWExLjc1IDEuNzUgMCAwIDEgMCAyLjQ3NGwtNS4wMjYgNS4wMjZhMS43NSAxLjc1IDAgMCAxLTIuNDc0IDBsLTYuMjUtNi4yNUExLjc1MiAxLjc1MiAwIDAgMSAxIDcuNzc1Wm0xLjUgMGMwIC4wNjYuMDI2LjEzLjA3My4xNzdsNi4yNSA2LjI1YS4yNS4yNSAwIDAgMCAuMzU0IDBsNS4wMjUtNS4wMjVhLjI1LjI1IDAgMCAwIDAtLjM1NGwtNi4yNS02LjI1YS4yNS4yNSAwIDAgMC0uMTc3LS4wNzNIMi43NWEuMjUuMjUgMCAwIDAtLjI1LjI1Wk02IDVhMSAxIDAgMSAxIDAgMiAxIDEgMCAwIDEgMC0yWiIvPjwvc3ZnPg%3D%3D" alt="Latest release"></a>
  <a href="https://github.com/brei0x/rocketchat-dark-theme/blob/main/LICENSE"><img src="https://img.shields.io/github/license/brei0x/rocketchat-dark-theme?labelColor=24292e&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSIjOTU5ZGE1IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBkPSJNOC43NS43NVYyaC45ODVjLjMwNCAwIC42MDMuMDguODY3LjIzMWwxLjI5LjczNmMuMDM4LjAyMi4wOC4wMzMuMTI0LjAzM2gyLjIzNGEuNzUuNzUgMCAwIDEgMCAxLjVoLS40MjdsMi4xMTEgNC42OTJhLjc1Ljc1IDAgMCAxLS4xNTQuODM4bC0uNTMtLjUzLjUyOS41MzEtLjAwMS4wMDItLjAwMi4wMDItLjAwNi4wMDYtLjAwNi4wMDUtLjAxLjAxLS4wNDUuMDRjLS4yMS4xNzYtLjQ0MS4zMjctLjY4Ni40NUMxNC41NTYgMTAuNzggMTMuODggMTEgMTMgMTFhNC40OTggNC40OTggMCAwIDEtMi4wMjMtLjQ1NCAzLjU0NCAzLjU0NCAwIDAgMS0uNjg2LS40NWwtLjA0NS0uMDQtLjAxNi0uMDE1LS4wMDYtLjAwNi0uMDA0LS4wMDR2LS4wMDFhLjc1Ljc1IDAgMCAxLS4xNTQtLjgzOEwxMi4xNzggNC41aC0uMTYyYy0uMzA1IDAtLjYwNC0uMDc5LS44NjgtLjIzMWwtMS4yOS0uNzM2YS4yNDUuMjQ1IDAgMCAwLS4xMjQtLjAzM0g4Ljc1VjEzaDIuNWEuNzUuNzUgMCAwIDEgMCAxLjVoLTYuNWEuNzUuNzUgMCAwIDEgMC0xLjVoMi41VjMuNWgtLjk4NGEuMjQ1LjI0NSAwIDAgMC0uMTI0LjAzM2wtMS4yODkuNzM3Yy0uMjY1LjE1LS41NjQuMjMtLjg2OS4yM2gtLjE2MmwyLjExMiA0LjY5MmEuNzUuNzUgMCAwIDEtLjE1NC44MzhsLS41My0uNTMuNTI5LjUzMS0uMDAxLjAwMi0uMDAyLjAwMi0uMDA2LjAwNi0uMDE2LjAxNS0uMDQ1LjA0Yy0uMjEuMTc2LS40NDEuMzI3LS42ODYuNDVDNC41NTYgMTAuNzggMy44OCAxMSAzIDExYTQuNDk4IDQuNDk4IDAgMCAxLTIuMDIzLS40NTQgMy41NDQgMy41NDQgMCAwIDEtLjY4Ni0uNDVsLS4wNDUtLjA0LS4wMTYtLjAxNS0uMDA2LS4wMDYtLjAwNC0uMDA0di0uMDAxYS43NS43NSAwIDAgMS0uMTU0LS44MzhMMi4xNzggNC41SDEuNzVhLjc1Ljc1IDAgMCAxIDAtMS41aDIuMjM0YS4yNDkuMjQ5IDAgMCAwIC4xMjUtLjAzM2wxLjI4OC0uNzM3Yy4yNjUtLjE1LjU2NC0uMjMuODY5LS4yM2guOTg0Vi43NWEuNzUuNzUgMCAwIDEgMS41IDBabTIuOTQ1IDguNDc3Yy4yODUuMTM1LjcxOC4yNzMgMS4zMDUuMjczczEuMDItLjEzOCAxLjMwNS0uMjczTDEzIDYuMzI3Wm0tMTAgMGMuMjg1LjEzNS43MTguMjczIDEuMzA1LjI3M3MxLjAyLS4xMzggMS4zMDUtLjI3M0wzIDYuMzI3WiIvPjwvc3ZnPg%3D%3D" alt="License"></a>
</p>

---

## Prerequisites

- Rocket.Chat **9.0** or later, web client or desktop app. Built and checked on 9.0.0.
- An administrator account (permission `edit-privileged-setting`) to change the Custom CSS setting.

The theme is a single stylesheet that overrides Rocket.Chat's Fuselage color tokens. It does not
apply to the iOS and Android apps, which ignore Custom CSS.

## Install

1. Copy the content of [`brei0x.css`](brei0x.css).
2. Paste it in **Administration > Workspace > Settings > Layout > Custom CSS**, then save.
3. Reload the page.

Upgrade, removal and troubleshooting: [docs/SETUP.md](docs/SETUP.md).
Changes between versions: [releases](https://github.com/brei0x/rocketchat-dark-theme/releases).

## Screenshot

![The #engineering channel with the Brei0x theme: channel sidebar, messages, a Darcula code block and the composer](docs/assets/screenshot.jpg)
