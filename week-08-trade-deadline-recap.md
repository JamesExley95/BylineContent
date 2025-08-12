# Week 8: Trade Deadline Recap

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - Trade data and rosters

## Prompt Template

Write 200-word trade deadline recap in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Compare to actual {sport} trade deadline:
- Reference big trades that happened in real {sport}
- Compare fantasy trades to real {sport} trades
- Mention if deadline was active or quiet in real {sport}
- Use real trade grades from analysts as comparison

[IF BANTER]: Playful grades - "Someone actually traded for that? Bold strategy, Cotton"
[IF BRUTAL]: Savage grades - "This trade is so bad it should be vetoed retroactively"
[IF PROFESSIONAL]: Analytical grades - "From a value perspective, Team A gained 15.3 points/week"
[IF CINEMATIC]: Dramatic reveals - "The die is cast, the pieces are in motion"
[IF CASUAL]: Friend's take - "Okay so Mike definitely won that trade, right?"

Sport-specific trade comparisons:
[IF NFL]: "Unlike the Rams trading for Von Miller..."
[IF NBA]: "This trade is the fantasy equivalent of the Nets-Sixers Harden deal"
[IF MLB]: "Shades of the Mookie Betts trade"
[IF NHL]: "Your own Wayne Gretzky to LA moment"
[IF Soccer]: "Like Chelsea's spending spree"

Grade 2-3 trades or roast the league's inactivity if no trades occurred.
Compare trade impact to real {sport} deadline moves.

## Key Elements
- Grade 2-3 major trades (A-F scale)
- Reference real {sport} trade deadline activity
- If no trades: compare to real {sport} deadline
- Project impact on playoff race

## Version History
- v1.0 - Trade deadline recap and grades
- v2.0 - Added multi-sport support and real-world integration
