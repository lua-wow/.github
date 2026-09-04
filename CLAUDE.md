# CLAUDE.md

## About

[lua-wow](https://github.com/lua-wow) is my personal GitHub organization used to separate World of Warcraft addons from my general programming repositories.

This repository (`lua-wow/.github`) contains organization-level GitHub configuration and the organization profile at `profile/README.md`.

## Instructions

- When working on `profile/README.md`, inspect the organization's repositories and their documentation before making content decisions.
- Prefer information from the actual repositories over assumptions.
- Keep the organization profile concise, minimalistic, and developer-oriented.
- Do not invent projects, features, compatibility information, statistics, or claims.
- Do not modify repositories outside this `.github` repository.

## Repository Inspection

- Other organization repositories are not normally cloned locally.
- When deeper inspection is useful, repositories may be cloned into `.repo/`.
- `.repo/` is temporary research material and must remain untracked.
- Only clone repositories relevant to the current task.
- Do not modify repositories inside `.repo/`.
- SSH access to GitHub is already configured; use SSH URLs when cloning repositories.

## Workflow

For changes to the organization profile:

1. Inspect the organization and relevant repositories.
2. Understand what each project actually does.
3. Draft the profile based on the discovered information.
4. Make the requested file changes.
5. Show a summary of what changed.

## Repositories

### Important

These repositories should receive priority when researching or documenting the organization:

1. `Tainted`
2. `Filger`
3. `oUF`
4. `oUF_` — repositories whose names start with `oUF_`

### Ignore

Do not include these repositories in new organization-profile content:

- `Tukui`
- `oUF_Lua`
- `JasjeUI`
- `lua-wow`
- `tukui-bkp`
- `Tukui-archive`
- `Blizzard-API`

### Deprecated / No Longer Maintained

- `xCT` — do not describe it as an actively maintained project.

## Safety

- Git write operations are forbidden.
- Git read-only operations are allowed.
- Do not create commits.
- Do not push changes.
- Do not modify Git history.
