# My School Assistant

A simple setup so Claude can help track assignments, plan my time, guide me through work, and check what I've done.

## How to use it

1. **Add assignments.** Drop a Google Classroom screenshot or pasted teacher email into `inbox/`, or just tell me about a new assignment. I'll add it to `assignments.md` and write a how-to guide for it in `guides/`.
2. **Get a plan.** Ask "what should I do today?" or "plan my week" and I'll update `today.md` or `week.md` based on what's due and how big each thing is.
3. **Follow the guide.** Before starting an assignment, check `guides/` for a step-by-step walkthrough with a worked example — it won't solve the assignment for you, just show you how.
4. **Mark things done.** Tell me when you finish something and I'll update its Status in `assignments.md`.
5. **Get your work checked.** Drop a photo or text file of your finished work into `to-check/`, then ask me to check it. I'll write step-by-step feedback (with hints, not answers) into `feedback/`.

## The files
| File/Folder | What it's for |
|---|---|
| `CLAUDE.md` | Rules I follow (read-only email, guides not answers, priority order, etc.) |
| `assignments.md` | Your assignment tracker |
| `today.md` | Top 3 priorities for today |
| `week.md` | Plan for the next 7 days |
| `inbox/` | Drop Classroom screenshots / teacher emails here |
| `guides/` | How-to guide for each assignment |
| `to-check/` | Drop your finished work here |
| `feedback/` | Where I leave feedback on your work |

That's it — just talk to me normally and I'll keep these files updated.
