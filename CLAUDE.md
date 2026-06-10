# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal GitHub Pages site for Yutthana (Oat), built with Jekyll using the `jekyll-theme-minimal` theme. It is deployed automatically by GitHub Pages from the `main` branch.

## Local Development

Install Jekyll and serve the site locally:

```bash
gem install jekyll bundler
jekyll serve
```

The site will be available at `http://localhost:4000`.

## Configuration

Site metadata (title, description, theme) lives in `_config.yml`. GitHub Pages picks up changes on push to `main`.

## Structure

- `_config.yml` — Jekyll site configuration and theme selection
- `docs/` — intended for page content (currently empty)
- `README.md` — repository description shown on GitHub
