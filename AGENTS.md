# AGENTS.md

Instructions for AI coding agents working in this repository.

This repo is one curated list, [README.md](README.md). Almost every change is a pull request that adds one affiliate program to it. Follow every rule in [contributing.md](contributing.md). The steps below show how to apply them.

## Adding a program

1. Open the program page and read the current terms. Write only figures the page states. If a figure isn't there (a cookie window, a minimum payout), leave it out rather than guessing.
2. Confirm both links load, with no 404 and no login wall.
3. Search README.md for the product's name and domain. If it's already listed, stop and tell the user. If the listed terms are out of date, update that entry instead of adding a new one.
4. Pick the section that fits best and insert the entry in alphabetical order (ignoring case) among its neighbors.
5. Match the format of recent entries exactly: `- [Product](homepage) - [affiliate information](program page) Description`.
6. Check that the diff is your one added line, plus an anchor and Index line if you added a section. Revert any incidental whitespace, line-ending or reformatting changes.
7. Title the PR `Add <Product> to <Section>`. In the description, link the program page and say whether the user works for or owns the product. If you don't know, ask the user.

## Don't

- Don't edit, reorder or remove other entries in the same PR.
- Don't add marketing language, emoji or calls to action to the entry.
- Don't use a referral or affiliate link as the product link.
- Don't change files other than README.md when adding a listing.
