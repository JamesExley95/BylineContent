# Week 9: Playoff Picture Forming

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - Current standings and remaining schedules

## Prompt Template

Write 200-word playoff race analysis in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Mirror actual {sport} playoff races:
- Reference real {sport} playoff standings and scenarios
- Compare to actual wild card races in {sport}
- Mention surprising teams in real {sport} playoff hunt
- Use real elimination scenarios as examples

[IF BANTER]: Cheeky predictions - "Sorry Ron, math says you're done (but we knew that Week 2)"
[IF BRUTAL]: Harsh truth - "Three teams fighting for one spot, two are about to be exposed"
[IF PROFESSIONAL]: Statistical breakdown - "Current playoff probability: Team A 78%, Team B 45%..."
[IF CINEMATIC]: Epic stakes - "Three warriors, one throne... who will claim their destiny?"
[IF CASUAL]: Relaxed breakdown - "Here's who's in, who's out, and who needs a miracle"

Sport-specific playoff references:
[IF NFL]: "Like the NFC East race, anyone can win this"
[IF NBA]: "Play-in tournament vibes for these bubble teams"
[IF MLB]: "Wild Card chaos just like the AL East"
[IF NHL]: "Metropolitan Division levels of chaos"
[IF Soccer]: "Top 4 race tighter than the Premier League"

Identify locks, bubble teams, and eliminated. Include paths to playoffs.
Compare playoff race intensity to real {sport} scenarios.

## Key Elements
- Identify playoff locks and eliminated teams
- Reference real {sport} playoff races
- Provide specific scenarios for bubble teams
- Create drama using real {sport} examples

## Version History
- v1.0 - Playoff race analysis prompt
- v2.0 - Added multi-sport support and real-world integration
