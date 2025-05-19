# Repository Structure

## Organization Overview

This repository contains the planning and development materials for the "Imperial Cultivation: Rise of House Aurelius" novel series. The structure is designed to balance comprehensiveness with manageable organization.

## For Language Models (LLMs)

When making substantive changes to this repository, please follow these guidelines:

1. **Update the CHANGELOG.md file** with a summary of your changes
   - Add your changes under the "[Unreleased]" section
   - Group changes into "Added", "Changed", "Fixed", or "Removed" categories
   - Be specific about which files were modified and how
   - If your changes warrant a version update, create a new version section

2. **Maintain consistent formatting** across all documents
   - Use Markdown formatting consistently
   - Follow existing naming conventions for files and headers
   - Preserve the hierarchical structure of the repository

3. **Document complex reasoning** for major narrative or structural changes
   - Include brief explanations for significant plot or character modifications
   - Document any alternatives that were considered but not implemented

These guidelines ensure that changes are properly tracked and the repository remains well-organized as it evolves.

## Main Directories

### `/characters/`
Character profiles and development arcs.

- **`/main_characters/`** - Detailed profiles for protagonist and primary characters
  - Michael Aurelius, Victoria Laurent, Empress Elara, etc.

- **`/supporting_characters/`** - Profiles for secondary and tertiary characters
  - Seraphina, Reylan Vex, common-born team members, antagonists, etc.

- **`consolidated_character_arcs.md`** - Character development across the series

### `/worldbuilding/`
Detailed aspects of the story world.

- **`/magic_system/`** - Cultivation mechanics and magical elements
  - Runic core system, soul binding, progression mechanics

- **`/politics/`** - Political structures and social systems
  - Imperial Council, class hierarchy, factional relationships

- **`/locations/`** - Key settings and environments
  - Imperial Capital, Academy, Aurelius homeworld

### `/plot/`
Story structure and narrative elements.

- **`/chapters/`** - Detailed outlines for individual chapters
  - Scenes, character moments, and plot developments

- Key plot documents for each book and the overall series arc

### `/planning/`
Meta-level project planning documents.

- Project roadmaps, task tracking, and development notes
- Series overview and long-term planning

## File Naming Conventions

- Character files: `character_name.md`
- Chapter files: `book#_chapter#.md`
- Worldbuilding files: `descriptive_name.md`

## Development Approach

Rather than creating numerous small files that would be difficult to track, we're using a consolidated approach:

1. **Consolidated Character Arcs** - Instead of separate files for each character's arc, we maintain a single document with all character arcs.

2. **Chapter-Based Scene Organization** - Scenes are documented within chapter files rather than as separate documents.

3. **Thematic Grouping** - Worldbuilding elements are grouped by theme (magic, politics, locations) rather than as individual concepts.

This approach makes the repository more manageable while still maintaining comprehensive documentation of all story elements.

## Expansion Strategy

As the project develops, we may add:

- `/reference/` - For research materials and inspiration sources
- Additional worldbuilding categories as needed
- Expanded location descriptions for key settings

The goal is to maintain a balance between comprehensive documentation and practical usability.
