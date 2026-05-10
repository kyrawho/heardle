# 🎲 Heardle: The Gamer's Edition

A daily song-guessing game built for my mom — who loves Wordle, NYT Connections, and any excuse to compete with my dad and their friends Grace and David.

You get six chances to name a song from a progressively longer clip. Start with one second. If you're stumped, tap "Not sure" and get a little more. Keep going until you get it or run out of tries.

---

## The story

My mom, Amy, plays NYT games every day. Wordle, Connections, the Mini — usually with my dad Jeff, and their friends Grace and David. When I started thinking about a Mother's Day gift, I wanted to make something they'd actually play together, not just once.

Heardle: The Gamer's Edition is that thing. Built for the four of them, tuned to their taste in music, with a personalized greeting for each player when they open it.

This was also my first vibe coding project — built with Claude and ChatGPT in May 2026, for Mother's Day.

---

## How to play

1. Open the game and enter your name
2. Pick a category: **📼 80s & 90s** or **🎧 2000s+**
3. Tap the play button to hear the first second of today's song
4. Type a guess — the autocomplete will help
5. If you're not sure, tap **Not sure** to skip to a longer clip
6. You have 6 rounds: 1s → 2s → 4s → 7s → 11s → 16s
7. Everyone playing the same category on the same day gets the same song
8. Share your scorecard with the group

---

## The players

| Name | Relationship |
|------|----------|
| 👩🏻 Amy | The Woman Herself! |
| 👨🏻 Jeff | Mom's Husband |
| 👩🏻 Grace | Mom's Friend |
| 👨🏻 David | Mom's Friend |
| 👩🏻 Carly | Mom's Daughter |
| 👩🏻 Suk Yi | Mom's Sister |

Each player gets a personalized greeting when they open the game. Just type your first name.

---

## Song categories

**📼 80s & 90s** — 1980 through 1999. Michael Jackson, Madonna, Whitney Houston, Eraserheads, Rivermaya, Fleetwood Mac, Nirvana, TLC, Mariah Carey, and more.

**🎧 2000s+** — 2000 to today. Beyoncé, Adele, Taylor Swift, Rihanna, Bruno Mars, Ben&Ben, Olivia Rodrigo, Dua Lipa, SB19, and more.

A new song every day per category. The song rotates on a deterministic schedule — same song for everyone, no randomness.

---

## Features

- Daily songs, same for all players
- Autocomplete pulls from a wide pool so the dropdown doesn't spoil future answers
- Fun fact about the song or artist after each round (Wikipedia-powered)
- Archive to replay past days
- Streak and score tracking
- Shareable scorecard
- Personalized greeting + memoji per player
- Works entirely offline after first load — no app, no login, no subscription needed

---

## Tech

Single HTML file. No framework, no backend, no database. Song previews from the iTunes Search API (free, no key required). Fun facts from Wikipedia. Runs in any browser, optimized for mobile Safari on iOS.

Built with Claude (Anthropic) and ChatGPT. First vibe coding project — May 2026.

---

## Roadmap

- **v1.2** — shared live leaderboard so the group can actually see each other's scores
- **v2.0** — by Christmas 2026 (or sooner)

---

*Made with love by Kyra Hu · Mother's Day 2026*
