---
name: moon-phase-calendar-builder
description: Use this when the user wants to create, verify, format, or improve a lunar moon phase calendar, especially for printable planners, astrology planning, gardening calendars, classroom handouts, journaling pages, wellness planning, content calendars, CSV files, PDFs, or .ics calendar imports. Do not use for unrelated astronomy tutoring, horoscope predictions, medical claims, legal deadlines, or calendars that require unverified dates. Produces a source-checked moon phase calendar package.
---

# Moon Phase Calendar Builder

## Purpose

Create professional lunar moon phase calendars, moon phase tables, monthly planning layouts, export-ready calendar outlines, and quality-control checks for users who need clear lunar planning materials.

This skill helps planners, teachers, astrology creators, gardeners, journal makers, wellness creators, digital product sellers, and personal users turn a year, timezone, location, and style brief into a practical moon phase calendar.

This skill provides calendar creation, formatting, verification, and planning support only. It does not guarantee astronomical authority, platform approval, sales, legal compliance, spiritual outcomes, health outcomes, planting success, business results, or any result outside the agent's control.

---

## When to Use This Skill

Use this skill when the user wants to:

* create a lunar moon phase calendar for a specific year, month, season, or date range
* make a printable monthly moon phase calendar
* generate a moon phase table with New Moon, First Quarter, Full Moon, and Last Quarter
* create a calendar for astrology, gardening, journaling, wellness, classroom, or content planning
* convert verified moon phase times into a user-selected timezone
* format a moon phase calendar as Markdown, table, CSV, PDF-ready text, HTML-ready text, or .ics-ready event specs
* improve an existing moon phase calendar for clarity, accuracy, layout, or buyer usability
* audit a lunar calendar for missing details, unclear timezone labels, weak formatting, or unsupported claims
* create product-page copy, usage notes, or setup instructions for a moon phase calendar product
* add optional lunar notes such as zodiac sign placeholders, full moon names, eclipse notes, supermoon notes, or planning prompts when source data is available

---

## When Not to Use This Skill

Do not use this skill for:

* unrelated general writing
* horoscope predictions presented as certain outcomes
* medical, mental health, fertility, legal, tax, financial, or safety advice
* claiming moon phases can guarantee health, wealth, relationships, crop yields, sales, manifestation results, or spiritual outcomes
* fake astronomical data, invented dates, or unverified event claims
* illegal activity
* plagiarism or copying paid calendar content without permission
* trademark misuse or unauthorized use of branded planner styles
* fake reviews, fake ratings, fake platform approval, or fake credentials
* bypassing platform rules
* exposing private or sensitive user data
* automated publishing, emailing, uploading, purchasing, or file overwriting without explicit user confirmation

If the user asks for unsupported claims, replace them with neutral planning language.

---

## Required Inputs

Collect or infer these details:

| Input | Required | Why It Matters | If Missing |
|---|---:|---|---|
| Calendar year or date range | Yes | Moon phase dates depend on the exact period | Ask for it if absent |
| Timezone or location | Yes | Phase date may shift by timezone | Ask for it if absent; default only if the user accepts a stated assumption |
| Output type | Yes | Determines formatting | Default to a readable Markdown calendar plus phase table |
| Included moon phases | No | Controls scope | Default to New Moon, First Quarter, Full Moon, Last Quarter |
| Audience/use case | No | Shapes notes and tone | Default to personal planning |
| Calendar style | No | Shapes layout | Default to clean, printable, practical |
| Week start | No | Matters for monthly grids | Default to Sunday for U.S. users, Monday for international users when known |
| Date/time format | No | Improves usability | Default to `Month Day, Year, h:mm AM/PM TZ` |
| Source preference | No | Improves trust | Use reliable astronomical or almanac sources where available |
| Export format | No | Determines artifact specs | Offer Markdown, CSV, PDF-ready, HTML-ready, or .ics-ready formats |
| Extra events | No | Adds value but requires verification | Include only when source data is available |
| Existing file/template | Sometimes | Needed for editing or audit requests | Ask for the file or proceed with text-only guidance |
| Branding or visual style | No | Useful for printables and marketplace products | Use a calm lunar aesthetic if missing |
| Accuracy tolerance | No | Determines verification depth | Default to source-matched primary phases, noting timezone conversion |

Do not produce a dated calendar if the year/date range and timezone are both missing. Ask only for those missing essentials.

---

## Workflow

Follow this process:

