---
title: Sub-Processors
summary: The third parties Mote uses to deliver the service, including every AI provider and the feature each one powers; mirrors support.mote.com articles 97 (sub-processors) and 655 (AI providers).
type: facts
domain: trust
last-reviewed: 2026-09-29
review-interval: 90d
sources:
  - https://support.mote.com/article/97-who-do-you-share-my-data-with (canonical sub-processor list, updated 2026-09-16)
  - https://support.mote.com/article/655-what-ai-services-does-mote-use-and-who-provides-them (AI services and providers, customer-facing)
  - https://www.mote.com/privacy
---

# Sub-Processors

The third parties Mote uses to deliver the service. **The authoritative,
maintained list is published at
[support.mote.com article 97](https://support.mote.com/article/97-who-do-you-share-my-data-with)**; that is the source of truth, and
[article 655](https://support.mote.com/article/655-what-ai-services-does-mote-use-and-who-provides-them) explains which AI provider powers which feature.

If this file and article 97 disagree, article 97 wins. Do not quote a provider
externally without checking it is still listed there.

## Named sub-processors

Mirrors article 97 as updated 2026-09-16 (24 providers).

| Sub-processor | Purpose |
|---|---|
| **Amazon Web Services** | Cloud infrastructure for audio processing, user management and general operations; speech synthesis for selected languages; hosts language models reached through OpenRouter (Amazon Bedrock) |
| **Google Cloud Platform** | Cloud transcription, translation, speech synthesis, image text recognition and data analytics; language models for writing review |
| **Microsoft** | Audio transcription, speech synthesis, language detection, cloud infrastructure and data analytics; hosts language models reached through OpenRouter |
| **Deepgram** | Voice to text transcription |
| **AssemblyAI** | Voice to text transcription |
| **ElevenLabs** | Speech synthesis for selected voices |
| **OpenRouter** | Routes requests to language model providers for text prediction, dictionary, vocabulary and writing review features |
| **OpenAI** | Language models for text prediction, dictionary and vocabulary features, and image text recognition |
| **Anthropic** | Language models for dictionary, vocabulary and writing review features |
| **Cerebras** | Language models for vocabulary lists, Sentence Star and text prediction, reached through OpenRouter |
| **Vercel** | Web and application hosting |
| **Chargebee** | Billing and subscriptions for paying customers |
| **Stripe** | Subscription payment processing |
| **Customer.io** | Customer lifecycle and product update emails |
| **Help Scout** | Customer support and help site |
| **Pipedrive** | Tracking sales and customer success engagements |
| **Zapier** | Sales and operations automation |
| **PostHog** | Website and extension usage analytics |
| **Google Analytics** | Website and app usage analytics |
| **Supabase** | Data analytics, anonymized data only |
| **Datadog** | Outage and failure tracking |
| **Sentry** | Outage and failure tracking |
| **Airtable** | Storing and reviewing user survey data |
| **Typeform** | Capturing user survey data |

## AI providers by feature

Mote's AI usage splits into two kinds, and the distinction matters in
procurement and privacy conversations. Keep them separate: conflating them
invites the assumption that student writing is being fed to a general-purpose
chatbot. This section mirrors [article 655](https://support.mote.com/article/655-what-ai-services-does-mote-use-and-who-provides-them).

### Speech and language services (not generative)

Specialized services that convert between speech, text and languages. They do
not produce new content. Where several providers are listed, each request goes
to the primary provider and falls back automatically if it is unavailable or
does not support the requested language.

| Service | Providers |
|---|---|
| Speech to text | Deepgram (primary), AssemblyAI, Microsoft Azure, Google Cloud |
| Text to speech | Microsoft Azure (primary, and the source of Mote's voice catalog), Google Cloud, Amazon Web Services, ElevenLabs |
| Translation | Google Cloud |

### Generative AI features

Large language models performing specific, bounded tasks. Mote is **not** a
general-purpose content generator and has no "write this for me" feature; see
[positioning.md](../brand/positioning.md), What Mote IS NOT.

| Feature | Providers |
|---|---|
| Dictionary | OpenRouter, routing to OpenAI and Anthropic models hosted by Microsoft Azure and Amazon Bedrock |
| Vocabulary lists | OpenRouter, routing to Cerebras or Amazon Bedrock, with OpenAI as fallback |
| Sentence Star | OpenRouter, routing to Cerebras or Amazon Bedrock |
| Writing Review | OpenRouter, routing to Google, with Anthropic as fallback |
| Reading text from images | Built-in local OCR in the Chrome Extension, falling back to Google, then OpenAI |

**OpenRouter is a routing layer.** Mote sends the request to OpenRouter, which
passes it to the model provider chosen for that feature, so Mote can change or
fall back between models without changing the product. Mote requires OpenRouter
to use only providers with a zero data retention policy.

**Model names change; providers are the stable answer.** Specific models are
swapped as better options ship. When answering a customer, name the provider,
not the model.

## Answering customer questions about AI

Point customers to [article 655](https://support.mote.com/article/655-what-ai-services-does-mote-use-and-who-provides-them), which covers this ground in
customer-facing language and links back to article 97.

Do **not** assert that providers do or do not train on Mote data. That is a
contractual question, is not answerable from the code, and is the most common
follow-up. Route it to support@mote.com.

## Related

- [privacy.md](./privacy.md): what's collected and what's shared.
- [data-handling.md](./data-handling.md): how Mote uses data.
- [compliance.md](./compliance.md): Mote's overall compliance posture.
