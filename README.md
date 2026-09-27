### Hi, I'm Jeff 👋

I build developer tools for working with AI: things that make models easier to measure, compare and live with day to day.

#### What I'm working on

<table>
<tr>
<td width="50%" valign="top">

**[System One Playground](https://github.com/goodboybeau/system-one-playground)**<br>
Run the new wave of *decision models* (Laya, Decider, Kev and TypeSafe's Jev) side by side on your Mac. Structured input goes in and calibrated probabilities come out, with honest numbers for accuracy, calibration, latency and memory. Every model runs sandboxed, offline, on the Apple GPU.

`Python` `TypeScript` `MLX` `Apple Silicon`

</td>
<td width="50%" valign="top">

**[claude-statusline](https://github.com/goodboybeau/claude-statusline)**<br>
A multi-line statusline for Claude Code: context window, 5-hour and weekly rate limits with countdowns, session cost, and per-turn timing stats, drawn as gradual-fill progress bars.

`Shell` `TypeScript` `Claude Code`

</td>
</tr>
</table>

<a href="https://github.com/goodboybeau/system-one-playground"><img src="https://raw.githubusercontent.com/goodboybeau/system-one-playground/main/docs/assets/overview.png" alt="System One Playground: every decision model on every dataset" width="100%"></a>

#### Things I've found lately

- Laya, the viral open "System One" model, silently cuts off long input after about 475 tokens, and a word-overlap baseline beats it on Banking77.
- On Apple Silicon, RSS undercounts GPU-backed models by 10–90×; physical footprint is the number to trust.
- Decision-trained 2B models match 4B ones at half the latency. [Full results →](https://github.com/goodboybeau/system-one-playground#results-on-an-m1-max-32-gb)
