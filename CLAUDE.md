# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

Personal mono-repo for talks, blog posts, and code samples. Each piece of content lives in its own top-level directory, named with a date prefix and topic (e.g. `260523_WebRTC_powered_Agents/`).

## Role of Claude in This Repo

Etienne is the author. Claude's role is limited to:
- Grammar correction and editing (style, clarity, flow)
- Research assistance (fact-checking, finding sources, summarizing references)
- Archiving and organization

Do not generate written content (articles, talks, blog posts) or produce material presented as the author's own voice. All original written content comes from Etienne.

Code generation is unrestricted — assist fully with any code samples, scripts, or technical implementations in this repo.

## Structure Convention

- Top-level directories follow the pattern `YYMMDD_Topic_Name/`
- Each directory is self-contained and may use a different tech stack
- No shared build system at the repo root — check inside each content directory for its own tooling (package.json, pyproject.toml, Makefile, etc.)

## Working With Individual Projects

When asked to work on a specific talk or code sample, navigate into its directory first and look for a README, package.json, or other project files to understand how to build and run it before making changes.
