# Implementation Notes for Multi-Sport Support

## Form Logic
1. User selects sport in Field 4
2. System loads sport-specific:
   - Week/period options
   - News piece calendar
   - Terminology dictionary
   - Real-world reference pool

## Prompt Adaptation
Every prompt includes:
- `{sport}` variable
- `[IF {sport}]` conditionals
- Sport-specific terminology swaps
- Appropriate real-world references

## Example Flow

### User Selects NBA
- Form shows "Week 1-24" options
- News pieces adapt to NBA calendar
- Prompts reference:
  - NBA games and players
  - Triple-doubles, not touchdowns
  - Load management, not bye weeks
  - Lakers-Celtics, not Cowboys-Eagles

### User Selects Soccer
- Form shows "Gameweek 1-38"
- News pieces follow Premier League calendar
- Prompts reference:
  - Matches and clean sheets
  - Transfer windows
  - Fixture congestion
  - Manchester Derby rivalries

## Benefits
- One system works for all sports
- Easy to add new sports later
- Consistent quality across sports
- Efficient prompt management