1. Validate fit  
   Confirm the user wants a moon phase calendar, table, planner, printable, audit, conversion, or export-ready calendar package.

2. Capture the calendar brief  
   Identify the year or date range, timezone/location, audience, output format, calendar style, included phases, extra events, and whether the user wants a downloadable artifact.

3. Resolve critical missing details  
   If the year/date range or timezone/location is missing, ask for the smallest missing detail. If the user requested a quick sample, clearly label any default assumptions.

4. Verify lunar data  
   Use reliable astronomical or almanac sources when producing real dated output. Prefer primary phase data from reputable sources such as observatories, government astronomy resources, established almanacs, or well-known time/date references.

5. Preserve source context  
   Record the source name, source timezone or UTC basis, retrieval date when relevant, and any conversion method used.

6. Convert timezone carefully  
   If the source data is in UTC or another timezone, convert it to the user's requested timezone. Watch for date changes when conversion crosses midnight.

7. Build the core phase table  
   Include phase name, local date, local time, timezone abbreviation, optional UTC time, and notes when useful.

8. Build the calendar layout  
   Choose the best structure for the requested output:
   * annual overview
   * monthly grid
   * monthly list
   * season-by-season calendar
   * printable planner pages
   * CSV event list
   * .ics-ready event specification
   * product-ready listing copy and instructions

9. Add user-specific notes  
   Add only relevant notes for the audience:
   * astrology: intention-setting prompts, zodiac placeholders, retrograde/eclipses only if verified
   * gardening: neutral biodynamic-style planning prompts without guaranteed results
   * classroom: vocabulary, observation activities, and discussion questions
   * journaling: reflection prompts
   * wellness: gentle routine prompts without medical claims
   * content planning: post ideas and reminder themes

10. Add quality checks  
   Check the count of phases, month coverage, date order, timezone label, duplicate events, missing phases, inconsistent formatting, and source notes.

11. Prepare exports when requested  
   For CSV or .ics, define exact field names and event formatting. For PDF-ready output, provide clean page sections and print notes. Use file tools only when available and explicitly requested.

12. Finalize with assumptions and verification notes  
   State the timezone, source basis, included phases, output format, and any limitations.

---

## Output Contract

Use this structure for most calendar creation requests:

1. **Calendar Summary**
   * Year or date range
   * Timezone/location
   * Included phases
   * Output format
   * Source/verification note

2. **Moon Phase Table**
   * Phase
   * Local date
   * Local time
   * Timezone
   * Optional notes

3. **Calendar Layout**
   * Annual, monthly, printable, CSV-ready, PDF-ready, or .ics-ready format based on the request

4. **Planning Notes**
   * Audience-specific prompts or usage notes when helpful

5. **Quality Checks**
   * Timezone confirmed
   * Dates sorted
   * Source checked
   * Missing phases reviewed
   * Export fields checked if applicable

6. **Limitations**
   * Mention that users should verify final dates before publication, sale, planting schedules, professional use, or time-sensitive use

For audit requests, use this structure:

1. Direct verdict
2. What works
3. Accuracy and timezone risks
4. Formatting and usability issues
5. Missing source or verification details
6. Priority fixes
7. Revised sample section
8. Final recommendation

For export requests, include the relevant contract:

### CSV Fields

```text
title,start_date,start_time,end_date,end_time,timezone,phase,notes,source
```

### .ics Event Fields

```text
SUMMARY
DTSTART
DTEND
TZID or UTC basis
DESCRIPTION
CATEGORIES
SOURCE NOTE
```

### Printable Layout Sections

```text
Cover title
Year overview
Monthly phase pages
Full moon highlight page
New moon planning page
Source and timezone note
Usage disclaimer
```

---

## Domain Rules

### Accuracy Rules

* Never invent moon phase dates or times.
* Do not mix source timezones without labeling them.
* Always state the timezone used.
* If converting from UTC, check whether the local date changes.
* If source data disagrees across sources, mention the discrepancy and use the more authoritative or better-documented source.
* Do not include eclipses, supermoons, blue moons, zodiac signs, lunar mansions, or full moon names unless the data is verified or clearly marked as a placeholder.
* Use "approximately" for times when the source does not provide exact minute-level data.
* Do not claim the calendar is official unless it comes directly from an official source and the source allows that characterization.

### Formatting Rules

* Keep calendars readable and uncluttered.
* Use consistent phase names:
  * New Moon
  * First Quarter
  * Full Moon
  * Last Quarter
