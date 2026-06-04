# GitHub Projects Scope Fix v1.8

Date: 2026-06-04  
Repository: https://github.com/Shadow-3/first-nations-governance-commons-public-demo  
Blocked issue: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/1

## Current Blocker

Native GitHub Projects board creation is blocked because the current GitHub CLI token is missing project scope. The observed command error was:

`your authentication token is missing required scopes [read:project]`

The sprint can still proceed using the fallback board:

- Milestone #1.
- Status labels.
- Domain labels.
- Issue comments for evidence.

## Fix Path

Run this from the machine where `gh` is authenticated:

```powershell
gh auth refresh --scopes project
```

Then confirm access:

```powershell
gh project list --owner Shadow-3
```

Create the native Project:

```powershell
gh project create --owner Shadow-3 --title "First fake-data Decidim sandbox sprint"
```

After creation, add or configure fields/views for:

- Inbox.
- Ready.
- In Progress.
- Review.
- Blocked.
- Done.

## Minimum Acceptance Check

S-001 can move out of `status:blocked` when one of these is true:

- Native GitHub Project exists and is linked from S-001.
- Maintainer records that the fallback milestone plus status-label board is the official board for this sprint.

## Safety Note

Do not use GitHub Project fields, issue comments, or screenshots for real community records, private member information, cultural material, real voting data, or real decision outcomes.

