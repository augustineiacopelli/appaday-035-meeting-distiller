# 035 · Meeting Distiller

**AppADay** — App 035 of 365  
**Category:** AI-Powered (A)  
**Live:** <https://augustineiacopelli.github.io/appaday-035-meeting-distiller/>  
**Portfolio:** <https://augustineiacopelli.github.io/appaday/>

-----

## What It Does

Paste raw meeting notes — as messy as they come — and Meeting Distiller uses Claude to extract a clean structured breakdown: a plain-language summary, a list of decisions made, action items with owners and deadlines, and open questions that still need answers.

The standout feature is the **Send Deliverables** section at the bottom. Each person mentioned in the action items gets their own card. Enter their email address and tap Send — Meeting Distiller opens your mail client with a pre-written message listing that person’s tasks and deadlines, ready to go.

## Features

- Paste any raw meeting notes — bullet points, transcripts, stream-of-consciousness
- Claude extracts: summary, decisions, action items (with owner + deadline), open questions
- Per-person deliverable cards with one-tap `mailto:` email drafts
- API key stored in local Settings modal, never hardcoded
- Dark, monospace-accented UI styled after a developer console

## Stack

Single-file HTML/CSS/JS — no frameworks, no build step. Anthropic Claude API (`claude-sonnet-4-20250514`) via direct browser fetch. Deployable to GitHub Pages as-is.

## Setup

1. Get an [Anthropic API key](https://console.anthropic.com/)
1. Open the app and tap ⚙️ Settings
1. Enter your API key and save
1. Paste notes and tap **Distill Meeting**

-----

*Part of [AppADay](https://augustineiacopelli.github.io/appaday/) — one complete web app shipped every day.*
