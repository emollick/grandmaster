# Board №7

A chess engine on an open board. It plays anyone. It has never lost.
Nobody is watching. You don't need to know the rules.

**[Play it here.](https://emollick.github.io/grandmaster/)**

## What this is

A single-file chess game for people who know nothing about chess, built to make
you feel like the greatest player who ever lived. You challenge DeepFish 17
(rating 4012, undefeated in 2,847,391 games) on a quiet public exhibition board,
and whatever happens after that is, frankly, the world's fault.

Your legal moves glow. Pick whichever feels right.

## The honest fine print

- **The chess is real.** Full legal move generation — castling, en passant,
  promotion, checkmate — verified against the standard perft test suite.
  The notation panel is genuine algebraic notation.
- **The opponent is real-ish.** DeepFish opens from an actual book and develops
  like a chess player. Its subsequent difficulties are its own business.
- **You cannot lose.** This is a structural guarantee, not encouragement.
- **The PGN export is a real game record.** Download it at the end and show a
  chess friend. Black's collapse is, as the textbooks say, instructive.

No dependencies, no build, no network. One HTML file. Open it and play.

---

*Built with [Claude Code](https://claude.com/claude-code). The only simulation is DeepFish's confidence.*
