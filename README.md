# 🎡 Countdown Raffle

Create a raffle, share the link, and when the countdown hits zero the wheel spins for everyone at the same time and picks a winner.

**Live:** https://wuenschtim99.github.io/raffle_generator/

## How it works
1. Enter a title, the participant names (one per line or comma-separated), and the draw time.
2. Click **Create raffle link** and send the link to everyone.
3. Everyone who opens the link sees the same countdown. At the draw time the wheel spins and lands on the winner.

There is no backend. The whole raffle (names, time, random seed) is stored in the link itself. The winner comes from that seed, so every device shows the same result, and anyone who opens the link after the draw sees the winner straight away (with a "Replay spin" button).

> Note: the result is fixed when the link is created. Someone who decodes the link could work out the winner in advance, so this suits casual raffles.
