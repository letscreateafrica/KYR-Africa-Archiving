# KnowYourRights Africa — Archive

The public [KnowYourRights Africa Site](https://african-diaspora-brief.letscreateafrica.chatgpt.site/) publishes dated visual newsletters, full briefs, policy alerts and two-day digests. Its [historical U.S. Immigrant Brief tracker records](https://african-diaspora-brief.letscreateafrica.chatgpt.site/tracker/) are retrospective generated text, not freshly verified news.

Published Site version 27 corresponds to Sites source commit `2c59143d9ce74a49f7500fb30f80720aec4054c8`. The [October 20 full brief](https://african-diaspora-brief.letscreateafrica.chatgpt.site/briefs/2026-10-20.html) and [visual newsletter](https://african-diaspora-brief.letscreateafrica.chatgpt.site/newsletter/2026-10-20/) are the latest published issue. The homepage archive guide searches dated entries locally and links their evidence. Community reach starts with a labelled 200 launch baseline and adds recorded homepage opens; it does not count unique people.

Download the [sanitized source and static build](KYR-Africa-Archiving-source.zip) and the [original editorial composition inputs](KYR-Africa-Archiving-source-art.zip). Extract both archives into the same directory to restore `artwork/source-art/`. The source archive omits Git history and the Site identity manifest in `.openai`; it includes `dist/`, the aggregate counter function source in `backend/`, and `ARCHIVE-RECONSTRUCTION.md`. The live counter uses a separate Supabase project and its deployed Edge Function; no credentials are included here.

Run `node build.mjs` and `node serve.mjs` (Node 18+) after restoring the artwork inputs. Follow `EDITORIAL-WORKFLOW.md` before publishing changes. The site displays general information, not individual legal advice.
