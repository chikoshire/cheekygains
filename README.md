# CheekyGains

**Human performance platform — standards, progression, coaching, and community.**

CheekyGains is a native fitness product in the **All Purpose** consumer ecosystem: structured training, follow-along flows, AI coaching (Naira), HealthKit-aware tracking, and a design system built for serious progression — not generic workout spam.

> Part of [All Purpose](https://chikoshire.com) · Mustard Seed Group

---

## The idea

Most fitness apps optimise for content volume. CheekyGains optimises for **standards and progression**.

- Clear levels (Novice → Elite thinking)  
- Workouts that respect modality (strength logger vs jump-rope / stretch follow-along)  
- Coaching that feels continuous — **Naira**, the AI performance coach  
- Native iOS as the source of truth for the athlete experience  

```text
Train → Log / Follow-along → Recap → Progress → Coach → Share / Community
```

## Product pillars

| Pillar | What you get |
| --- | --- |
| **Workout engine** | Strength sessions, follow-along cardio/mobility, modality-correct UX |
| **Progression** | Level-aware routines and exercise library quality |
| **Naira** | AI performance coach inside the CheekyGains experience |
| **Health surface** | HealthKit-aware sync and recovery-aware product thinking |
| **Design system** | All Purpose visual language — typography, motion, studio tooling |
| **Growth loops** | Invite / waitlist and seasonal mechanics (product roadmap) |

## Experience highlights

- **Native SwiftUI iOS app** — athlete experience lives on-device first  
- **Follow-along flows** for modalities that should not use a strength logger  
- **Recaps & history** that close the loop after a session  
- **Exercise library** curated for disambiguation and quality (hundreds of movements)  
- **Admin / Design Studio** web surfaces for content and system tooling  
- **Audio coaching** paths for guided sessions  

## Architecture (public)

```text
┌──────────────────┐     ┌──────────────────┐     ┌──────────────────┐
│  CheekyGains iOS │────▶│  Auth / Sync /   │────▶│  Content &       │
│  (SwiftUI)       │     │  Backend         │     │  Coaching layer  │
└────────┬─────────┘     └──────────────────┘     └────────┬─────────┘
         │                                                  │
         ▼                                                  ▼
   HealthKit / device                              Naira (coach)
   sensors & history                               + Design Studio
```

## Who it is for

Athletes and ambitious beginners who want:

- Clear standards instead of endless random WODs  
- A coach that remembers context  
- A product that feels premium and native  

## Ecosystem

CheekyGains sits inside **All Purpose** alongside media and consumer surfaces (Relay, Horizon, Made It Out, All Purpose Music, and more). Research on coaching systems also connects to Benediction Lab’s **Infinite Coach** investigations.

## What is public vs private

| Public | Private |
| --- | --- |
| This product showcase | iOS / backend source |
| Product narrative & maps | Exercise media binaries & internal CMS |
| High-level architecture | Model prompts, coach memory, user data |

## Status

In active production hardening — native workout flows, recaps, HealthKit, auth, audio, and Design Studio tracked toward release-quality builds (including TestFlight).

## Links

- **Founder / ecosystem:** [chikoshire.com](https://chikoshire.com)  
- **Org:** [mustardseedgroup](https://github.com/mustardseedgroup)  
- **Research:** [benedictionlab.com](https://benedictionlab.com)

---

<sub>Showcase repository — source code is private by design.</sub>
