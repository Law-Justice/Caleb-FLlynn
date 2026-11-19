# Trial Lab: State of Ohio v. Caleb Flynn

A vertical, interactive timeline that walks high-school students through the procedure of a real jury trial, using the Miami County, Ohio trial of Caleb Flynn. Students act as jurors: they learn each step, watch a focused clip, type responses, and reach their own verdict **before** the site reveals what the jury decided.

It is built for **four class periods of about 70 minutes**, delivered as back-and-forth instruction (teacher guidance, student typing). A student who misses a day can switch to **On my own** and complete it individually.

> **Note for the teacher:** this file contains lesson timings and notes. If you publish the folder in a public GitHub repository and do not want students to read it, delete `README.md` before you upload. The site itself does not need it.

## What is in the folder

- `index.html` is the entire site (no libraries, no outside files)
- `screenshots/` shows what each part looks like
- `.nojekyll` tells GitHub Pages to publish the files as they are

## How it works

1. **Cover.** The student types a name and chooses *With my class* or *On my own*. The mode can be changed at any time from the bar at the top.
2. **Vertical timeline.** Four color-coded days and 19 stations, with a jump bar for each day. Cards stay small (icon, title, minutes, number of clips and questions).
3. **Each station has up to three steps:** Learn (key ideas and Ohio rules), Watch (a clip with a stated time window and “watch for” prompts), Respond (typed responses with a word counter and hints).
4. **Two ways to work.**
   - *With my class:* the longer explanations are collapsed because the teacher is covering them. Required responses are the questions from your assignments plus new ones. Discussion prompts are optional notes.
   - *On my own:* the full explanations are open, and discussion prompts become required typed responses.
5. **Verdict and reveal.** Station 18 asks for a vote on each charge and a written explanation. Station 19, with the jury’s verdict and sentence, stays locked until the student locks in their verdict. Nothing before it names the outcome.
6. **Word notebooks.** *Download Day N notebook* appears in each day’s header and in *My notebook*, and there is a complete notebook for all four days. A completion code is added at the end of each. Nothing is sent anywhere; the document is built in the browser.
7. **Courtroom guide.** A drawer with who’s who, the order of a jury trial (each step links to its station), key terms, and the charges.

Progress saves automatically in the student’s browser. It is tied to the device and web address, so a student should use the same computer to continue.

## Running each day

### Day 1: The Jury, the Evidence, and the Openings

Station time is about **63 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 1. The case in brief | 8 | Read the overview together and use the who’s-who table. Collect two first impressions on the board to revisit on Day 4. |
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

If you run short: have students answer only the questions in Station 10 that you choose, and finish the rest at the start of Day 3 or in *On my own* mode.

### Day 3: Witnesses: Texts, Cross-Examination, and Experts

Station time is about **64 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 11. Cross-examining a family witness | 10 | Watch the window. Compare the tone with the officer’s cross. |
| 12. Alleigha Botner: direct examination and the texts | 22 | Teach why a participant in the texts can authenticate them. Watch the reading clip first, then the two Court TV windows. Ask which three messages the state most needs. |
| 13. Cross-examining Alleigha Botner | 20 | Teach credibility and bias before the clips. After watching, ask what the defense could and could not get Botner to say. |
| 14. Expert witnesses | 12 | Teach lay versus expert, then watch the clip. Ask students to name the leading questions. |

This is the heaviest day. If you run short: skip the optional comparison question in Station 13 and let students finish Station 14 (the experts) at the start of Day 4.

### Day 4: Closing Arguments and Your Verdict

Station time is about **47 minutes**. In a 70-minute period that leaves about 3 minutes to launch (recap, open the site, set the mode) and 4 to wrap up (download the day’s notebook).

| Station | Minutes | Teacher moves |
|---|---|---|
| 15. Your evidence ledger | 6 | Quiet work. Students sort direct and circumstantial evidence for and against, now including the Botner testimony. |
| 16. The defense rests | 5 | Explain the Fifth Amendment and why the burden never shifts. |
| 17. Closing arguments | 15 | Read the defense-closing coverage together, watch the two clips, then discuss which side was more effective. |
| 18. Your verdict | 14 | Go through the charges, then silent writing. Remind students the reveal opens only after they lock in. |
| 19. What the jury decided | 7 | Reveal, then discuss how verdicts compared and what procedure shaped their thinking. |

This day has about 20 spare minutes. Use them for a mock jury deliberation: groups of four argue each charge using their evidence ledgers before anyone locks in a verdict, or for a longer debrief after the reveal.

Switch a student to *On my own* on any day they missed. The jump bar lets them go straight to that day.

## The Alleigha Botner stations (Day 3)

