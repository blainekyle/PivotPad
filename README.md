# PivotPad

[![Live App](https://img.shields.io/badge/Live_App-GitHub_Pages-3b82f6?style=flat-square&logo=github)](https://blainekyle.github.io/PivotPad/)
[![Version](https://img.shields.io/badge/Version-1.9.0-10b981?style=flat-square)](https://blainekyle.github.io/PivotPad/)

**Fast, zero-dependency bidirectional list ↔ delimited-text (CSV) pivot pad.**

Launch in browser: **[blainekyle.github.io/PivotPad](https://blainekyle.github.io/PivotPad/)**

---

## Overview

**PivotPad** turns newline-separated vertical lists (ticket numbers, asset IDs, hostnames, emails, SQL `IN (...)` values) into copy-ready delimited strings — and unpacks delimited strings right back into clean one-item-per-line lists in real time.

## Key Features

- **Bidirectional Real-Time Sync**:
  - Type or paste into **List View (One per line)** on the left to immediately format **Delimited View (CSV)** on the right.
  - Edit or paste any delimited string into **Delimited View** on the right to immediately pivot it back into a vertical list on the left.
- **Custom Multi-Character Delimiters**: Replace the default `,` delimiter with any separator up to 5 characters (e.g. `, `, `;`, ` | `, or `', '` when pasting inside a surrounding `IN ('...')` clause) with automatic regex escaping on reverse splits.
- **Blank Line Filtering**: Toggle **Omit blank lines** to strip empty rows and trailing whitespace entries in both directions.
- **One-Click Copy**: Instant clipboard export with visual confirmation feedback.
- **Classic Mode**: Includes a footer toggle to switch anytime to [**Pivot Pad Classic**](https://blainekyle.github.io/PivotPad/ppclassic.html).
- **100% Client-Side**: Pure standalone HTML/CSS/JS with zero external dependencies, tracking, or network requests.

## Running Locally

Clone the repository and open `index.html` directly in any browser:

```bash
git clone https://github.com/blainekyle/PivotPad.git
```
