# Week 5: Buy Low Candidates

## Required Inputs
- `{sport}` - Selected sport
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Week/Gameweek number
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - League rosters and performance data

## Prompt Template

Write 200-word "Buy Low" analysis in {sport} fantasy for {selected_tone} tone.

REAL-WORLD CONTEXT: Reference actual {sport} situations:
- Players returning from injury in real life
- Teams with improving schedules or matchups
- Coaching changes or scheme adjustments
- Recent trades or roster moves in real {sport}
- Connect fantasy value to real game situations

[IF BANTER]: Cheeky opportunity - "Time to fleece your league-mates while they're panicking!"
[IF BRUTAL]: Savage assessment - "These managers are too stupid to see value on their bench"
[IF PROFESSIONAL]: Analytical approach - "Based on usage trends and upcoming matchups..."
[IF CINEMATIC]: Dramatic opportunity - "In the darkest hour, fortune favors the bold"
[IF CASUAL]: Friendly advice - "Here's who you should probably try to grab"

Sport-specific factors to consider:
[IF NFL]: Bye weeks, strength of schedule, weather
[IF NBA]: Rest patterns, back-to-backs, tanking teams
[IF MLB]: Pitching matchups, ballpark factors, platoons
[IF NHL]: Line changes, power play time, goalie rotations
[IF Soccer]: Fixture difficulty, rotation risk, form

Focus on 2-3 underperforming players. Suggest specific trades using actual rosters.

## Key Elements
- Identify 2-3 undervalued players currently rostered
- Explain why they're undervalued using real {sport} context
- Suggest specific realistic trades
- Match tone throughout

## Version History
- v1.0 - Initial buy low analyst prompt
- v2.0 - Added multi-sport support and real-world integration
