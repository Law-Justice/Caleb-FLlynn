# Trial Lab: State of Ohio v. Caleb Flynn

A vertical, interactive timeline that walks high-school students through the procedure of a real jury trial, using the Miami County, Ohio trial of Caleb Flynn. Students act as jurors: they learn each step, watch a focused clip, type responses, and reach their own verdict **before** the site reveals what the jury decided.

It is built for **three class periods of about 70 minutes**, delivered as back-and-forth instruction (teacher guidance, student typing). A student who misses a day can switch to **On my own** and complete it individually.

> **Note for the teacher:** this file contains lesson timings and notes. If you publish the folder in a public GitHub repository and do not want students to read it, delete `README.md` before you upload. The site itself does not need it.

## What is in the folder

- `index.html` is the entire site (no libraries, no outside files)
- `screenshots/` shows what each part looks like
- `.nojekyll` tells GitHub Pages to publish the files as they are

## How it works

1. **Cover.** The student types a name and chooses *With my class* or *On my own*. The mode can be changed at any time from the bar at the top.
2. **Vertical timeline.** Three color-coded days and 16 stations, with a jump bar for each day. Cards stay small (icon, title, minutes, number of clips and questions).
3. **Each station has up to three steps:** Learn (key ideas and Ohio rules), Watch (a clip with a stated time window and “watch for” prompts), Respond (typed responses with a word counter and hints).
4. **Two ways to work.**
   - *With my class:* the longer explanations are collapsed because the teacher is covering them. Required responses are the questions from your assignments plus a few new ones. Discussion prompts are optional notes.
   - *On my own:* the full explanations are open, and discussion prompts become required typed responses.
5. **Verdict and reveal.** Station 15 asks for a vote on each charge and a written explanation. Station 16, with the jury’s verdict and sentence, stays locked until the student locks in their verdict. Nothing before it names the outcome.
6. **Word notebooks.** *Download Day N notebook* appears in each day’s header and in *My notebook*, and there is a complete notebook for all three days. A completion code is added at the end of each. Nothing is sent anywhere; the document is built in the browser.
7. **Courtroom guide.** A drawer with who’s who, the order of a jury trial (each step links to its station), key terms, and the charges.

Progress saves automatically in the student’s browser. It is tied to the device and web address, so a student should use the same computer to continue.

## Running each day

### Day 1: The Jury, the Evidence, and the Openings

Station time is about **63 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 1. The case in brief | 8 | Read the overview together and use the who’s-who table. Collect two first impressions on the board to revisit on Day 3. |
| 2. The rules for jurors | 12 | Play the clip. Pause to have students restate presumption of innocence and reasonable doubt in their own words. |
| 3. Two kinds of evidence | 10 | Run the sorter as a class poll. Ask one student to defend a close call. Stress that both kinds carry equal weight. |
| 4. The state’s opening statement | 14 | Watch the window. Have pairs list what the prosecutor promises to prove before they type. |
| 5. The defense’s opening statement | 11 | Watch, then compare the two stories about the same night. |
| 6. Your first check-in as a juror | 8 | Quiet typing. Collect students’ open questions to revisit on Day 2. |

If you run short: use the sorter in Station 3 as a quick class poll and let students finish Station 6 as an exit ticket.

### Day 2: Admitting Evidence, Direct Examination, and Cross

Station time is about **53 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 7. How evidence gets in, and who tells the story | 9 | Explain foundation with a non-case example (a photo of a school fight). Run the open-ended versus leading sorter. |
| 8. The 911 witness: laying the foundation | 14 | Watch once, pausing at each step of the foundation. Then type. |
| 9. Hearing the 911 call | 12 | Let students listen with the screen off if they prefer. Discuss sincerity as a class before they type, and separate what they noticed from what can be proven. |
| 10. Cross-examination and the body camera | 18 | Teach cross-examination, then watch. Ask students to track what the defense says was not preserved or recorded. |

If you run short: have students answer only the questions in Station 13 that you choose, and finish the rest at the start of Day 3 or in *On my own* mode.

### Day 3: Witnesses, Closing Arguments, and Your Verdict

Station time is about **63 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 11. Cross-examining a family witness | 10 | Watch the window. Compare the tone with the officer’s cross. |
| 12. Expert witnesses | 12 | Teach lay versus expert, then watch the clip. Ask students to name the leading questions. |
| 13. The defense rests | 5 | Explain the Fifth Amendment and why the burden never shifts. |
| 14. Closing arguments | 15 | Read the defense-closing coverage together, watch the two clips, then discuss which side was more effective. |
| 15. Your verdict | 14 | Go through the charges, then silent writing. Remind students the reveal opens only after they lock in. |
| 16. What the jury decided | 7 | Reveal, then discuss how verdicts compared and what procedure shaped their thinking. |

If you run short: discuss Station 13 aloud instead of typing it, and let students finish the reflection in Station 16 at home.

Switch a student to *On my own* on any day they missed. The jump bar lets them go straight to that day.

## What changed from the longer version

All 23 questions from your three assignments are still in, word for word. To fit 210 minutes, I merged overlapping stations (the direct-examination and lay-witness stations became one, and the cross-examination concept now sits with the body-camera station), cut the stand-alone digital-evidence and evidence-ledger stations, folded the final instructions into the verdict station, merged the two closing-argument stations, shortened every clip window, and reduced word minimums.