Stations 12 and 13 follow the pattern of your assignments (a goal, clips, and headed question groups). Station 12 covers her direct examination and the text messages: why a participant in the messages can authenticate them, why the state had her read them aloud, what the state wants jurors to infer, and how “Actions will come tomorrow” can be read two ways. Station 13 covers the defense cross-examination by Emily Smith: bias and motive, her admission that she lied in her first FBI interview, her online searches, and how the defense reframed Flynn’s messages. The cross-examination questions deliberately echo your “Analyzing the Cross Examinations” question by asking students to compare this cross with the officer’s and the sister’s.

Some messages in her testimony use harsh language about a real person. The site paraphrases them and shows a note on the Watch step. Her full testimony ran almost seven hours over September 23 and 24, so the clips are short Court TV segments plus one clip of her reading the texts.

## What changed from the three-period version

I added the two Botner stations, restored the stand-alone evidence-ledger station, and moved to four periods. All 23 questions from your three assignments are still in, word for word.

## Video clips and time windows

Every clip shows a time window (for example “Watch 17:43 to 27:43”), and the player starts there and stops at the end time. A plain YouTube link sits under each player in case the player is blocked. Videos load only when a student clicks play (YouTube’s privacy-enhanced address), and the site makes no other outside requests.

I could not watch the videos or read their timestamps. **Only the start times of 17:43 (body camera) and 20:00 (sister-in-law) come from your assignment.** Every other window was chosen from the clip’s title and description or from the order of testimony in news coverage, and is an estimate. Use the teacher tool to check and fix them. The Botner Court TV clips are short themed segments (10 to 32 minutes in Court TV’s library), so the beginning of each clip should hold the topic its title names.

| Station | Clip | Source | Window | Basis |
|---|---|---|---|---|
| 2 | Jury instructions from the judge | Trial video (YouTube) | 0:00 – 5:00 | estimated from the clip description or the order of testimony |
| 4 | State’s opening statement and key exhibits | Trial video (YouTube) | 0:00 – 8:00 | estimated from the clip description or the order of testimony |
| 5 | Defense counsel’s opening statement | Trial video (YouTube) | 0:00 – 6:00 | estimated from the clip description or the order of testimony |
| 8 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 0:00 – 8:00 | estimated from the clip description or the order of testimony |
| 9 | Caleb Flynn breaks down hearing his own 911 call in court | Court TV | 8:00 – 16:00 | estimated from the clip description or the order of testimony |
| 10 | Caleb Flynn bodycam footage: “Ashley’s Dead, She’s Gone” | Court TV | 17:43 – 27:43 | start 17:43 is from your assignment; the end is estimated |
| 11 | Caleb Flynn sister-in-law testimony | Trial video (YouTube) | 20:00 – 28:00 | start 20:00 is from your assignment; the end is estimated |
| 12 | “Actions Will Come Tomorrow”: Alleigha Botner reads Caleb Flynn’s texts | Trial clip (YouTube) | whole clip | whole short clip; publisher not confirmed |
| 12 | Caleb Flynn wished he could kill his wife, not go to jail: Mistress | Court TV | 0:00 – 5:00 | estimated from the clip description or the order of testimony |
| 12 | Pastor’s mistress reveals his first words after wife’s murder | Court TV | 0:00 – 4:00 | estimated from the clip description or the order of testimony |
| 13 | Caleb Flynn’s mistress believed he killed his wife | Court TV | 0:00 – 5:00 | estimated from the clip description or the order of testimony |
| 13 | Pastor’s mistress admits she resented his wife | Court TV | 0:00 – 7:00 | estimated from the clip description or the order of testimony |
| 14 | Caleb Flynn’s defense clashes with crime scene agent | Court TV | whole clip | whole short clip: nothing to estimate |
| 17 | State’s closing: Prosecuting attorney Matt Joseph | Courtroom Insider (YouTube) | 0:00 – 6:00 | estimated from the clip description or the order of testimony |
| 17 | State’s rebuttal: Prosecuting attorney Paul Watkins | Courtroom Insider (YouTube) | 0:00 – 5:00 | estimated from the clip description or the order of testimony |

**To adjust a window:** open the site with `#teacher` at the end of the web address (for example `.../index.html#teacher`). A **Clip times** button appears at the top. Enter start and end times as m:ss, press **Preview** to check, and **Save here** to keep the change in that browser. **Copy list** gives you the values to paste into `index.html`, where each clip has `start:` and `end:` in seconds (search for the clip id, such as `id: "cb2"`). Students never see the tool.

