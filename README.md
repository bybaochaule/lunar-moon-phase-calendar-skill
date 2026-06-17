# Lunar Moon Phase Calendar Skill

A Codex/ChatGPT agent skill for generating lunar calendars, looking up moon phases for specific dates, listing upcoming major moon phases, and adding practical moon-aware planning notes.

This skill is designed for factual lunar phase guidance. It focuses on observable conditions such as dark skies near the new moon, brighter nights near the full moon, and useful visibility notes for planning.

## What It Can Do

- Generate a monthly lunar calendar
- Look up the moon phase for a specific date
- List upcoming new moons, first quarters, full moons, and last quarters
- Add practical planning notes for skywatching, photography, gardening, rituals, events, or other moon-aware activities
- Use the user's local timezone by default unless another timezone is provided

## What It Does Not Do

- It does not provide astrology or horoscope readings
- It does not make guaranteed outcome claims based on moon phases
- It does not invent exact timestamps, illumination percentages, or eclipse details
- If exact astronomical timing cannot be verified, it should clearly say the result is approximate

## Example Prompts

Create a lunar calendar for October 2026.

What will the moon phase be on March 14, 2027?

List the next four major moon phases in my timezone.

Make a moon phase calendar for next month and add notes for night-sky photography.

## Default Behavior

When a user asks for a monthly lunar calendar, the skill should return a table with:

- Date
- Day of week
- Moon phase
- Illumination, when reliable enough to include
- Brief practical notes, when useful

It should also highlight the major phase milestones for the month:

- New moon
- First quarter
- Full moon
- Last quarter

When a user asks about a specific date, the skill should return:

- The date used
- The timezone used
- The moon phase
- A short note about waxing or waning, when useful

## Recommended Repository Structure

lunar-moon-phase-calendar-skill/
  README.md
  SKILL.md
  agents/
    openai.yaml
  examples/
    AGENTS.md

## Safety Notes

This skill should keep moon guidance practical and factual. It may discuss darker skies, brighter nights, moon visibility, and approximate planning windows. It should not present spiritual, astrological, or ritual outcomes as facts.

When exact timing matters, the agent should verify against reliable astronomical sources. If timing cannot be verified, the answer should say that clearly.
