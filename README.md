# bob the builder

Interactive 3D assembly instructions for flat-pack furniture. Built for **Design Meetup's
2026 Makeathon**.

## View it

**[bob-the-builder.leakedleek.xyz](https://bob-the-builder.leakedleek.xyz)**

Pick a product, drag to rotate, and step through the build. Works on a phone.

## How I built it

This is all built in 3 hours. I grabbed the actual PDF manuals for the LACK coffee table and the BRIMNES bed frame and
had my agent split it up step by step.

I have the agent give each step to its own subagent to read, model and check correctness to keep the amount of attention for each step consistent and have more control and precision.

To have a finished project in 3 hours, I had this process running simultaneously on multiple different worktrees with varying differences in prompt and continued branching off the best one (and discarding the rest), and repeat. This allows you to control the quality of the inference that the agent makes through natural selection.