Which videos are confirmed: the 911 video, the body-camera video, and the Botner clips labeled Court TV carry Court TV titles that match Court TV’s own library and Facebook page. The expert cross-examination clip is described on Court TV’s library. The two closing-argument videos carry the Courtroom Insider tag. The clip of Botner reading the texts (Station 12) comes from a channel I could not identify. Four of the links in your assignments (jury instructions, the two opening statements, and the sister-in-law testimony) I could not independently confirm, and they are used as given. If any video is unavailable, the link under it will say so.

Law&Crime Trials posted the full direct examination and the full cross-examination of Botner, and Court TV’s library lists a 59-minute full cross-examination. I did not use the full versions because I could not find where each topic begins inside them. To use a different video, replace the `yt:` value for that clip in `index.html` and set its `start:` and `end:`.

No video of the defense’s closing argument turned up, so Station 17 links two news pages that report it in detail and uses the state’s rebuttal clip.

To turn all videos off, search `index.html` for `videos:true` and change it to `videos:false`.

## Accuracy notes

Facts come from reporting by CNN, ABC News, CBS News, NBC News, the Dayton Daily News and affiliates, WHIO, WLWT, NewsNation, Court TV and Courtroom Insider, and Ohio law as cited in appellate opinions.

- **Trial status.** Your assignments describe the trial as ongoing. It has finished: jury selection began Sept. 17, 2026, openings were Sept. 18, Botner testified Sept. 23 and 24, the state and defense rested Sept. 28, closings and the verdict were Sept. 29, and sentencing was Oct. 5. The site is built so students decide first and see the outcome last.
- **Botner’s testimony.** She is 24 and testified for the state for almost seven hours. The state said she and Flynn exchanged about 107,000 messages. Reports differ on one quotation: some outlets give Flynn’s remark the morning after as “the way I thought it would” and others “the way we thought it would,” so the site paraphrases it. Defense attorney Emily Smith conducted the cross-examination. Botner has not been charged and testified she was promised nothing.
- **Counts.** Some outlets say 11 charges. Two misdemeanor intimidation counts were dismissed before the verdict. The jury returned verdicts on nine counts.
- **Deliberation length.** Reports range from about two hours to two and a half hours. The site says so.
- **Reasonable doubt.** Ohio’s statute (R.C. 2901.05) says jurors must be firmly convinced of “the truth of the charge.” Your assignment quotes it as “the defendant’s guilt.” The site uses the statute’s wording.
- **Expert witnesses.** The BCI crime-scene agent, the BCI firearms examiner, and the digital forensic examiners gave opinions based on specialized training. The site calls them expert-type witnesses and does not claim anything about how each was formally qualified.
- **The 911 center director.** Your assignment says the defense asked no questions of this witness, and the site follows your assignment.
- **Ohio rules cited:** R.C. 2901.05; 2903.01; 2903.02; 2903.11; 2921.12; Ohio Evid.R. 401, 602, 607, 611, 701, 702, 801(D)(2), 901; State v. Jenks, 61 Ohio St.3d 259 (1991); Griffin v. California (1965).

## Updating the site without losing student progress

Progress is saved in each student’s browser under one key (`CFG.key`, near the top of `index.html`). This version carries over saves from the earlier versions of the site automatically: the first time a student opens the new page, any earlier save is merged into the current one. Their name, working mode, quick-check answers, and every response they typed are kept, and if a prompt exists in two saves the longer text wins, so nothing a student wrote is lost. The old save is left in place as a backup.

To keep this working:

- **Upload the new `index.html` to the same repository, with the same name, so the web address does not change.** Progress belongs to the address, so a new address or a renamed repository starts every student from zero.
- **Do not change `CFG.key`, and do not change the `id` of an existing station or question.** Responses are stored by question id. Adding new stations is safe. Removing a station leaves its old responses in the browser but they no longer appear in notebooks.
- Students must use the same browser and device. Clearing browser data erases progress.
- Day 1 is unchanged by this update. Day 1 stations and questions keep their ids, so a student who has started or finished Day 1 sees all of it exactly as they left it. The new Botner stations are on Day 3.
- “Downloaded” markers from earlier versions are reset (the notebook can simply be downloaded again).

## Publishing on GitHub Pages

1. Create a repository and upload `index.html` and `.nojekyll`.
2. In the repository, open **Settings, then Pages**, choose the **main** branch and the **/ (root)** folder, and save.
3. After a minute the site is live at `https://YOUR-NAME.github.io/REPOSITORY-NAME/`. Add `#day2` (and so on) to a link to send students straight to a day.

Do not rename the repository after students begin, because their saved progress is tied to the web address.

## Privacy

No accounts, no tracking, and no outside services except YouTube when a student clicks play. Responses are stored only in the student's own browser. Students turn work in by downloading the Word notebook and uploading it to Google Classroom.
