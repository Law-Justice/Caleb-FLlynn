# Trial Lab: State of Ohio v. Caleb Flynn

A vertical, interactive timeline that walks high-school students through the procedure of a real jury trial, using the Miami County, Ohio trial of Caleb Flynn. Students act as jurors: they learn each step, watch a focused clip, type responses, and reach their own verdict **before** the site reveals what the jury decided.

It is built for **four class periods of about 90 minutes**, delivered as back-and-forth instruction (teacher guidance, student typing). A student who misses a day can switch to **On my own** and complete it individually.

> **Note for the teacher:** this file contains lesson timings and notes. If you publish the folder in a public GitHub repository and do not want students to read it, delete `README.md` before you upload. The site itself does not need it.

## What is in the folder

- `index.html` is the entire site (no libraries, no outside files)
- `screenshots/` shows what each part looks like
- `.nojekyll` tells GitHub Pages to publish the files as they are

## How it works

1. **Cover.** The student types a name and chooses *With my class* or *On my own*. The mode can be changed at any time from the bar at the top.
2. **Vertical timeline.** Four colored days, 22 stations, with a jump bar for each day. Cards stay small (icon, title, minutes, number of clips and questions).
3. **Each station has up to three steps:** Learn (key ideas and Ohio rules), Watch (a clip with a stated time window and “watch for” prompts), Respond (typed responses with a word counter and hints).
4. **Two ways to work.**
   - *With my class:* the longer explanations are collapsed because the teacher is covering them. Required responses are the questions from your assignments plus new ones. Discussion prompts are optional notes.
   - *On my own:* the full explanations are open, and discussion prompts become required typed responses.
5. **Verdict and reveal.** Station 21 asks for a vote on each charge and a written explanation. Station 22, with the jury’s verdict and sentence, stays locked until the student locks in their verdict. Nothing before it names the outcome.
6. **Word notebooks.** *Download Day N notebook* appears in each day’s header and in *My notebook*. There is also a complete notebook for all four days. A completion code is added at the end of each. Nothing is sent anywhere; the document is built in the browser.
7. **Courtroom guide.** A drawer with who’s who, the order of a jury trial (each step links to its station), key terms, and the charges.

Progress saves automatically in the student’s browser. It is tied to the device and web address, so a student should use the same computer to continue.

## Running each day

### Day 1: The Jury and the Evidence (about 85 minutes of station time, plus transitions)

| Station | Minutes | Teacher moves |
|---|---|---|
| 1. The case in brief | 10 | Read the overview with students; use the who’s-who table. Ask for first impressions and write two on the board to revisit on Day 4. |
| 2. The rules for jurors | 15 | Play the clip window. Pause to have students restate presumption of innocence and reasonable doubt in their own words. |
| 3. Two kinds of evidence | 15 | Run the sorter as a class poll and ask one student to defend a close call. Stress that both kinds carry equal legal weight. |
| 4. The state’s opening | 20 | Watch the window. Have pairs list what the prosecutor promises to prove before they type. |
| 5. The defense’s opening | 15 | Watch, then compare the two stories about the same night. |
| 6. First check-in | 10 | Quiet typing. Collect the students’ open questions to revisit on Day 3. |

### Day 2: Admitting Evidence and Direct Examination (about 90 minutes of station time, plus transitions)

| Station | Minutes | Teacher moves |
|---|---|---|
| 7. How evidence gets in | 10 | Explain foundation with a non-case example (a photo of a school fight). |
| 8. Direct examination and lay witnesses | 15 | Run the open-ended versus leading sorter. Ask students to rewrite a leading question as an open one. |
| 9. The 911 witness | 25 | Watch the window once, pausing at each step of the foundation. Then type. |
| 10. Hearing the 911 call | 20 | Give students a choice to listen with the screen off. Discuss sincerity as a class before they type; stress separating what they noticed from what can be proven. |
| 11. Texts and digital evidence | 20 | Introduce authentication and party statements. Ask who could testify to where a text came from. |

### Day 3: Cross-Examination and the Investigation (about 90 minutes of station time, plus transitions)

| Station | Minutes | Teacher moves |
|---|---|---|
| 12. Cross-examination | 10 | Define cross and leading questions. Ask why the defense asked the 911 director nothing. |
| 13. Body camera and first officers | 25 | Watch the window. Ask students to track what the defense says was not preserved or recorded. |
| 14. Cross of a family witness | 20 | Watch the window. Compare tone with the officer’s cross. |
| 15. Expert witnesses | 25 | Teach lay versus expert, then watch the clip. Ask students to name leading questions. |
| 16. Evidence ledger | 10 | Quiet work. Students sort direct and circumstantial evidence for and against. |

