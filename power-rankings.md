# Power Rankings Prompt

## Required Inputs
- `{league_name}` - Name of the fantasy league
- `{week_number}` - Current week
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - Current standings and recent performance

## Prompt Template

Generate power rankings for {league_name} after Week {week_number} in {selected_tone} tone.

FORMAT: Rank each team 1-[total_teams] with 30-word explanation each.

[IF BANTER]: Include playful nicknames and jokes about their trajectory
[IF BRUTAL]: Brutally honest about their chances, call out weakness
[IF PROFESSIONAL]: Focus on metrics - record, points for/against, strength of schedule
[IF CINEMATIC]: Dramatic descriptions of rise/fall, destiny narratives
[IF CASUAL]: Quick takes on who's hot and who's not

Include movement indicators (↑↓↔) and one bold prediction.

## Output Format
1. [Team Name] (↑2) - [30-word explanation in selected tone]
2. [Team Name] (↔) - [30-word explanation in selected tone]
[Continue for all teams]

BOLD PREDICTION: [One sentence prediction matching tone]

## Version History
- v1.0 - Power rankings generator
