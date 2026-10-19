# Doris — Vapi Configuration

## 1. Assistant Identity

| Setting | Value |
|---|---|
| Assistant name | Doris |
| Voice provider | Vapi |
| Voice ID | Layla |
| AI provider | OpenAI |
| AI model | GPT-4.1 mini |

## 2. Speech Configuration

| Setting | Value |
|---|---|
| Transcription provider | ElevenLabs |
| Transcription model | Scribe v1 |
| Transcription language | English |
| Background denoising | Enabled |
| Automatic transcription fallback | Enabled |

## 3. Call Messages

**Initial message**

> Hi, this is Doris from Project AI - is now a good time to talk about your business needs?

**Voicemail message**

> Please call back when you're available.

**End-of-call message**

> Goodbye.

## 4. Voicemail Detection

The exported configuration specifies Vapi voicemail detection with the following retry settings:

- Maximum retries: 6
- Initial delay: 5 seconds
- Retry frequency: 5 seconds
- Maximum wait for voicemail beep: 0 seconds

These are configuration values, not evidence of successful voicemail detection in a live call.

## 5. Analysis Settings

| Setting | Status |
|---|---|
| Call summary generation | Disabled |
| Success evaluation | Disabled |

The configuration does not establish that call summaries or proposal decisions are automatically stored or evaluated.

## 6. Configuration Limitations

The supplied configuration confirms the assistant's voice, model, transcription, initial call messages, and voicemail settings.

It does not confirm:

- An automatic email-sending integration.
- CRM or lead-record synchronization.
- Automated proposal generation.
- Live call performance or end-to-end testing.

The assistant's system prompt instructs Doris to confirm whether the lead wants a proposal by email. The actual delivery of that proposal remains unverified.

## 7. Security and Privacy

This document intentionally excludes organization IDs, assistant IDs, credentials, and customer information from the exported configuration.

Do not commit API keys, private call recordings, customer phone numbers, or personal lead information to the public repository.
