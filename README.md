# KAIST Concurrency and Parallelism Laboratory

## What is Research?

> "Research is what I am doing when I don't know what I am doing," Wernher von Braun

The defining characteristic of research is everything---from motivation to methods to evaluation to
goal---is tentative: in the middle of doing research, you don't know what will be the end result. As
a consequence, a researcher will suffer from:

- **Failure everyday**. You don't know what you're doing, so you'll fail almost always. To deal with
  the frustration from such failures, you should be mentally tough enough to tolerate such
  frustration. If successful, from time to time you will be able to understand or design small
  things, which accumulate to a paper and a thesis.

- **Changing plans**. You don't know what you're doing, so your goal will be changing as you make
  progress on your project. So any long-term plan is destined to be significantly revised. Thus you
  should think of the goal as a ever-moving target, the current version being just the best possible
  approximation of the actual end result. Your goal should be neither too concrete nor too abstract:
  if too concrete, it will not be resilient to the revision; if too abstract, it will not guide your
  research.


## Communication

All communication (except for Mattermost and face-to-face meeting) is **asynchronous**: the receiver
is not required to reply promptly. Mattermost chat in work hours is supposed to be synchronous: the
receiver is requested to reply promptly.


### Registration

When you first come to the lab, please do the following instructions:

- Create {firstname}.{lastname}@kaist.ac.kr email account.
    + You can add "additional account" in mail.kaist.ac.kr > Settings > My Account > Additional account.
    + If it is already taken, add a number at the end of the id, e.g. {firstname}.{lastname}07@kaist.ac.kr
- Send your email address and GitHub ID to jeehoon.kang@kaist.ac.kr.
- Your GitHub ID will be invited to `kaist-cp` organization.
- You'll get {firstname}.{lastname}@cp.kaist.ac.kr G Suite account.
- You'll get a Mattermost account in [https://cp.kaist.ac.kr/mm](https://cp.kaist.ac.kr/mm).


### Email

- Use {firstname}.{lastname}@kaist.ac.kr email account for all work emails.
- Forward all {firstname}.{lastname}@kaist.ac.kr emails to {firstname}.{lastname}@cp.kaist.ac.kr and
  check emails in [Gmail](https://www.gmail.com).
- Configure the Gmail account to send from {firstname}.{lastname}@kaist.ac.kr.
- Write [proper formal emails](https://www.wikihow.com/Write-a-Formal-Email).
- Try to reply within 12 hours.


### Calendar

- Use {firstname}.{lastname}@cp.kaist.ac.kr account for calendar and other G Suite applications.
- If you want to have a meeting, just directly invite the others in [Google
  Calendar](https://calendar.google.com). In the invitation, write the purpose of the meeting.


### GitHub

- All work should be done in the [`kaist-cp` organization](https://github.com/kaist-cp).
- If you want to create a new repository, ask Jeehoon.
- Get email notification for mentions and issue/PR comments.


### Mattermost

- Instant messaging service at https://cp.kaist.ac.kr/mm.
- Try to reply promptly in work hours. (No need to reply in other times.)
- At the beginning of each work day, briefly state what you'll do that day at [this
  channel](https://cp.kaist.ac.kr/mm/cp/channels/one-line-a-day).


### Face-to-face meeting

- Before asking for a meeting, write down a short meeting agenda and share it.

- In the agenda, clearly state the purpose of meeting.  It can be, but not limited to: (1) reporting
  the progress, (2) asking questions/opinions, or (3) just chatting.

- Try to be direct, top-to-bottom, and conclusion-first (e.g. not "A, so B, so C", but "C, because
  B, because A").

- If you have multiple things to discuss, enumerate them at the beginning of a meeting for better
  planning of the meetings.



## First things to do

- Create your website at https://cp.kaist.ac.kr/{firstname}.{lastname}.
  1. Fork [our website repository](https://github.com/kaist-cp/kaist-cp.github.io) and clone it.
  2. Install dependent libraries and run a local server to test by following commands:

        ```bash
        # Make sure Ruby is installed.
        $ bundle install
        $ bundle exec jekyll serve
        ```

  3. Add your meta information(name, status, github ID, etc.) to `people.yml`.
  4. Make a new file `{firstname}.{lastname}.md` under the directory `_people/`.
  5. Write your concrete information on the `{firstname}.{lastname}.md`. I recommend you refer to `_people/jeehoon.kang.md`.
  6. Make a commit, push it and PR.
- Make sure you know how to use Git. FYI, [this tutorial](https://www.atlassian.com/git/tutorials) is a good introduction.
- Study the following programming languages depending on your research interest:
  + [Rust](https://www.rust-lang.org/), or
  + [Coq](https://coq.inria.fr/) (by reading [Software Foundations](https://softwarefoundations.cis.upenn.edu/) Volume 1).