## Video clips and time windows

Every clip shows a time window (for example “Watch 17:43 to 27:43”), and the player starts there and stops at the end time. A plain YouTube link sits under each player in case the player is blocked. Videos load only when a student clicks play (YouTube’s privacy-enhanced address), and the site makes no other outside requests.

I could not watch the videos or read their timestamps. **Only the start times of 17:43 (body camera) and 20:00 (sister-in-law) come from your assignment.** Every other window was chosen from the order of testimony in news coverage and is an estimate. Use the teacher tool to check and fix them.

| Station | Clip | Source | Window | Basis |
|---|---|---|---|---|
| 2 | Jury instructions from the judge | Trial video (YouTube) | 0:00 – 5:00 | estimated from the order of testimony |
| 4 | State’s opening statement and key exhibits | Trial video (YouTube) | 0:00 – 8:00 | estimated from the order of testimony |
| 5 | Defense counsel’s opening statement | Trial video (YouTube) | 0:00 – 6:00 | estimated from the order of testimony |
| 8 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 0:00 – 8:00 | estimated from the order of testimony |
| 9 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 8:00 – 16:00 | estimated from the order of testimony |
| 10 | Caleb Flynn bodycam footage: “Ashley’s Dead, She’s Gone” | Court TV | 17:43 – 27:43 | start 17:43 is from your assignment; the end is estimated |
| 11 | Caleb Flynn sister-in-law testimony | Trial video (YouTube) | 20:00 – 28:00 | start 20:00 is from your assignment; the end is estimated |
| 12 | Caleb Flynn’s defense clashes with crime scene agent | Court TV | whole clip | whole short clip: nothing to estimate |
| 14 | State’s closing: Prosecuting attorney Matt Joseph | Courtroom Insider (YouTube) | 0:00 – 6:00 | estimated from the order of testimony |
| 14 | State’s rebuttal: Prosecuting attorney Paul Watkins | Courtroom Insider (YouTube) | 0:00 – 5:00 | estimated from the order of testimony |

**To adjust a window:** open the site with `#teacher` at the end of the web address (for example `.../index.html#teacher`). A **Clip times** button appears at the top. Enter start and end times as m:ss, press **Preview** to check, and **Save here** to keep the change in that browser. **Copy list** gives you the values to paste into `index.html`, where each clip has `start:` and `end:` in seconds (search for the clip id, such as `id: "c9"`). Students never see the tool.

Which videos are confirmed: the 911 video and the body-camera video are published by Court TV, and the expert cross-examination clip is described on Court TV’s own library. The two closing-argument videos carry the Courtroom Insider tag. Four of the links in your assignments (jury instructions, the two opening statements, and the sister-in-law testimony) I could not independently confirm, and they are used as given. If any video is unavailable, the link under it will say so.

No video of the defense’s closing argument turned up, so Station 14 links two news pages that report it in detail and uses the state’s rebuttal clip.

To turn all videos off, search `index.html` for `videos:true` and change it to `videos:false`.

## Accuracy notes

Facts come from reporting by CNN, ABC News, CBS News, NBC News, the Dayton Daily News and affiliates, WHIO, Court TV and Courtroom Insider, and Ohio law as cited in appellate opinions.

- **Trial status.** Your assignments describe the trial as ongoing. It has finished: jury selection began Sept. 17, 2026, openings were Sept. 18, the state and defense rested Sept. 28, closings and the verdict were Sept. 29, and sentencing was Oct. 5. The site is built so students decide first and see the outcome last.
- **Counts.** Some outlets say 11 charges. Two misdemeanor intimidation counts were dismissed before the verdict. The jury returned verdicts on nine counts.
- **Deliberation length.** Reports range from about two hours to two and a half hours. The site says so.
- **Reasonable doubt.** Ohio’s statute (R.C. 2901.05) says jurors must be firmly convinced of “the truth of the charge.” Your assignment quotes it as “the defendant’s guilt.” The site uses the statute’s wording.
- **Expert witnesses.** The BCI crime-scene agent, the BCI firearms examiner, and the digital forensic examiners gave opinions based on specialized training. The site calls them expert-type witnesses and does not claim anything about how each was formally qualified.
- **The 911 center director.** Your assignment says the defense asked no questions of this witness, and the site follows your assignment.
- **Ohio rules cited:** R.C. 2901.05; 2903.01; 2903.02; 2903.11; 2921.12; Ohio Evid.R. 401, 602, 611, 701, 702, 801(D)(2), 901; State v. Jenks, 61 Ohio St.3d 259 (1991); Griffin v. California (1965).

## Publishing on GitHub Pages

1. Create a repository and upload `index.html` and `.nojekyll`.
2. In the repository, open **Settings, then Pages**, choose the **main** branch and the **/ (root)** folder, and save.
3. After a minute the site is live at `https://YOUR-NAME.github.io/REPOSITORY-NAME/`. Add `#day2` (or `#day3`) to a link to send students straight to a day.

Do not rename the repository after students begin, because their saved progress is tied to the web address.

## Privacy

No accounts, no tracking, and no outside services except YouTube when a student clicks play. Responses are stored only in the student’s own browser. Students turn work in by downloading the Word notebook and uploading it to Google Classroom.
