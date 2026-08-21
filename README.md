# Joseph Bisaccia

**Lead AI Engineer — secure enterprise AI in regulated healthcare.**

I build production AI systems and the instrumentation that proves — or
disproves — their value. Nine years shipping technical systems into
organizations that had to adopt them; the last two building production AI.

## The *-gate* projects

Four small, complete harnesses with one thesis: **nothing ships until it
passes a gate — and the gate itself must be earned.**

| repo | the gate | the claim it protects |
|---|---|---|
| [kappa-gate](https://github.com/jbisaccia-9/kappa-gate) | an LLM-as-judge must clear Cohen's κ ≥ 0.70 against hand-authored labels before it is trusted | "our eval says this is good" |
| [roi-gate](https://github.com/jbisaccia-9/roi-gate) | an ROI figure is reportable only if the model was biased *against* the claim — CI refuses the vendor-deck version | "this deployment is worth $X/yr" |
| [phi-gate](https://github.com/jbisaccia-9/phi-gate) | a redaction layer must clear recall ≥ 0.95 on a labeled corpus before it may front an LLM | "the pipeline is safe for regulated data" |
| [trade-gate](https://github.com/jbisaccia-9/trade-gate) | no order executes while the local book and the broker's snapshot disagree | "the bot knows what it holds" |

Each one is runnable in three commands, tested, CI-checked, and honest about
its limits — every dataset is synthetic, and each README states what the tool
*cannot* do alongside what it can.

## Elsewhere

[getaiintegrations.com](https://getaiintegrations.com/) ·
[LinkedIn](https://www.linkedin.com/in/joseph-bisaccia-ai/) ·
[portfolio video](https://youtu.be/XQtBcV9fjlU)
