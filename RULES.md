# Fortepianissimo — Rules (v2)

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

### Comparing two hands of the same kind: bests before values
1. **Bests first.** The hand holding the highest bests card wins (then the next bests card, and so on). How many bests cards you hold doesn't matter. A pair of 5s with a bests card beats a pair of 8s without one.
2. **Then values.** If neither hand holds a bests card, higher values win: a straight goes by its top card; otherwise compare the biggest group first, then the other cards from high to low.
3. **Bests never beats a better kind of hand.** Any two pair beats any pair, bests or not.

## Turn
- Swap one of your cards for one pool card, or pass.
- Once every player has had a turn, you may instead call **"Forte!"**: place one token face down. Your hand is locked.

## After a call
- Every other player takes one last turn, then places one token face down.

## Reveal
- **Major (M)** is correct if your hand is the highest.
- **Minor (m)** is correct if your hand is the lowest.
- If hands are still tied (no bests cards and the same values), every tied claim counts as correct. No one loses a life over a tie.
- Wrong claim: lose a life. At 0 lives you're out.

## Winning
- Last player standing wins. Deal passes left each round.
- If everyone still in goes out on the same reveal, the game is a draw.

## Open questions (choices made in v1)
- Calling replaces your swap (Blitz-style knock). Alternative: swap, then call.
- Passing is allowed: a turn is a swap, a pass, or a call.
- No calling until everyone has had at least one turn.
- Bests before values: within the same kind of hand, bests cards are compared before values. In 1,000 simulated games this decided the best or worst hand in about 1 in 5 reveals, against 1 in 150 when bests only broke exact ties.
- True ties (no bests cards, same values) count as correct for Major and Minor.
- Straight ranks above three of a kind and two pair because it's slightly rarer with 5 suits (4,340 vs 4,500). Three of a kind and two pair are equally rare; three of a kind is ranked higher by convention.
