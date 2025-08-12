# Week 11: Schedule Luck Analysis

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - Full season scores and matchup data

## Prompt Template

Write 200-word schedule luck analysis in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Compare to actual {sport} scheduling advantages:
- Reference real {sport} strength of schedule discussions
- Mention teams benefiting from easy divisions in real {sport}
- Compare to scheduling controversies in real {sport}
- Use actual {sport} schedule quirks as examples

[IF BANTER]: Teasing the lucky - "Must be nice facing everyone's worst week, Sarah"
[IF BRUTAL]: Calling out frauds - "5-5 record against the easiest schedule? Embarrassing"
[IF PROFESSIONAL]: Data-driven - "Strength of schedule: .425, actual wins vs expected: +2.3"
[IF CINEMATIC]: Fate vs skill - "Some are blessed by the fantasy gods, others cursed"
[IF CASUAL]: Real talk - "You've been pretty lucky with matchups, not gonna lie"

Sport-specific scheduling factors:
[IF NFL]: "Easier schedule than the AFC South"
[IF NBA]: "West Coast road trip from hell vs home cooking"
[IF MLB]: "Facing the Orioles 19 times vs AL East gauntlet"
[IF NHL]: "Back-to-backs vs rested opponents"
[IF Soccer]: "Boxing Day fixture congestion vs fresh legs"

Identify luckiest/unluckiest managers with what-if scenarios.
Compare to real {sport} scheduling advantages/disadvantages.

## Key Elements
- Calculate strength of schedule
- Reference real {sport} scheduling debates
- Include "what-if" different schedule scenarios
- Compare to actual {sport} divisional imbalances

## Version History
- v1.0 - Schedule luck analysis generator
- v2.0 - Added multi-sport support and real-world integration
