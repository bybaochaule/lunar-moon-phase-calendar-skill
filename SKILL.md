---
name: lunar-moon-phase-calendar
description: Use when the user asks for a monthly lunar calendar, the moon phase for a specific date, upcoming new/full/quarter moons, or moon-aware planning notes. Default to the user's local timezone unless they specify a different one.
---

# Lunar Moon Phase Calendar

## When To Use

Use this skill when the request is about any of the following:

- generating a monthly lunar calendar
- looking up the moon phase for a specific date
- listing upcoming new moon, full moon, first quarter, or last quarter dates
- adding moon-aware notes for planning, observing, gardening, photography, rituals, or events

Do not use this skill for astrology, horoscope interpretation, or unsupported claims about guaranteed outcomes from moon phases.

## Core Rules

1. Default to the user's local timezone unless the user gives a different timezone.
2. If the user asks for a month view and does not specify a month, ask for the month and year.
3. If the user asks for a specific date lookup and the date is ambiguous, clarify only the missing date details needed to answer.
4. When exact phase timing matters, use reliable astronomical information. If you cannot verify exact timing, say so and present the answer as approximate rather than pretending precision.
5. Keep the answer practical. Include moon-related planning notes only when they add clear value.

## Request Handling

### 1. Monthly lunar calendar

When asked for a monthly lunar calendar:

- identify the target month, year, and timezone
- generate a detailed table covering the month
- highlight the major phase milestones: new moon, first quarter, full moon, and last quarter
- add brief planning notes when useful, such as strong nights for moon viewing, darker skies around new moon, or bright moonlight around full moon

Default output:

| Date | Day | Moon phase | Illumination | Notes |
| --- | --- | --- | --- | --- |
| 2026-01-01 | Thu | Waxing crescent | Approx. 8% | Early-evening crescent visibility |

Use approximate illumination only when it is grounded well enough to be helpful. If exact illumination is not reliable, omit the percentage instead of inventing it.

### 2. Specific-date moon phase lookup

When asked for the phase on a specific date:

- answer with the date in the user's timezone
- name the phase clearly
- include a short explanation of whether the moon is waxing or waning when useful
- mention if the answer may differ by timezone when the phase changes near that date boundary

Default shape:

- Date
- Timezone used
- Moon phase
- Optional short note

### 3. Upcoming major moon phases

When asked for upcoming major phases:

- list the next relevant new moon, first quarter, full moon, and last quarter dates unless the user asks for only one type
- order the list chronologically
- use the requested timezone or the user's local timezone by default
- include short planning notes only when useful

Default table:

| Date | Phase | Timezone | Note |
| --- | --- | --- | --- |

### 4. Moon-aware planning notes

When the user wants planning or event notes:

- keep the notes tied to observable conditions such as darker skies, brighter nights, or the visibility of a crescent or gibbous moon
- avoid mystical certainty or outcome guarantees
- tailor the notes to the user's stated activity when one is provided

## Output Quality Bar

- Prefer a detailed table with dates and phases by default.
- Be explicit about the timezone used.
- Use concise, factual language.
- If exact astronomical timing is not verified, say the timing is approximate.
- Do not fabricate exact timestamps, illumination percentages, or eclipse details.

## Example Request Shapes

- `Create a lunar calendar for October 2026.`
- `What will the moon phase be on March 14, 2027?`
- `List the next four major moon phases in my timezone.`
- `Make a moon phase calendar for next month and add notes for night-sky photography.`
