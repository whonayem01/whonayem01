# Abdullah Al Nayem

Backend-focused software engineer shipping production Python, Django and AWS systems since 2021. Currently building and running an AI voice product solo, from architecture to live users. MSc Software Engineering, Kingston University London. Based in London, open to relocation, and always curious about new systems to break and then fix better.

## What I work with

**Languages:** Python, TypeScript, JavaScript, SQL  
**Backend:** Django, DRF, FastAPI, Celery, asyncio, WebSockets, REST API design, pytest  
**Data & messaging:** PostgreSQL, Redis, RabbitMQ, pgvector  
**Cloud & DevOps:** AWS (ECS, Lambda, RDS, S3, SQS), Docker, Terraform, GitHub Actions, Nginx, Sentry  
**AI engineering:** Claude and OpenAI APIs, structured outputs with Pydantic, evals, voice agents (ElevenLabs), RAG, prompt caching  
**Frontend:** React, Next.js, Zustand, React Query, Tailwind, Jest

## What I am building: Prepwise

An IELTS speaking practice app with AI examiners. You talk, it talks back, then it explains in detail how your grammar collapsed under pressure.

* Real time voice sessions over WebRTC, with multi-stage ElevenLabs voice agents running each structured, timed section
* Backend drives session state, tool dispatches and guarded transitions, so every exam runs the same from first question to final score
* Transcript scoring and feedback generated through the Claude API
* Eval suite that validates scores against official criteria and catches drift across prompt and model changes, within half a band of examiner marked samples in 84% of cases
* Django and DRF backend with Celery workers and Redis, running on AWS

[iOS](https://apps.apple.com/us/app/prepwise-ielts/id6761788714) · [Android](https://play.google.com/store/apps/details?id=com.blacknerdstudio.prepwise) · [Web](https://prepwise.nayem.one) · [Architecture notes](https://github.com/whonayem01/prepwise-architecture)

## Before this

* **Enosis Solutions.** LMS serving 50k users, pulled p95 from 800ms to 280ms with query tuning, Redis caching and Celery pipelines. Also migrated a Canadian fuel retail chain from VB.NET to Django and Next.js, rebuilding the pricing engine behind 500K price rows and cutting over all 180 stores.
* **LIILab.** Email marketing pipeline on AWS SES handling 40k+ sends a month, with campaign queuing, delivery tracking and retry logic.
* **MSc Software Engineering (Distinction)**, Kingston University London, 2025.
* **BSc Computer Science and Engineering**, Leading University, Bangladesh.

## Things I picked up along the way

* [AWS Certified Cloud Practitioner](https://www.credly.com/badges/3b29c2fe-90e4-43da-9231-8120b33c2954)
* IEEEXtreme 14.0 country champion, 129th globally
* 800+ problems solved on [Codeforces](https://codeforces.com/profile/blacknerd) (Specialist, max 1509) and [CodeChef](https://www.codechef.com/users/blacknerd) (max 4 star)

## Elsewhere

[nayem.one](https://nayem.one) · [LinkedIn](https://www.linkedin.com/in/whonayem01) · whonayem01@gmail.com

Happy to talk about Django, product decisions, or why the bug only shows up in production.
