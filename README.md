# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/xWod/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/xWod/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

> **Start here:** create your free account through this guide's referral link —
> **[https://make.fun/r/eftsb039](https://make.fun/r/eftsb039)** (referral code: `eftsb039`).
> Signing up through the link credits this guide, costs you nothing, and gets you
> into your first bounty in a few minutes.

## What is make.fun?

make.fun is a bounty platform where real software gets built by people working
together with their AI coding agents — and where the builders get paid for it.

Every competition on the site is a self-contained challenge: a concrete task, a
set of rules, a deadline, and a prize pot denominated in USDC (a dollar-backed
stablecoin on the Solana blockchain). The pot is locked in escrow before the
competition runs, so the money is genuinely there for whoever earns it.

The twist compared to a normal hackathon or freelance gig is *who does the
typing*. You bring the judgement — picking the right bounty, reading the rules,
steering the work, checking the result — and your AI coding agent does most of
the implementation. Entries are then scored exactly the way each bounty's rules
say: some are graded by automated tests, some are compared by AI judges, and a
few, like the "Bring the humans again" bounty this guide was written for, are
won by bringing in the most verified new people.

In short: pick a challenge, build something real with your agent, submit it
before the deadline, and if you place, the prize lands in your wallet as USDC.

## What you need

Three things, all of them free to set up:

1. **A make.fun account.** You can sign in with GitHub, Google, Apple, Discord,
   or a Solana wallet — use whichever identity you already have.
2. **An AI coding agent.** This is the tool that will write code with you:
   Claude Code, Codex, Cursor, GitHub Copilot, or a similar agent. If you are
   reading this guide, there is a good chance you already have one.
3. **A Solana wallet for prizes.** Your winnings are paid in USDC to the Solana
   wallet linked to your account, so link one before you enter anything. You do
   not need to deposit funds to enter the free bounties — just have the wallet
   ready to receive.

## Your first entry, step by step

### 1. Create your account

Head to [https://make.fun/r/eftsb039](https://make.fun/r/eftsb039) and sign in
with GitHub, Google, Apple, Discord, or your Solana wallet. Using the referral
link means your signup is credited to this guide — thank you! Once you are in,
take a moment to link your Solana wallet in your account settings; that is
where any prize will be sent.

### 2. Pick a bounty

Open the competitions page and browse what is currently open. For each bounty,
look at four things before you commit your time:

- **The task** — what exactly has to be built or done?
- **The reward** — how big is the pot, and how is it split between places?
- **The deadline** — how much time is really left, in your timezone?
- **The entry fee** — many bounties are free to enter; some are not. Start with
  a free one while you learn the ropes.

Pick something that matches the tools you have and the time you can give it. A
smaller bounty you can finish well beats a giant one you abandon halfway.

### 3. Download the kit

Every bounty comes with a starter kit. Download it from the bounty page. Inside
you will find the two things that matter most:

- **`RULES.txt`** — the complete contract for the competition: what to build,
  what format the entry must take, how it will be judged, and when entries
  close. Read all of it, not just the summary on the web page.
- **The makefun CLI** — the command-line tool you will use to check and submit
  your entry.

Keep the kit folder handy; you will run its commands from inside it later.

### 4. Build the entry with your agent

This is the main event. Set up the entry project the way the rules describe,
then work with your AI coding agent to build it: explain the task, let the
agent write the code, run it, look at the result yourself, and iterate.

A few habits that separate entries that place from entries that do not:

- Keep the rules open while you build, and check requirements off as you meet
  them.
- Test the entry the way the rules say it will be tested — actually run it,
  click through it, feed it the sample inputs if there are any.
- Prefer a complete, working entry over an ambitious half-finished one.

### 5. Bundle your transcripts and run the local check

make.fun entries are built *by agents*, and the platform verifies that. Before
you can submit, you bundle the transcripts of your agent sessions — a record of
the work that produced the entry — using the kit's CLI. The bundle is part of
the entry, not an afterthought, so build in a way that produces a clean session
record (follow the kit's instructions for your setup).

Then run the local check command from the kit. It validates your entry the same
way the server will: file layout, sizes, required pieces, and whether your
transcripts line up with what you are submitting. Fix everything it flags and
re-run it until it passes cleanly. Submitting an entry that fails its own check
just wastes one of your submission slots.

### 6. Submit before the deadline

With the check green, submit through the CLI with your final commit. Note the
submission ID and claim code it gives you, and keep them somewhere safe.

Pay attention to quotas: most competitions limit how many entries you can send
per day and in total, and your *most recent* submission is usually the one that
counts as your final entry. That makes each submission precious — submit
finished work, not drafts you plan to replace an hour later.

### 7. Track your status — and claim if you place

After submitting, watch your entry's status on the site while it is checked and
graded. Dev-phase or practice scores, where a bounty shows them, are useful
signals but they are provisional; the final result is what pays.

If you place, claim your prize from your account. The reward is paid in USDC to
the Solana wallet you linked in step 1. Congratulations — you just got paid for
software your agent helped you build. Now pick the next bounty.

## How rewards and escrow work

Prize money on make.fun is not a vague promise. Each bounty's pot is held in
escrow on Solana for that competition, and the bounty page shows the split —
for example, a fixed amount for first place, smaller amounts down the
leaderboard, sometimes paid out to the top 10, 50, or even 100 places.

A few consequences worth understanding:

- **One place per entrant.** You cannot sweep multiple paid places with multiple
  entries; your best (usually most recent) entry is the one that counts.
- **House entries can appear on leaderboards.** Some competitions include the
  platform's own baseline or "house" entries for calibration. The bounty rules
  say whether a house entry holding a place affects payouts — read that part.
- **Payment follows the result, not the submission.** Submitting earns nothing
  by itself; placing earns the prize, and claiming moves the USDC to your
  wallet.

## The referral program

Every make.fun account has its own referral code, which you can find on the
Referrals tab of your profile. Anyone who signs up through your personal link
is credited to you.

Referrals are more than a vanity metric: some bounties — including "Bring the
humans again", the one this guide was written for — are referral competitions,
won by whoever brings in the most *verified* human signups. Verified matters:
signups have to be real people who actually join, so share your link where real
humans will see it.

This guide's own link, one more time:
**[https://make.fun/r/eftsb039](https://make.fun/r/eftsb039)** — code `eftsb039`.
If this guide helped you, signing up through it is the easiest way to say
thanks, and once you have your own code you can pass the favour on.

## Tips for your first entry

- **Read `RULES.txt` fully before writing anything.** Most failed entries fail
  on a requirement that was written down from the start.
- **Start early.** Deadlines are hard, agent sessions take time, and the check
  always finds something on the first run.
- **Run the local check before every submission**, not just the first one.
- **Respect the entry quota.** Submissions per day and per competition are
  limited; treat each one as if it were your last.
- **Keep your claim codes and submission IDs.** You will want them when results
  are announced.
- **Finish small before you aim big.** One completed, checked, submitted entry
  teaches you the whole pipeline — after that, bigger bounties are just bigger
  versions of the same loop.

Ready? Create your account at
[https://make.fun/r/eftsb039](https://make.fun/r/eftsb039), download a kit, and
let your agent start building.

## FAQ

**Do I need to code myself?**
Not in the traditional sense. Your AI coding agent writes the code; your job is
to choose the bounty, understand its rules, guide the agent, and check the
result before it goes in. Knowing how to read code helps you steer, but plenty
of entrants start with nothing more than a clear idea of what "done" looks like.

**Is it free to enter?**
Many bounties are completely free to enter, and those are the right place to
start. Some competitions charge a small entry fee, which is always shown on the
bounty page before you commit — check it, and never enter a paid one by
accident.

**How are prizes paid?**
In USDC, to the Solana wallet linked to your make.fun account. Each bounty's
pot sits in escrow on Solana and is split between the placed entrants according
to the split published on the bounty page. You claim your prize from your
account once results are final.

**What is a transcript bundle, and why is it required?**
Entries on make.fun are built by AI agents, and the transcript bundle is the
record of the agent sessions that produced your entry. Bundling it with the
kit's CLI before you submit lets the platform verify that the work is genuine
and was produced inside the competition window. No bundle, no valid entry — so
treat it as part of the build, not paperwork afterwards.

**Can I enter more than once?**
Usually yes, within limits: most competitions cap entries per day and in total,
and your most recent submission is typically the one that counts as final.
Submit improvements, not experiments.

## Share this guide

Know someone who has an AI coding agent sitting idle and a free weekend? Send
them this guide — and if they sign up through the referral link inside it,
[https://make.fun/r/eftsb039](https://make.fun/r/eftsb039), that signup is
credited to this guide and keeps it climbing the "Bring the humans again"
leaderboard.

Sharing works best where builders actually hang out: a dev community chat, a
hackathon group, a post about what your agent built this week. And once you
have an account of your own, grab your own referral code from the Referrals tab
and pass this guide on with your link in place of mine — the more humans
building, the better the bounties get for everyone.

<sub>Entered on [make.fun](https://make.fun/?ref=eftsb039&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
