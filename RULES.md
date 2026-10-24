# Fortepianissimo — Rules (v1)

Loosely based on Blitz / 31.

## Components
- 50 cards: ranks 1–10 in five suits, each marked with a music-notation symbol: Treble (𝄞 treble clef), Bass (𝄢 bass clef), Sharp (♯), Flat (♭), Eighth (♪ eighth note).
- Each player: 4 lives and two tokens, **M** (Major, "best hand") and **m** (Minor, "worst hand").

## Setup
- Deal 4 cards to each player. Deal 4 cards face up in the center as the pool.
- Turn a fifth card face up as the **bests** card. Its suit is bests for the round. The bests card itself stays out of play.

## Hands (4-card poker, best first)
Ranked by how rare each hand is in this 50-card deck (out of 230,300 possible hands). 1 is low; straights don't wrap.

| Hand | Example | Ways to make it |
|---|---|---|
| Straight flush | 7-8-9-10, one suit | 35 |
| Four of a kind | 6-6-6-6 | 50 |
| Flush | four of one suit | 1,015 |
| Straight | 3-4-5-6 | 4,340 |
| Three of a kind | 9-9-9-2 | 4,500 |
| Two pair | 8-8-3-3 | 4,500 |
| Pair | 5-5-10-2 | 90,000 |
| High card | 10-7-4-1 | 125,860 |

Within a category, higher ranks win (the straight's top card; for groups, the bigger group's rank first, then kickers). If two hands are still equal, **bests breaks the tie**: the hand with the higher bests card wins (then the next bests card, and so on).

## Turn
- Swap one of your cards for one pool card, or pass.
- Once every player has had a turn, you may instead call **"Forte!"**: place one token face down. Your hand is locked.

## After a call
- Every other player takes one last turn, then places one token face down.

## Reveal
- **Major (M)** is correct if your hand is the highest.
- **Minor (m)** is correct if your hand is the lowest.
- If hands are still tied after bests, every tied claim counts as correct. No one loses a life over a tie.
- Wrong claim: lose a life. At 0 lives you're out.

## Winning
- Last player standing wins. Deal passes left each round.
- If everyone still in goes out on the same reveal, the game is a draw.

## Open questions (choices made in v1)
- Calling replaces your swap (Blitz-style knock). Alternative: swap, then call.
- Passing is allowed: a turn is a swap, a pass, or a call.
- No calling until everyone has had at least one turn.
- Bests only breaks exact ties. It doesn't change hand rankings (a pair holding a bests card doesn't beat a higher pair).
- Ties that bests can't break count as correct for Major and Minor.
- Straight ranks above three of a kind and two pair because it's slightly rarer with 5 suits (4,340 vs 4,500). Three of a kind and two pair are equally rare; three of a kind is ranked higher by convention.
