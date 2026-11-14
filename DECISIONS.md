# Decisions

**Week 2 Gap Closure: 11/4/2026**

## Gap 1: The missing number
-The Gap: The number of self reported voids are uncounted.
-What I found: | Line accidental void reports | 1 to 3 per location per month, self-reported | Certainly undercounted. Nobody files a ticket about their own mistake |
-Source: Under 'what we measure'.
-What it changes: We understand that the number of voids in a shift or day arene't accurate due to failed self reporting by employees.

## Gap 2: The solution disguised as a problem
-What the ticket asks for: The tickets asks for stats on the number of accidental, self-reported voids.
-The problem underneath it: Employees aren;t self reporting accidental voids.
-How I know they're different: when logging a ticket, timestamp, user, and tcket state are noted. Employees aren't logging the nformation correctly.
-Does the proposed solution address the real problem: Partly, we acknowledge that the voids aren't being logged properly but a solution hasn't been created.

## Gap 3:
-The constraint: A void is unrecoverable with tag, .rail-ticket--danger. A dialogue box is presented with a dialogue box, recoverable actions have an undo button but not dialogue boxes. There is no sign-in on pass displays.
-Where I found it: 'The four patterns' -> ticket pattern and confirmation destruction.
-Why the ticket doesn't mention it: the ticket proposes the information, it doesn't provide the documentation to solve the issue.
-what it rules out: Toast feedback from voids because Toast aren't on the line. User attributions because there is no sign-on. Adding a control to void tickets. A new backend service for logging voids.

**What goes in:** decisions, the gaps you closed and how, what you declined to do, what you cut, system decisions, anything you re-framed later, and your AI log. **What doesn't:** raw findings. Those go in [EVIDENCE.md](EVIDENCE.md).


**Week 3: Studio - Three Options**

| 1 Sentence | Create void option to prompt user to self identify when voiding orders or ingredients |

| What it costs the user | Slight additional effort. User will have to interact with 2-3 additional screens |

| What it costs the system including a sm/med/lg build size | On line, the build is large because an keyobard will have to be added in addition to the employee ID prompt. For servers, the build will be a medium because the additional windows follow a similar layout with minimal interactive function. |

| What it assumes | It assumes the user will have the time and necessary tools to input their user ID into the device. |

| What would kill it | It could kill productivity on the line due to cooks having to stop their flow to input ID. |


Write it as you go. Reconstructing this in Week 7 produces a file that reads like a case study rather than a record, and the design walkthrough will find the difference.

Full structure is in the **Decision Record** template. The short version:

```markdown
## 2026-09-14 — Chose Option B over A

**What I decided:** [one line]
**Why:** [the evidence, named]
**What I gave up:** [the cost]
**What would change this:** [what evidence would flip it]
```

For an AI entry, same shape: which tool, what for, what you kept, what you changed. Directing a tool is a decision.

---

## YYYY-MM-DD — [your first decision]

**What I decided:**
**Why:**
**What I gave up:**
**What would change this:**