* Include timezone abbreviation in every table or clearly in the section header.
* Use month names instead of ambiguous numeric-only dates unless the user requests numeric format.
* For international users, prefer ISO date format when useful: `YYYY-MM-DD`.
* For printables, keep notes concise and avoid dense paragraphs inside calendar cells.
* For .ics-ready output, avoid emojis in event titles unless the user requests them.
* For marketplace products, include a source/timezone note and a verification reminder.

### Audience Rules

* Astrology calendars may include reflective prompts, but must not guarantee outcomes.
* Gardening calendars may include tradition-based or planning prompts, but must not guarantee crop success.
* Wellness calendars may include gentle self-care prompts, but must not give medical advice.
* Classroom calendars should use educational language and avoid spiritual claims unless requested for cultural context.
* Digital product calendars should include buyer instructions, file-use notes, and a clear timezone disclaimer.

### Marketplace Safety Rules

* Do not claim guaranteed sales, rankings, virality, buyer demand, platform approval, or legal compliance.
* Do not claim the output is copyright-safe or trademark-safe.
* Do not copy paid almanac tables, copyrighted calendar layouts, or branded planner designs.
* Do not include fake reviews, badges, ratings, certifications, or endorsements.
* Use safer wording such as "source-checked," "printable-ready," "planning-friendly," and "designed for personal use."

---

## Tool Rules

Use tools only when they materially improve the result.

Recommended tool behavior:

```text
Research tools:
Use for real moon phase dates, current/future year calendars, eclipses, supermoons, blue moons, full moon names, or source verification.

Read/Edit:
Use when the user provides an existing calendar, PDF, CSV, Markdown file, .ics file, listing draft, or template to review or improve.

Bash:
Use only when generating or validating downloadable artifacts such as CSV, .ics, HTML, Markdown, or PDF-ready files.
```

Never invent tool results.

Require explicit confirmation before:

* overwriting files
* deleting files
* uploading files
* emailing calendar files
* publishing listings
* purchasing templates or data
* changing account settings
* exposing private data
* modifying important user files

---

## Resource Guidance

No bundled resources are required for the basic skill.

Optional useful resources:

```text
moon-phase-calendar-builder/
├── SKILL.md
└── optional resources/
    ├── scripts/
    │   ├── build_ics.py
    │   ├── build_csv.py
    │   └── validate_phase_table.py
    ├── references/
    │   └── trusted_lunar_data_sources.md
    └── assets/
        ├── printable_calendar_layout.md
        ├── csv_field_template.md
        └── ics_event_template.md
```

Use `scripts/` only for deterministic export helpers. Use `references/` for stable source guidance. Use `assets/` for reusable layout templates.

Do not bury large source tables inside `SKILL.md`. Keep the skill focused on behavior and verification.

---

## Failure Handling

### Missing Year or Date Range

Ask for the year or date range. Explain that moon phase dates cannot be produced accurately without it.

### Missing Timezone or Location

Ask for the timezone or location. Explain that the local date can change depending on timezone.

### No Research Tools Available

Do not invent dates. Provide a fillable template and tell the user what source data is needed.

### Conflicting Source Data

State the conflict, identify the sources, and recommend using the most authoritative or better-documented source. Avoid finalizing a dated calendar until the discrepancy is resolved.

### Ambiguous Output Format

Default to a Markdown phase table plus monthly calendar outline. Offer export-ready CSV or .ics structure if helpful.

### Too Broad

Narrow the task to one calendar product or propose separate deliverables:
* printable moon phase calendar
* astrology planner calendar
* gardening moon calendar
* classroom moon observation calendar
* .ics import calendar

### Unsafe or Unsupported Request

Refuse briefly and redirect to a safer planning-focused version.

### Tool Failure

Retry once if safe. If the tool still fails, provide a partial result, explain the blocker, and give a manual template or export specification.

### Quality Failure

Do not finalize. Revise until the calendar has complete dates, consistent timezone labels, sorted phases, and clear source notes.

---

## Final Answer Rules

When returning the final answer:

* provide the completed calendar package directly
* state the year/date range and timezone near the top
* state the source basis or verification status
* use clean Markdown unless another format is requested
* keep planning notes practical and non-guaranteed
* include assumptions only when useful
* include limitations when relevant
* do not invent dates, source names, source quotes, or astronomical events
* do not claim official status, guaranteed accuracy, guaranteed outcomes, or platform approval
* do not over-explain unless the user asks
