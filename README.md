# Gemachte Bilder – Narrative eines Ortes

An interactive media literacy tool exploring how Berlin's Kottbusser Tor is framed in German news coverage. Built for the **Transferale 2026**.

→ [Live Demo](https://sonnenmaschine.github.io/Kottiquiz/)

---

## What it does

The tool consists of three interactive formats, designed to run on a tablet at an exhibition stand:

**Format 1 – Which headline is real?**
Five pairs of headlines. One is genuine, one is either invented or sourced from coverage of a different location with the place name swapped. The goal: show that sensationalist framing follows predictable patterns – and that those patterns travel across cities and outlets.

**Format 2 – How do you describe Kotti?**
Two steps: first, select words you personally associate with the Kottbusser Tor. Then, select which words you expect to find in media coverage. The comparison reveals the gap between lived experience and media image.

**Format 3 – Sort the narratives**
Four recurring media narratives about Kotti, sorted by the participant from most to least frequent in news coverage. After submitting, the tool reveals the actual distribution based on a corpus analysis of 40 articles.

---

## Research context

This tool was developed as part of a seminar paper on media framing and urban space at HTW Berlin, supervised by Prof. Daniela Hensel.

The analysis is based on a corpus of 40 articles published between 2024 and 2025 across five outlets: RBB, Tagesspiegel, Berliner Zeitung, Berliner Morgenpost, and BZ. Articles were coded for dominant frame, language patterns, quoted sources, and narrative type.

The categorisation of terms (e.g. which words are typical of tabloid vs. local coverage) reflects analytical decisions made in the coding process and should be read as interpretive, not exhaustive.

A full discussion of methodology, sources, and limitations will published by the accompanying seminar paper later this year.

---

## Technical notes

- Single HTML file, no dependencies, no build step
- Runs entirely in the browser
- Response data is stored in `localStorage` on the device – nothing is sent to a server
- An admin view (accessible via a link at the bottom of the start screen) shows aggregated results per format and allows CSV export
- Designed for tablet use (768px+), also works on desktop

---

## Design

The interface uses a brutalist aesthetic with high-contrast black and white, no rounded corners, and uppercase typography. Colour is used semantically only (KERN UX design system colour tokens for success/error states).

---

## Limitations and intended use

This tool is designed for a specific exhibition context – a research fair with a short dwell time per visitor. It simplifies deliberately. The framing categories used in Format 2, the percentage distributions in Format 3, and the source attributions in Format 1 are grounded in the corpus analysis but are not statistically representative.

For a more complete picture, please refer to the upcoming seminar paper.

---

## Contact

Thomas Reimer

HTW Berlin / Public Design

thomas.reimer@student.htw-berlin.de