### Day 4: Closing Arguments and Your Verdict (about 85 minutes of station time, plus transitions)

| Station | Minutes | Teacher moves |
|---|---|---|
| 17. The defense rests | 10 | Explain the Fifth Amendment and why the burden never shifts. |
| 18. Closing: the state | 20 | Watch the window. Ask how the prosecutor links separate pieces. |
| 19. Closing: the defense and rebuttal | 20 | Read the defense closing coverage together, watch the rebuttal, then discuss which side was more effective. |
| 20. The law the jury applies | 10 | Go through the four charges. Emphasize prior calculation and design. |
| 21. Your verdict | 15 | Silent writing. Remind students the reveal opens only after they lock in. |
| 22. What the jury decided | 10 | Reveal, then discuss how verdicts compared and what procedure shaped their view. |

Switch students to *On my own* on any day they missed. The jump bar lets them go straight to that day.

## Video clips and time windows

Every clip shows a time window (for example “Watch 17:43 to 32:43”), and the player starts there and stops at the end time. A plain YouTube link sits under each player in case the player is blocked. Videos load only when a student clicks play (YouTube’s privacy-enhanced address), and the site makes no other outside requests.

I could not watch the videos or read their timestamps. **Only the start times of 17:43 (body camera) and 20:00 (sister-in-law) come from your assignment.** Every other window was chosen from the order of testimony in news coverage and is an estimate. Use the teacher tool to check and fix them.

| Station | Clip | Source | Window | Basis |
|---|---|---|---|---|
| 2 | Jury instructions from the judge | Trial video (YouTube) | 0:00 – 10:00 | estimated from the order of testimony |
| 4 | State’s opening statement and key exhibits | Trial video (YouTube) | 0:00 – 12:00 | estimated from the order of testimony |
| 5 | Defense counsel’s opening statement | Trial video (YouTube) | 0:00 – 10:00 | estimated from the order of testimony |
| 9 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 0:00 – 8:00 | estimated from the order of testimony |
| 10 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 8:00 – 18:00 | estimated from the order of testimony |
| 13 | Caleb Flynn bodycam footage: “Ashley’s Dead, She’s Gone” | Court TV | 17:43 – 32:43 | start 17:43 is from your assignment; the end is estimated |
| 14 | Caleb Flynn sister-in-law testimony | Trial video (YouTube) | 20:00 – 30:00 | start 20:00 is from your assignment; the end is estimated |
| 15 | Caleb Flynn’s defense clashes with crime scene agent | Court TV | whole clip | whole short clip: nothing to estimate |
| 18 | Prosecuting attorney Matt Joseph delivers closing arguments | Courtroom Insider (YouTube) | 0:00 – 12:00 | estimated from the order of testimony |
| 19 | Prosecuting attorney Paul Watkins wraps up closing with a rebuttal argument | Courtroom Insider (YouTube) | 0:00 – 8:00 | estimated from the order of testimony |

**To adjust a window:** open the site with `#teacher` at the end of the web address (for example `.../index.html#teacher`). A **Clip times** button appears at the top. Enter start and end times as m:ss, press **Preview** to check, and **Save here** to keep the change in that browser. **Copy list** gives you the values to paste into `index.html`, where each clip has `start:` and `end:` in seconds (search for the clip id, such as `id:"c9"`). Students never see the tool.

Which videos are confirmed: the 911 video and the body-camera video are published by Court TV, and the expert cross-examination clip is described on Court TV’s own library. The two closing-argument videos carry the Courtroom Insider tag. Four of the links in your assignments (jury instructions, the two opening statements, and the sister-in-law testimony) I could not independently confirm, and they are used as given. If any video is unavailable, the link under it will say so.

No video of the defense’s closing argument turned up, so Station 19 links two news pages that report it in detail and uses the state’s rebuttal clip.

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
3. After a minute the site is live at `https://YOUR-NAME.github.io/REPOSITORY-NAME/`. Add `#day2` (and so on) to a link to send students straight to a day.

Do not rename the repository after students begin, because their saved progress is tied to the web address.

## Privacy

No accounts, no tracking, and no outside services except YouTube when a student clicks play. Responses are stored only in the student’s own browser. Students turn work in by downloading the Word notebook and uploading it to Google Classroom.
