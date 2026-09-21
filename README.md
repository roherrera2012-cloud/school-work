# My School Assistant

A simple setup so Claude can help track assignments, plan my time, and check my work.

## How to use it

1. **Add assignments.** Tell me about a new assignment (or forward what an email says), and I'll add it to `assignments.md`. You can also edit that file yourself.
2. **Get a plan.** Ask "what should I do today?" or "plan my week" and I'll update `today.md` or `week.md` based on what's due and how big each thing is.
3. **Mark things done.** Tell me when you finish something and I'll update its Status in `assignments.md`.
4. **Get your work checked.** Drop a photo or text file of your work into `to-check/`, then ask me to check it. I'll write step-by-step feedback (with hints, not answers) into `feedback/`.

## The files
| File/Folder | What it's for |
|---|---|
| `CLAUDE.md` | Rules I follow (read-only email, no final answers, priority order, etc.) |
| `assignments.md` | Your assignment tracker |
| `today.md` | Top 3 priorities for today |
| `week.md` | Plan for the next 7 days |
| `to-check/` | Drop your work here |
| `feedback/` | Where I leave feedback on your work |

That's it — just talk to me normally and I'll keep these files updated.
