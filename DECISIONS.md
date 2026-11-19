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



## Week 4: Studio A - Direction and Constraint ##

**Part 1: Pick a Direction**
Hi Marisole,

My choice is to go with the server station because of known device functionality. The server station will have the option to use a keyboard which keeps my decision the same. The expo option wasn't viable because the need to disrupt the flow of the line by inputing an employee ID mid cooking action which isn't a reasonanble ask. It is also unknown if the device has keyboard functionalities. The floor option was only ruled out due to the unknown nature of keyboard functionality. The data doesn't tell me which options would be most obstructed by the need to input an employee ID and manually void food items.

Thanks,
Ren Lewis


**Part 2: answer the Memo**
Hi Marisole,

The question to be answered is what measures can be implemented to ensure voids, accidental or not, are accoutned for? With your input that the issue may not be what I think it is, I'll divert my attention to the floor layout I originally created. The issue I anticipated was that the floor device may not have the functionality for a keyboard but that may be the issue to resolve. With you out of office, I'll start the build for the floor workflow. I want to delve deeper into the possible functionality for the floor device by adding the void button, keyboard, and two additional windows. When you're back in office there will be something tangible for you to review.

Thanks,
Ren Lewis




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


