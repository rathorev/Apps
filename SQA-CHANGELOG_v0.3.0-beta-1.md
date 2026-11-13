# Smart Quiz Studio: Changelog

Versioning follows semantic versioning (`MAJOR.MINOR.PATCH`) with a `0.x` beta phase before the first stable `1.0.0` release.
Dates are in 2026.

## [0.3.0-beta-1] · 13 Nov
Feature-complete beta. Collecting feedback before 1.0.

### Added
- Notes & Comments panel with categories (Progress, Idea, Needs focus, Bank feedback). It is scrollable, expandable, filterable and saved with progress.
- Per-question comments, editable in the Question Overview table and in the quiz window.
- Drag-and-drop import for CSV question banks and JSON progress files (drop anywhere on the page).
- Export Question Overview as CSV with status, attempts, mastery %, Marked/Important flags and comments. Respects the active search and filters.

### Changed
- Side panel reorganised into collapsible sections (Setup, Question Bank & Progress, Notes, About). It stays in view on wide screens.
- Question Bank and Progress merged into one card. Start/Resume/Reset buttons moved to the top of Quiz Setup.
- Scrollbars hidden for a cleaner look. Scrolling still works by wheel, touch and keyboard.
- Version renumbered from 1.2 to the 0.x beta scheme.

### Fixed
- Horizontal overflow on phone-width screens.

## [0.2.0] · 12 Nov
### Added
- Load progress with Replace or Append (adds new questions, merges stats and flags).
- ⚑ Mark and ⭐ Important flags (Practice mode), visible and filterable in the Question Overview table.
- Practice only marked and important questions from the dashboard or after a session.
- Export important questions to CSV.

## [0.1.0] · 10 Nov
First build.
- Practice and Exam modes; Enforce Learning re-queue; hints; Tips & Traps feedback panel.
- Question types MC, MS, TF, FB; CSV import/export with validation and Replace/Append.
- 20 built-in questions; Question Overview table with stats; Save/Resume Progress; LocalStorage.
- Topics loaded from CSV; version display; phone and tablet layout.

## Known limitations (0.3.0-beta-1)
- Important and Marked flags and comments are stored in progress files, not in the question-bank CSV. The table export includes them but they are not restored when that file is re-imported.
- No keyboard shortcuts besides Enter to check a typed answer.
- No dark theme.

## Planned before 1.0
- Stability pass from real study sessions; fix anything found.
- Decide the final shape of the saved-progress file format and keep older files loadable.
