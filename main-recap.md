# Main Weekly Recap Narrative Prompt

## Required Inputs
- `{sport}` - Selected sport (NFL/NBA/MLB/NHL/Soccer)
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current week/gameweek (1-17 for NFL, 1-24 for NBA, etc.)
- `{period_name}` - Week/Gameweek/Period based on sport
- `{selected_tone}` - User's chosen tone
- `{recap_all_games}` - Boolean for full recap
- `{game_of_the_week_only}` - Boolean for single game
- `{user_selected_game}` - Optional specific matchup
- `{uploaded_data}` - League data (CSV/Excel/API)

## Prompt Template

Generate fantasy {sport} recap for {league_name} {period_name} {period_number} in {selected_tone} tone.

REAL-WORLD CONTEXT: Reference actual {sport} events from this {period_name}:
- Mention real games, scores, and player performances
- Connect fantasy outcomes to actual game situations
- Use current {sport} storylines and news
- Reference injuries, trades, or major events

OPENING HOOK: Write 2-3 sentence lead capturing the week's biggest story/drama
[This appears BEFORE the matchups table]

USER CHOICE: {recap_all_games} or {game_of_the_week_only}

[IF recap_all_games]:
Write 75-100 words per matchup covering:
- How the game unfolded (key performances, turning points)
- Notable player performances (both good and bad)
- What this result means for each team
- Connect to real {sport} performances where relevant
- Match tone to selection (banter/brutal/professional/cinematic/casual)

[IF game_of_the_week_only]:
GAME SELECTION: {user_selected_game} OR {ai_selects_closest_or_highest_scoring}
Write 300-400 words deep dive on selected matchup:
- Pre-game context/stakes
- How it played out (progression of scoring if close)
- Star performances and crucial decisions
- Impact on both teams' seasons
- Reference relevant real {sport} games
- Match tone throughout

END WITH: One-sentence teaser for next week's biggest matchup

## Sport-Specific Terminology
[IF NFL]: touchdowns, yards, receptions, bye weeks
[IF NBA]: points, rebounds, assists, triple-doubles, load management
[IF MLB]: home runs, RBIs, ERA, batting average
[IF NHL]: goals, assists, saves, power play points
[IF Soccer]: goals, assists, clean sheets, bonus points

## Tone Variations
[Existing tone definitions remain the same]

## Version History
- v1.0 - Initial prompt creation
- v1.1 - Removed Visionary/Optimist sections per feedback
- v1.2 - Added game selection option
- v2.0 - Added multi-sport support and real-world context
