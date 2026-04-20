---
layout: default
title: Inkwell — Privacy Policy
---

# Inkwell — Privacy Policy

**Last updated: 20 April 2026**

This Privacy Policy describes how **Inkwell** (the "app") handles your journal entries and related information.

Inkwell is developed and operated by an independent developer based in Spain. Contact: **vendrell.dev@gmail.com**.

## Summary in one paragraph

Your journal entries are **stored locally on your device in an AES-256 encrypted database** (SQLCipher). Routine AI features (mood detection, auto-tags, titles, one-line summaries) run **on your device** and your entries never leave your phone. "Deep insight" is an explicit opt-in feature, enabled per entry, that sends **that single entry** to Anthropic's Claude API over an encrypted connection; it is deleted by Anthropic within 7 days and is never used to train AI models.

## What the app stores on your device

- Journal entries (gratitude, habits, free-writing, mood check-ins) — stored in an SQLCipher-encrypted database in the app's private storage. The encryption key is held in the Android Keystore and protected by your device biometric or PIN.
- Prompts you've answered, streak data, habit logs, reminders — local only.
- AI-generated metadata (auto-titles, tags, mood labels, one-line summaries from on-device models) — stored alongside the relevant entry, local only.

You can export everything to JSON or Markdown at any time from **Settings → Export**. You can delete everything from **Settings → Delete all data**.

## On-device AI (default)

Routine AI operations — inferring mood from free text, generating auto-titles and tags, producing one-line summaries — run locally using your device's built-in on-device models (Google Gemini Nano on supported Android devices, or a bundled small-model fallback).

These operations happen entirely on your device. No entry content is transmitted off-device for these features.

## Cloud AI ("Deep Insight") — opt-in per entry

"Deep Insight" is a separate feature activated only when you explicitly tap it on a specific entry:

- **What is sent**: the single entry's text only. Not the whole journal, never automatically, never in the background.
- **Who receives it**: Anthropic, Inc. (USA) and/or Anthropic Ireland Ltd., via the Claude API.
- **How long Anthropic retains it**: up to 7 days for trust and safety purposes, after which it is deleted. Anthropic does not use API inputs to train AI models.
- **Legal basis (GDPR)**: your explicit consent (Art. 9(2)(a)) each time you first enable the feature. You can withdraw consent at any time in **Settings → AI**.
- **Transfer outside the EU**: data may be processed in the United States under Standard Contractual Clauses and Anthropic's DPA.

You can disable cloud AI entirely in settings; the rest of the app works without it.

## What the app does NOT do

- It does **not** run analytics or crash reporting in v1.0.
- It does **not** upload your journal to any cloud backup in v1.0 (no "cloud sync" feature exists).
- It does **not** share your entries with any third party other than Anthropic, and only when you explicitly tap Deep Insight.
- It does **not** read your contacts, location, calendar, camera, or microphone.

## Permissions requested

- **POST_NOTIFICATIONS** (Android 13+): for daily journaling reminders.
- **USE_BIOMETRIC / USE_FINGERPRINT**: to unlock the encrypted database. Biometric data itself never leaves your device.
- **INTERNET**: only used when you tap Deep Insight. Otherwise the app operates fully offline.

## Special-category data (GDPR Article 9)

Journal content frequently contains information about your mental or physical health, beliefs, and relationships. We treat all journal content as **special-category personal data** under Article 9 of the GDPR. This is why:

- Storage is always encrypted.
- Cloud processing requires explicit, granular, per-entry consent.
- A Data Protection Impact Assessment has been conducted for this processing.

## Your rights under GDPR and UK GDPR

You have the right to:

- **Access** a copy of your data (Settings → Export → JSON or Markdown).
- **Rectify** any entry by editing or deleting it inside the app.
- **Erase** all your data (Settings → Delete all data). This removes everything from your device. For data previously sent via Deep Insight, Anthropic deletes it on its own 7-day schedule; you can also request erasure by contacting **vendrell.dev@gmail.com**.
- **Object** to or withdraw consent for cloud AI at any time (Settings → AI → Off).
- **Lodge a complaint** with the Spanish data-protection authority (AEPD, aepd.es) or your local EU/UK authority.

## Children

Inkwell is not directed at children. Target audience on Google Play: 18+.

## Not a medical or therapeutic service

Inkwell is a journaling tool, not a mental-health or therapy service. If you are experiencing a crisis, please contact local emergency services or an appropriate helpline (e.g., **024** in Spain; **112** across the EU; **988** in the US).

## Changes to this policy

Material changes will be reflected in the "Last updated" date above and, where required by law, communicated inside the app.

--

Contact: **vendrell.dev@gmail.com** · Developer: [@davencode-dev](https://github.com/davencode-dev), Spain.
