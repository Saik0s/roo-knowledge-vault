# Roo Knowledge Management System

<p align="center">
  <img src=".github/header.jpeg" alt="Roo Knowledge Management System">
</p>

This repository is adapted from a code-based "Memory Bank" into a knowledge-driven "Knowledge Bank." We maintain the same file structure (.clinerules-* and .roomodes) but reorient all processes toward capturing, organizing, analyzing, and retrieving knowledge.

## Key Principles

1. **Atomic Notes**: Each note captures a single idea or concept. References and links connect notes into a broader map of knowledge.
2. **PARA Method**: Organize content into:
   - **Projects**: Short-term efforts requiring multiple notes or tasks
   - **Areas**: Ongoing responsibilities or domains
   - **Resources**: Topics of interest or references
   - **Archives**: Inactive or past content
3. **Linking & Cross-Referencing**: Use consistent naming or tags to tie notes together. For instance, if a note references another, create a direct link or mention of that note.
4. **Scalability**: This system supports thousands of notes. To keep it agile:
   - Keep each note atomic
   - Use robust linking
   - Rely on curated categories (PARA or similar)
5. **Modes**:
   - **Architect**: Oversee structural organization, create or refine top-level categories
   - **Ask**: Retrieve quick answers, locate references
   - **Notes** (formerly “Code”): Create or edit note content
   - **Analysis** (formerly “Debug”): Correlate multiple notes to derive deeper insights
   - Additional modes in `.roomodes` (Collector, Organizer, Archivist) for specialized tasks.

## Basic Usage

1. **Initialize**: In Architect mode, set up the knowledge-bank/ directory if missing. Create top-level PARA folders or other categories.
2. **Collect**: In Collector mode, ingest new material (web highlights, meeting notes, etc.) as raw notes with minimal classification.
3. **Organize**: In Organizer mode, refine note tags, link them, place them in correct categories.
4. **Ask**: Query the knowledge system for specific facts, references, or short answers.
5. **Notes**: Rewrite or refine the text of existing notes, add or remove content, merge notes, etc.
6. **Analysis**: Dive deep into cross-topic insights or complicated research. Summarize or propose structural changes.

## Example Workflows

- **Add a New Resource**:
  1. Switch to “Collector” mode.
  2. Paste your new source or reference as a note.
  3. Switch to “Organizer” to add tags or links.
  4. If deeper discussion is needed, ask in “Analysis” or open a new note in “Notes.”

- **Rearrange Topics**:
  1. Start in “Architect” to confirm high-level structure changes are needed (e.g. new project or area).
  2. Switch to “Organizer” to rename categories, move notes, or unify tags.

- **Find Info**:
  1. Switch to “Ask” mode, ask your question.
  2. System will locate relevant notes. Possibly switch to “Analysis” if deeper correlation is required.

Enjoy your knowledge system and keep learning!
