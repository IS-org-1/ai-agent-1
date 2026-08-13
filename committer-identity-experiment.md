# Committer Identity Experiment

Tracking how GitHub resolves commit author/committer across changes.

## Step 1 — GitHub email set to private
- git user.name: ievgencoderoi1-ai
- git user.email: (unchanged at commit time; user manages email)
- Expectation: committer resolves to the account (PASS) as long as the
  commit email maps to a GitHub account.

## Step 1b - email now noreply
- git user.email: 290055406+ievgencoderoi1-ai@users.noreply.github.com

## Step 1c - username-only noreply
- git user.email: ievgencoderoi1-ai@users.noreply.github.com

## Step 2 - changed user.name
- git user.name: ievgencoderoi1-ai-new
- git user.email: ievgencoderoi1-ai@users.noreply.github.com (unchanged)
