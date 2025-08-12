# Week 5: Buy Low Candidates

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - League rosters and performance data

## Prompt Template

Write 200-word "Buy Low" analysis in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference actual {sport} situations:
- Players returning from injury in real {sport}
- Teams with improving schedules based on real standings
- Recent coaching changes or tactical adjustments
- Trade rumors or roster moves in real {sport}
- Weather patterns (NFL), rest schedules (NBA), or fixture congestion (Soccer)

[IF BANTER]: Cheeky opportunity - "Time to fleece your league-mates while they're panicking!"
[IF BRUTAL]: Savage assessment - "These managers are too stupid to see value on their bench"
[IF PROFESSIONAL]: Analytical approach - "Based on usage trends and upcoming matchups..."
[IF CINEMATIC]: Dramatic opportunity - "In the darkest hour, fortune favors the bold"
[IF CASUAL]: Friendly advice - "Here's who you should probably try to grab"

Sport-specific factors:
[IF NFL]: Bye weeks, divisional matchups, weather forecasts
[IF NBA]: Rest patterns, tanking teams, trade deadline approaching
[IF MLB]: Pitching rotations, ballpark factors, weather patterns
[IF NHL]: Line combinations, power play units, back-to-back games
[IF Soccer]: Fixture difficulty rating, European competition, rotation patterns

Focus on 2-3 underperforming players. Suggest specific trades using actual rosters.
Reference why real {sport} factors make them valuable.

## Key Elements
- Identify 2-3 undervalued players currently rostered
- Connect to real {sport} situations for credibility
- Suggest specific realistic trades
- Match tone throughout

## Version History
- v1.0 - Initial buy low analyst prompt
- v2.0 - Added multi-sport support and real-world integration
