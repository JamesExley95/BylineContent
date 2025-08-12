# Week 12: Rivalry Week Stories

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{rivalry_input}` - User-provided rivalry context (optional)
- `{uploaded_data}` - Historical matchup data and current week pairings

## Prompt Template

Write 200-word rivalry coverage in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference famous {sport} rivalries:
- Compare intensity to classic {sport} rivalries
- Mention if real rivalry games are happening this week
- Use real rivalry history as metaphors
- Reference famous moments from {sport} rivalries

[IF BANTER]: Inside jokes emphasized - "The Toilet Bowl Trophy is on the line again"
[IF BRUTAL]: Past humiliations - "Remember talking all that trash before losing by 50?"
[IF PROFESSIONAL]: Historical analysis - "Series record: 7-3, average margin: 12.4 points"
[IF CINEMATIC]: Epic showdown - "Ancient grudges demand satisfaction... this is war"
[IF CASUAL]: Friends beefing - "These two have been going at it since draft day"

Sport-specific rivalry comparisons:
[IF NFL]: "Cowboys-Eagles level hatred" / "Packers-Bears historic"
[IF NBA]: "Lakers-Celtics intensity" / "Heat-Knicks beef"
[IF MLB]: "Yankees-Red Sox eternal" / "Dodgers-Giants bad blood"
[IF NHL]: "Canadiens-Bruins Original Six rivalry" / "Battle of Alberta"
[IF Soccer]: "El Clasico drama" / "Manchester Derby intensity"

User-provided rivalries: {rivalry_input}
If no rivalries provided, focus on:
- Closest matchup as "Game of the Week"
- First vs Last as "David vs Goliath"
- Similar records as "Playoff Implications Battle"

Cover 2-3 rivalry matchups with history and current stakes.
Connect each rivalry to real {sport} examples.

## Key Elements
- Identify 2-3 rivalry matchups or use user input
- Reference famous {sport} rivalries
- Include historical record between teams
- Explain current stakes for both teams

## Version History
- v1.0 - Rivalry week storytelling prompt
- v2.0 - Added multi-sport support and real-world integration
