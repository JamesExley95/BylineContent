# CSV-Compatible Weekly News Pieces (No Historical Data Required)

## Overview
These alternative news pieces work with single-week CSV/Excel data only. System automatically uses these when user provides CSV instead of Sleeper API.

## Weeks 1-4: "This Week's Surprises"

Write 200-word analysis of this week's surprise performers in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference this week's actual {sport} games and results.

Focus on THIS WEEK ONLY:
- Highest scoring unexpected player (bench or low projection)
- Lowest scoring expected star
- Most lopsided matchup
- Closest matchup
- Connect to real {sport} games that just happened

No historical data needed - just analyze this week's surprises.

## Week 5: "Bench Points Disaster"

Write 200-word analysis of bench points left behind in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference why players might have been benched based on real {sport} matchups.

Analyze from THIS WEEK'S data:
- Who left the most points on bench
- Optimal lineup vs actual lineup for each team
- Worst bench decision of the week
- Connect to real {sport} - was it reasonable based on matchups?

Calculate optimal scores and compare to actual.

## Week 6: "Power Rankings This Week"

Write 200-word power rankings based on THIS WEEK'S performance in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference this week's {sport} games for context.

Rank all teams by:
- Points scored this week (primary)
- Optimal lineup efficiency (secondary)
- 30-word commentary for each team
- Who's hot right now based on this single week

No historical needed - pure week-based power rankings.

## Week 7: "Trade Ideas From This Week"

Write 200-word trade suggestion analysis based on THIS WEEK'S rosters in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference current {sport} news, injuries, and situations.

Based on current rosters visible in data:
- Teams with too many players at one position
- Teams with clear weaknesses
- Fair trades that make sense
- Reference real {sport} player situations

Look at roster construction only, no history needed.

## Week 8: "Start/Sit Disasters"

Write 200-word analysis of start/sit decisions from THIS WEEK in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Were the decisions reasonable based on {sport} matchups?

Focus on:
- Worst start decision (player who busted)
- Worst sit decision (bench player who boomed)
- Perfect lineup managers
- Should they have known better based on matchups?

Use only this week's lineup decisions and scores.

## Week 9: "Lucky or Good This Week"

Write 200-word analysis of luck vs skill THIS WEEK in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference actual {sport} game scripts and surprises.

Analyze:
- Teams that won with low scores (lucky)
- Teams that lost with high scores (unlucky)
- Optimal lineup percentage for each team
- Did the right team win each matchup?

Based entirely on this week's data.

## Week 10: "Roster Strengths & Weaknesses"

Write 200-word roster analysis based on THIS WEEK'S data in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference current {sport} player situations and upcoming schedules.

Identify from current rosters:
- Strongest position groups
- Weakest position groups
- Teams that need trades
- Hidden gems on benches

Roster analysis only, no historical data needed.

## Week 11: "Optimal Lineup Review"

Write 200-word optimal lineup analysis for THIS WEEK in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Should managers have seen it coming based on {sport} matchups?

Grade each manager on:
- Optimal lineup percentage
- Points left on bench
- Right/wrong decisions
- A-F grades for lineup management

This week only, no history required.

## Week 12: "Rivalry Week" (USER INPUT VERSION)

Write 200-word rivalry coverage in {sport} fantasy for {league_name} in {selected_tone} tone.

User-provided rivalries: {rivalry_input}

If no rivalries provided, create based on THIS WEEK:
- Closest matchup = "Rivalry of the Week"
- Highest scoring matchup = "Shootout of the Week"  
- Lowest scoring = "Toilet Bowl"
- 1st vs Last (if visible in standings)

Use this week's matchups to create drama.

## Week 13: "Crunch Time Analysis"

Write 200-word analysis of current standings in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference {sport} playoff races for comparison.

Based on CURRENT standings only:
- Who's in playoff position
- Who's on the bubble
- Who needs a miracle
- This week's most important matchups

Simple standings analysis, no complex scenarios.

## Week 14: "This Week's Heroes & Villains"

Write 200-word heroes and villains from THIS WEEK in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Connect to this week's {sport} standout performances.

Heroes:
- Highest scorer
- Best manager decision
- Clutch performance

Villains:
- Lowest scorer
- Worst decision
- Biggest disappointment

This week only focus.

## Week 15: "Playoff Matchup Preview"

Write 200-word preview of THIS WEEK'S matchups in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference current {sport} playoff games happening.

For each matchup:
- Key players to watch
- Advantage areas
- Bold prediction
- Connect to real {sport} playoffs

Based on current rosters only.

## Week 16: "Championship Preview"

Write 200-word championship preview in {sport} fantasy for {league_name} in {selected_tone} tone.

REAL-WORLD CONTEXT: Compare to real {sport} championship games.

Based on THIS WEEK'S matchup:
- Roster comparison
- Key matchup advantages
- X-factors
- Prediction

Focus on current rosters, not journey to get here.

## Week 17: "Season Awards"

Write 200-word season awards based on FINAL WEEK data in {sport} fantasy for {league_name} in {selected_tone} tone.

Awards based on visible data:
- Champion
- Highest scorer (if visible)
- Best roster construction
- Most balanced team
- Bold predictions for next year

Limited to what's visible in final week data.

## User Custom Options (Always Available)

When user selects "Custom Story", use their input:
- Topic: {custom_topic}
- Details: {custom_details}
- Context: {additional_context}

Write about their specific topic using only current week data.

## Implementation Logic

IF data_source == "CSV/Excel":
    USE these CSV-compatible prompts
ELIF data_source == "Sleeper API":
    USE full historical prompts (week-01-04-early-overreactions.md, etc.)

## Version History
- v1.0 - Initial CSV-compatible alternatives
- v2.0 - Complete set with all 17 weeks
- v2.1 - Added multi-sport support
