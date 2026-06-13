---
description: List every ops command and what it does
---

Show the user the full list of ops commands available in this repo. Format it as a clean table grouped by zone. Do NOT invoke any other agent — this command only prints the list.

Use exactly this output:

```
# Your Ops Commands

Type any of these in chat and Claude will run the agent for you.

## Quick action
| Command | What it does |
|---|---|
| /board | **Show the visual ops board inside Claude chat** |
| /check-everything | Full health check on all 4 parts of your business |
| /ops | Short alias for /check-everything |

## Offers
| Command | What it does |
|---|---|
| /check-offers | Audit all 12 offers — prices, tier health, conversion path |
| /check-killzone | Check the $497 → $5,997 pricing bridge |
| /check-pricing | Look for discounts, fake bonuses, fake scarcity |

## Trademarks
| Command | What it does |
|---|---|
| /check-trademarks | Audit trademark names — what's registered, what's risky |
| /trademark-priority | Tell me what to file first |

## Frameworks / Methods
| Command | What it does |
|---|---|
| /check-methods | Audit all frameworks — docs, naming, deployment |
| /fix-rams | Fix the RAMS naming mix-up across files |
| /find-gaps | Find frameworks in IP-REGISTRY with no document file |

## Reputation / Channels
| Command | What it does |
|---|---|
| /check-reputation | Audit reputation, credentials, channels |
| /check-voice | Check writing voice consistency across files |
| /check-content-universe | Check whether the 20-piece content system is documented |

## Help
| Command | What it does |
|---|---|
| /ops-help | Show this list |

Tip: you can also just describe what you want in plain English ("audit my offers", "what trademark should I file first"). Claude will pick the right agent.
```

After printing the table, do nothing else. End your response.
