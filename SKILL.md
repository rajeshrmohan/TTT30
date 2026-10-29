---
name: powerpoint-slide-builder
description: Creates clear, well-structured PowerPoint (.pptx) presentations from information the user provides. Use when the user asks for slides, a slide deck, a presentation, or a pitch deck, or wants notes, a document, or an outline turned into slides.
---

# PowerPoint Slide Builder

## Purpose
Turn the information the user gives (topic, notes, pasted text, documents, data) into a professional, easy-to-read PowerPoint deck that the user can present with minimal editing.

## When to use this skill
- The user asks for "slides", "a deck", "a presentation", or "a PowerPoint".
- The user supplies content (text, a file, a report, bullet points) and wants it converted to slides.
- The user wants to restructure or shorten an existing deck.

Do not use this skill for Word documents, spreadsheets, or PDFs.

## Step 1: Gather inputs
Before building, identify the following. Use what the user already provided; only ask about what is missing and essential. Ask all questions in a single message, and if the user does not answer, proceed with sensible defaults and state them.

| Input | Default if not given |
|---|---|
| Topic and key message | Required, ask if missing |
| Audience (e.g. students, management, clients) | General professional audience |
| Purpose (inform, teach, persuade, report) | Inform |
| Length / number of slides | 8 to 12 content slides |
| Presentation time | Roughly 1 to 2 minutes per slide |
| Tone (formal, friendly, technical) | Professional and clear |
| Source material | Only the user's supplied content |
| Branding (template, colours, logo, fonts) | Clean neutral theme, one accent colour |
| Speaker notes wanted? | Yes |

## Step 2: Plan before building
1. Write a one-sentence core message for the whole deck.
2. Draft a slide-by-slide outline (title + one-line purpose for each slide).
3. Show the outline to the user and ask for approval only if the deck is long (over 15 slides) or the request was ambiguous. Otherwise, proceed directly to building.

## Step 3: Standard deck structure
Adapt as needed, but follow this flow by default:

1. **Title slide**: deck title, subtitle or purpose, presenter name, date.
2. **Agenda / overview**: 3 to 5 items (skip for decks under 6 slides).
3. **Body slides**: one idea per slide, grouped into logical sections. Use section divider slides for decks over 12 slides.
4. **Summary / key takeaways**: 3 to 5 points.
5. **Next steps / call to action** (when relevant).
6. **Questions / contact** or **References** (when sources are used).

## Step 4: Slide content rules
- **One idea per slide.** The slide title should state the point, not just the topic (e.g. "Sales grew 18% in Q3" rather than "Sales").
- **Maximum 5 bullets per slide, maximum about 12 words per bullet.** Use fragments, not paragraphs.
- **No walls of text.** If content is long, split it across slides or move detail into speaker notes.
- **Prefer visuals over bullets** where possible: tables for comparisons, charts for numbers, diagrams or flows for processes, icons or images for concepts.
- **Charts:** use native PowerPoint charts with a clear title, labelled axes, and the key insight in the slide title. Do not invent data.
- **Tables:** maximum 5 columns and 6 rows per slide. Highlight the key figure.
- **Consistency:** same fonts, sizes, alignment, and colour usage on every slide. Use the template's slide layouts and placeholders rather than free-floating text boxes.
- **Parallel wording:** bullets in a list share the same grammatical form.

## Step 5: Design rules
- Use a clean layout with generous white space and consistent margins.
- Fonts: one sans-serif family (e.g. Calibri, Segoe UI, Arial). Titles 28 to 36 pt, body 18 to 24 pt, never below 16 pt.
- Colours: one primary colour plus one accent. Ensure strong contrast between text and background (dark text on light, or light text on dark).
- Do not rely on colour alone to convey meaning.
- Images: relevant, high quality, never stretched. Add alt text to every image, chart, and diagram.
- Avoid decorative clip art, heavy animations, and slide transitions beyond a simple fade.
- If the user supplies a template or brand guide, follow it exactly.

## Step 6: Speaker notes
For each content slide, add speaker notes of 2 to 5 sentences containing:
- What to say to expand on the slide.
- Any supporting detail, example, or statistic that does not fit on the slide.
- A transition sentence to the next slide.

## Step 7: Accuracy and sourcing
- Use only information the user provided or that can be cited from reliable sources. Never fabricate statistics, quotes, names, or dates.
- If a fact or figure is missing, insert a clearly marked placeholder such as **[INSERT: Q3 revenue figure]** and list all placeholders at the end of your reply.
- Add source citations in small text at the bottom of slides that contain data, or on a final References slide.

## Step 8: Quality check before delivering
Confirm every item:
- [ ] Slide count and flow match the request.
- [ ] Every slide has a clear title and a single main idea.
- [ ] No slide has more than 5 bullets or any text overflow.
- [ ] Fonts, colours, and alignment are consistent.
- [ ] Text meets minimum size and contrast.
- [ ] Charts and tables are accurate and labelled.
- [ ] Speaker notes are present on content slides.
- [ ] Alt text is added to visuals.
- [ ] No spelling errors; consistent spelling variant (e.g. British or American) throughout.
- [ ] Placeholders and assumptions are listed.

## Step 9: Output and response format
1. Deliver the finished `.pptx` file.
2. In the chat reply, include only:
   - A 3 to 6 line summary of the deck (slide count, structure, theme used).
   - Any assumptions made (audience, length, tone, branding).
   - Any placeholders the user still needs to fill in.
   - One suggested next step (e.g. "Want a shorter 5-minute version?").
3. Do not paste the entire slide text into chat unless asked.

## Handling edits
When the user asks for changes, modify the existing deck rather than rebuilding it. Preserve formatting and untouched slides. Typical requests: shorten, change tone, add or remove a slide, reorder, restyle, translate, or convert to speaker-friendly handouts.

## Example prompts the user may give
- "Create a 10-slide deck on cybersecurity basics for first-year students. Use the notes below."
- "Turn this report into a 6-slide executive summary for senior management."
- "Make a 5-minute pitch deck for our project. Audience: funding committee. Include a timeline and budget table."
- "Convert this outline into slides with speaker notes, using our blue school template."

## Default behaviour summary
If the user gives only a topic, build an 8 to 10 slide deck with the standard structure, a neutral professional theme, and speaker notes. State the assumptions you made, and invite the user to refine audience, length, and branding.
