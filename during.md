# During the Sprint

- **Set up a place for shared note-taking.**
  This document should be visible to all participants
  and persist beyond the end of the sprint.
- **Run a "sprint primer" session.** A primer session helps contributors get oriented with the structure of your lesson and its associated repository,
  the setup required to work on the lesson
  (e.g. local builds to preview lesson webpages),
  and the communication channels that will be used during and in-between the sprint sessions.
  You could run this primer session a day or two before the sprint begins,
  or as the first session of the sprint event itself,
  before co-working sessions begin.
- **Hold regular, scheduled check-ins** to allow contributors to report
  on their progress, including what they've achieved,
  what's blocking their progress,
  and what they intend to do next.
- **Record the check-ins.**
  If technically possible, and provided all participants consent,
  record these check-ins so that those who could not join can catch up
  on the latest progress when they (re-)join the sprint.
  This is particularly important for sprints taking place
  across multiple sessions/days and/or a wide range of timezones.
  If you cannot record the check-in discussions,
  make sure to take extensive notes in a shareable location.
- **Assign roles for check-ins.**
  To ensure everyone has an equal chance to contribute to the discussion
  and the sprint,
  the lead organiser(s) should assign meeting roles for the check-in calls.
  To further promote equity of participation,
  these roles should be rotated for each day of the sprint,
  or each separate sprint event.
  Roles may include:
  - a _Facilitator_ who coordinates the discussion and keeps it moving,
    watching out for raised hands and making sure those with something to contribute
    get the chance to do so;
  - a _Timekeeper_ who monitors the time remaining for the check-in and
    ensures that all topics are covered in a timely fashion.
    The Timekeeper prompts the
    Facilitator/speaker to move on when necessary to cover everything.
  - an _Issue/Task Creator_, who keeps track of actions that arise
    from the check-in discussion and creates an issue or
    describes the task in the shared notes.
  - a _Notetaker_, who takes minutes of what is discussed in the check-in.
    In some instances, it may be possible to combine the roles of Notetaker and Task Creator.
- **Make note of who is working on/is going to work on what.**
  This helps to avoid duplication of effort during the sprint,
  and gives participants a way of coordinating additional discussions
  among themselves where appropriate to make progress on a task.
- **Use a chat channel for communication outside check-ins.**
  To allow participants to "unplug" from video calls/move to separate locations for the bulk of the sprint,
  use a text-based chat such as Slack or Gitter for discussion when not
  checking in.
  If your chosen platform allows it, minimise global notifications
  to sprint participants by making use of threaded conversations.
  This will allow contributors to focus on their chosen task unless involved in
  a conversation directly relevant to them.
- **Prepare breakout rooms for small group discussion and co-working between check-ins.**
  **[Online]** Open a small number of break out rooms for sprint participants to use during working sessions.
  This allows the participants to self-organize if they need to discuss something they are working on or co-work on a particular task.
  In Zoom, select the option to "Let participants choose room".
  For **[in-person]** sprints, prepare an equivalent set of different rooms/locations
  for participants to gather and discuss in smaller groups without fear of
  disturbing the whole team.
- **Provide a way for contributors to mark their work ready for review.**
  If you prefer to require material is reviewed before being included in the lesson,
  give participants a way to signal when their contributions are ready.
  You might consider providing guidance/assigning responsibilty for reviewers
  of particular sections/types of contribution.
  If your lesson is being developed on GitHub, see the section below for more
  specific recommendations.
- **Record information about participants and contributions.**
  Prompt participants to add their details to the shared notes,
  so you can refer to it later and ensure everyone's contributions are recorded.
  Information to collect might include names, affiliations, preferred pronouns,
  Orcid identifiers, GitHub usernames, and any other identifiers/handles that
  are relevant or frequently used in your domain.
  You may also wish to record the different ways in which participants are
  contributing to the lesson during the sprint, to ensure proper credit is
  given later e.g. when publishing the lesson.
- **Complete any remaining reviews.**
  Sprints often end with an influx of new material, as contributors finish up what they were working on as the event closed.
  Other material developed earlier in the sprint may be awaiting review.
  Making sure that these are reviewed and (where appropriate) merged into the lesson
  ensures contributors develop a sense of accomplishment from the sprint,
  and ties up any loose ends before new tasks are taken on to develop the material further.
  If the participants who were originally assigned to review have had to leave,
  the organisers should take over responsibility for these reviews to ensure they
  are completed in a timely manner.

## Recommendations for GitHub

- **Consider running a skill-up session for contributors.**
  Depending on their previous experience with the platform,
  contributors may benefit from learning/being reminded how to use GitHub,
  working on branches/forks,
  and the associated tools on their local system.
  Providing a session/resources on this will also make your sprint less
  intimidating for newcomers to lesson development,
  which may increase participation.
  [GitPod](https://gitpod.io/) may offer a way for participants to contribute to the lesson
  without the need for setting up a local development environment.
  As with the "primer" session mentioned above,
  this skill-up may fit best at the beginning of the sprint,
  before the first co-working session begins, or as a separate event
  that takes place in the days leading up to the full sprint.
- **Flag pull requests as draft and ready for review as you work.**
  Opening draft pull requests early, while work on a task is ongoing,
  can help contributors understand where progress is being made and identify
  tasks/issues that still need to be tackled.
  Marking pull requests as ready for review helps maintainers prioritise their
  focus during the sprint and maintains momentum by ensuring that completed work
  is merged into the lesson as soon as possible.
  Opening draft pull requests is particularly important at the end of a sprint,
  to capture progress up to that point even if a task hasn't yet been completed.
- **Plan who will review pull requests.**
  Make a plan for who will review each pull request.
  As a group you can create list of reviewers by subject so the person who opens the pull request knows who is interested and capable of reviewing and can request a review accordingly.
  Alternatively, you may decide on a circle of reviewers. E.g. Aaliyah reviews Juan's PRs, Juan reviews Alex's PRs, and Alex reviews Aaliyah's PRs.
  Another option might be to ask for a reviewer when planning who will do the task.
  For particularly small groups where reviewing is more likely to become a bottleneck, or in cases where the main objective of the sprint is to create quantity rather than quality, you may decide it is acceptable for contributors to merge their own pull requests.
- **Link pull requests to open issues.**
  Mentioning open issues in pull requests (even when a work in progress)
  informs people about which issues are being worked on.
  As mentioned in the point above, this is particularly useful to ensure progress
  can continue on the lesson after the sprint has finished.
- **Record contributions that do not (directly) result in commits.**
  Some participants may be more comfortable writing matrial on a different platform
  e.g. Google Docs, which is later transferred to GitHub by someone else.
  Make use of GitHub's [commit co-author](https://github.blog/2018-01-29-commit-together-with-co-authors/) feature where possible or,
  if the author does not have a GitHub account,
  make sure their name and other details are included in your README, AUTHORS,
  or any other listing/metadata about contributors to the project
  (`.zenodo.json`, `.allcontributorsrc`, etc).
- **Review open pull requests.**
  At the end of the sprint, organisers should ensure that any pull requests marked as ready for review are processed and (where appropriate) merged,
  so that these contributions are not forgotten or left to go stale before changes can be requested.
