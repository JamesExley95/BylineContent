# Meme Helper Prompt (Standalone Content)

## Required Inputs
- `{sport}` - Selected sport
- `{league_name}` - Name of the fantasy league
- `{period_number}` - Current period
- `{inside_jokes_or_events}` - User-provided context
- `{selected_tone}` - User's chosen tone
- `{uploaded_data}` - League data for reference

## Prompt Template

Generate 3 meme options for {league_name} {period_name} {period_number} based on biggest moments in {sport} fantasy.

Context provided: {inside_jokes_or_events}
Tone: {selected_tone}
Sport: {sport}

For each meme provide:
TEMPLATE: [Drake meme, Distracted boyfriend, Woman yelling at cat, etc.]
SETUP/TOP TEXT: [First part]
PUNCHLINE/BOTTOM: [Second part]
CONTEXT: [One sentence explaining why this is funny to your league]

Focus on:
- Biggest upset
- Worst bench decision  
- Most lopsided victory
- Best/worst trade from earlier paying off/backfiring
- Sport-specific situations:
  [IF NFL]: Monday night miracles, bye week disasters
  [IF NBA]: Rest day benchings, triple-double on bench
  [IF MLB]: Pitching matchup fails, platoon disasters
  [IF NHL]: Backup goalie nightmares, hat trick benchings
  [IF Soccer]: Captain choice fails, differential disasters

## Tone Variations
[IF BANTER]: Playful jokes about the week's events
[IF BRUTAL]: Savage callouts of failures
[IF PROFESSIONAL]: Skip meme, suggest "{period_name} {period_number} Statistical Summary" instead
[IF CINEMATIC]: Epic movie quotes adapted to fantasy
[IF CASUAL]: Relatable fantasy {sport} moments

## Example Output
TEMPLATE: Drake meme
SETUP/TOP TEXT: Starting your 3rd string RB
PUNCHLINE/BOTTOM: Leaving 30 points on your bench
CONTEXT: Mike benched Kenneth Walker who scored 3 TDs

## Version History
- v1.0 - Initial standalone meme generator
- v2.0 - Added multi-sport support
