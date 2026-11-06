<p align="center"><img src="docs/assets/housejet-logo.png" alt="HouseJet" width="320"></p>

# Vibe Editing for Agents

**Turn one 30-minute recording into a week of finished, on-brand real estate clips, edited by AI on your own Mac.**

You talk to it in plain English through the Claude Code app. No editing software, no timeline, no terminal.

## Set it up (about 15 minutes)

1. Download the **Claude Code** app from [claude.com/claude-code](https://claude.com/claude-code) and sign in (paid Claude plan: Pro or Max).
2. Start a new chat and paste this:

```
Set up HouseJet Vibe Editing for me on this Mac. I'm a real estate agent and I'm not technical,
so do everything yourself and explain each step in plain English.
Clone https://github.com/clay624/housejet-vibe-editing.git into my Documents folder,
then follow its CLAUDE.md, HOUSEJET.md and ONBOARDING.md. Ask me one question at a time,
and finish by making me a test clip.
```

3. Answer its questions. It walks you through your brokerage, market, logo and the accounts the editor needs, then makes a test clip.

## What you'll need

| | |
|---|---|
| A Mac | Your footage stays on your computer, except audio sent to the transcription services below |
| Claude Code app | Paid Claude plan (Pro or Max) |
| AssemblyAI account | Transcription. Billed by usage on your own account |
| Google AI Studio (Gemini) key | Listens to the audio to find the best moments |
| Groq key | Backup transcription and checks |

The kit walks you through each sign-up. Check each provider's pricing page for current rates.

## Once it's running

| Say this | What happens |
|---|---|
| "make clips from this" | Drop in a video or link. Finished vertical clips land in `20_DELIVER/` |
| "mine highlights from this" | Turns a buyer Q&A or market update into longer YouTube videos |
| "make the captions bigger" | Change captions, cuts, logo or music in plain English |

## Real estate rules built in

Every clip follows [`HOUSEJET.md`](HOUSEJET.md): Fair Housing checks, your brokerage name on every clip, no prices or stats you didn't say on camera, and only media you have rights to. You're still the one posting, so watch every clip before it goes up.

## Credits

Built by HouseJet on the open-source [vibe-editing](https://github.com/maddexritter-rgb/vibe-editing) kit (MIT License). See [`NOTICE.md`](NOTICE.md).
