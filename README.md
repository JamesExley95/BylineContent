# BylineContent
BYLINE AI PROMPT SYSTEM - PLAIN ENGLISH EXPLANATION

## Overview
This repository contains all prompts and templates for the Byline AI fantasy sports content generation system. These prompts power our no-code MVP using Flowise AI and Anthropic.

## System Architecture

### Content Types
1. **Newsletter Components**
   - Main Recap Narrative
   - Awards Section (MVP, Manager, Optional)
   - Matchups Table (Visual component)
   
2. **Weekly News Pieces**
   - 15 different templates based on week of season
   - Each adapts to user-selected tone
   
3. **Standalone Content**
   - Meme Helper
   - Power Rankings

### User Flow
1. User completes dynamic form selecting content types
2. User chooses tone (Banter/Brutal/Professional/Cinematic/Casual)
3. User provides league data (Sleeper ID or CSV upload)
4. System generates appropriate prompts with variables
5. AI processes prompts and returns formatted content
6. Content delivered via email and web page

## File Structure
/newsletter-components

main-recap.md          # Core narrative generation

awards.md              # Three award types

/weekly-news-pieces

week-01-04-early-overreactions.md

week-05-buy-low.md

week-06-midseason-awards.md

week-07-trade-deadline-preview.md

week-08-trade-deadline-recap.md

week-09-playoff-picture.md

week-10-waiver-wire-heroes.md

week-11-schedule-luck.md

week-12-rivalry-week.md

week-13-must-win.md

week-14-playoff-clinching.md

week-15-playoff-preview.md

week-16-championship.md

week-17-season-reflection.md

/standalone-content

meme-helper.md         # Generates meme suggestions

power-rankings.md      # Weekly power rankings

/tone-guides

master-tone-guide.md   # Defines all five tones

## Tone System
Every prompt adapts to five distinct tones:
- **Banter**: Light-hearted, cheeky, playful
- **Brutal**: Savage roasting, no mercy
- **Professional**: Formal, analytical, ESPN-style
- **Cinematic**: Dramatic narratives, epic storytelling
- **Casual**: Friendly, conversational, relaxed

## Variables Used
- `{league_name}` - User's league name
- `{week_number}` - Current week (1-17)
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - League data (CSV/Excel)
- `{user_selected_game}` - Optional specific matchup
- `{inside_jokes_or_events}` - User-provided context

## Implementation Notes

### For Flowise AI
1. Store prompts as environment variables or in connected database
2. Create master flow that routes to appropriate prompt based on user selection
3. Inject variables from form data
4. Process through Anthropic API
5. Format output for email/web delivery

### Quality Assurance
- Test each prompt with sample data before deployment
- Ensure tone consistency throughout generated content
- Validate that all variables are properly replaced
- Check output length matches specifications

## Version Control
Each prompt file includes version history. Update when modifying prompts:
- v1.0 - Initial creation
- v1.1 - Bug fixes or minor adjustments
- v2.0 - Major revisions or restructuring

## Future Enhancements
## Current Features (v2.0)
- Multi-sport support (NFL, NBA, MLB, NHL, Soccer)
- Real-world sports integration in all content
- CSV-compatible alternatives for users without historical data
- Custom news piece options with user input
- Sport-specific terminology and references

## Future Enhancements
- Infographic generation prompts (coming in v2.1)
- Video script generation (planned for full product)
- Additional sports (Cricket, Australian Football)
- AI-powered trade analyzer
- Season-long narrative tracking

## Support
For questions about prompt implementation or modifications, refer to individual prompt files for specific documentation.

---
*Last Updated: [Current Date]*
*Byline AI - Your league. Your stories.*
