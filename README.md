# Appear

The website for 2appear.network. Appear helps people be seen in the way they want to be seen, and co-create in a way that works.

## How it is built

- Plain HTML pages with no build step, served by GitHub Pages.
- The top bar and sign-in load from https://2gather.network/nav/ with no version number. That host answers with `cache-control: no-cache`, so a change there reaches every site.
- The look follows 2Gather. The top bar shows Appear's own logo and line on this host.

## Where it is going

This repo is stage 1. The plan is a single combined repo with `common/` (the shared top bar and sign-in), `gather/`, `appear/` and `balance/`. When that exists, the pages here move into `appear/`.
