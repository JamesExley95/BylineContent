# Updated Form Structure for Custom Content

## Section 4: Weekly Recap Narrative (REVISED)

### Field 6: Tone Selection
[Existing tone options]

### Field 7: Recap Coverage  
○ All games (brief recap of each matchup)
○ Game of the Week only (deep dive on one matchup)

### Field 7a: Which Game? (if Game of Week selected)
○ Let AI choose
○ [Dropdown of matchups]

### Field 8: Weekly News Piece
**"What story should we tell this week?"**

○ Let AI choose based on week {week_number}
○ Select from suggestions:
  - Surprise Performers
  - Bench Points Analysis  
  - Manager Report Card
  - Optimal Lineup Review
  - Trade Ideas
  - Power Rankings
  - Custom Story (fill in below)

### Field 8a: Custom Story Title (if selected)
Text field: "What's your story about?"
[50 character limit]

### Field 8b: Custom Story Details
Text field: "Give us the details:"
[500 character limit]
Examples shown:
- "Rivalry details: Mike vs Sarah, loser does punishment"
- "Inside joke: The trophy curse continues"
- "League drama: Commission controversy"

### Field 8c: Additional League Context (Optional)
Text field: "Any running jokes, storylines, or context we should know?"
[500 character limit]

### Field 9: Data Upload
[Existing CSV/Excel upload]

## Smart Defaults by Week
If user selects "Let AI choose", system checks:
1. Is historical data available? (Sleeper API)
   - YES: Use original complex prompts
   - NO: Use CSV-compatible versions
2. Apply week-appropriate theme
3. Generate content

## Version History
- v1.0 - Original prompts requiring historical data
- v2.0 - Added CSV-compatible alternatives
- v2.1 - Added user input options for customization
