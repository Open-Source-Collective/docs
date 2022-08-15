---
description: Ensuring that the project can survive its contributors
---

# Promoting maintainers and handling conflict

This is a guide based on several Open Source Collective workshops led by Sumana Harihareswara of Changeset Consulting in early 2022. It focuses on skills in handling conflict, addressing difficult issues, and recruiting and promoting maintainers for Open Collective-hosted open source software projects.

### Handling conflict and tackling difficult issues

#### You can do this

We all develop skills in handling interpersonal conflict and dealing with sticky issues. You can use the skills you already have and bring them into your open source work.

Sometimes it feels like open source is an odd world, neither exactly like a workplace nor like a friends-and-family setting. But it has aspects of both, so when you need to resolve conflict, you can consider approaches you would use at work and approaches you would use with family and friends.

In a small team, it might feel very risky to bring simmering conflict out into the open, for fear of losing contributors and endangering the project. And, if the team is small, or the subset of the team that is willing to engage in confrontation or reconciliation is small, you might fear that you do not have the critical mass to persuade someone to behave differently, or to keep the project going if they leave. Or you might just have no one to talk with about what to do. In that case, consider talking with other OSC collective maintainers in the [OpenCollective Slack](https://opencollective.slack.com) to share perspectives and think about a path forward.

#### Systems and relationships

When you're dealing with a difficult person or issue, remember that you can use both _systems_ and _relationships_.

On the systemic level, you can use and create social and digital structures to help encourage people to treat each other well, and mitigate the effects of people rubbing each other the wrong way. For example, you can add moderation to forums and issue discussion platforms. You can create a word or time limit, to reduce the soapboxing that any one person can force on the rest of the group. You can work to build a code of conduct and/or a Values statement to create a shared set of expectations for how people should treat each other, and use that to support the slow work of coaching or removing someone whose behavior isn't up to the standard. You can refocus someone's energy by offering them a badge and a committee so they can dig into the topic they're passionate about (while reducing friction with others).

You can also work using interpersonal relationships, talking privately (in text or audio/video chat) with specific people, including people who are proving difficult. Ask them for context and advice about how the project should be handling issues -- if you have private discussions with several different people, with different points of view, you'll often get insight into the underlying tensions that are causing conflict, and can address those causes. You can also, in private, sometimes ask questions that would look like sideswipes if you asked them in public, such as: "if you were new and you saw what you just wrote, would you feel it was welcoming?" -- as long as you genuinely follow up those questions with discussion.

If you have a working relationship with someone who is abrasive to a lot of their peers, and their uncongenial behavior is causing problems, you may be able to have a frank conversation with them to help them understand that their abrasiveness is making them less effective. As someone once told Benjamin Franklin (per Dale Carnegie's paraphrase in _How To Win Friends and Influence People_):

> Ben, you are impossible. Your opinions have a slap in them for everyone who differs with you. They have become so offensive that nobody cares for them. Your friends find they enjoy themselves better when you are not around. You know so much that no man can tell you anything. Indeed, no man is going to try, for the effort would lead only to discomfort and hard work. So you are not likely ever to know any more than you do now, which is very little.

And: when you're having trouble handling someone who really gets under your skin, consider that they might be really bothering you because of ways they remind you of yourself. They may have a lot of your strengths but be taking them in an antisocial direction. Recognizing that can help you get a better handle on your own feelings so you can act productively.

### Recruiting and promoting maintainers

To grow the number of maintainers for your project, you need to consider retaining and growing the contributors you already work with, using both systematic process and your own relationships with potential maintainers. Some steps here are similar to steps you can take to increase how many contributors you have and the quality and frequency of their contributions.

#### Assess contributor retention

If existing contributors are stagnating or leaving instead of staying and getting promoted, it probably makes sense to focus on increasing retention before increasing inflow. That's what [Wikipedia and its sibling projects realized](https://strategy.wikimedia.org/wiki/Product\_Whitepaper#Great\_Movement\_Projects:\_Rich-text\_editing\_interface,\_and\_the\_-1\_to\_100\_edit\_experience) when facing a decline in contributions around 2011. English Wikipedia was getting people in the door to edit for the first time, but they often bounced off the process and stopped somewhere in their first dozen edits. So Wikimedia analyzed why, launched experiments, and worked to smooth obstacles that were getting in the way of retention.

Consider your "engagement funnel" -- what stages a contributor passes through to become a core member of your team. On Wikipedia, the stages could be summarized as going from "-1" to "100":

1. "-1": the user doesn't even realize they _could_ edit Wikipedia.
2. "0": the user realizes they could, but haven't done so yet.
3. "1": the user has made their first edit, getting over their own hesitation and any technical obstacles.
4. "10": they've made 10 edits, which means they've successfully dealt with any unpleasant social interactions stemming from their first few edits.
5. "100": they've made 100 edits, so they're thoroughly used to the technical side and the social side of editing, and may have taken leadership of a topic area.

Try a similar assessment of your contributor base, putting your contributors in buckets based on how many times they've contributed. When you're finding potential maintainers to recruit, nurture, and promote, it's most productive to focus on users who already know the terrain, such as people who have made 10-100 contributions. (Think outside the box: these contributions might include translations, useful replies on an email list, good bug reports, or independent blog posts or StackOverflow replies.)

**Patterns in your promising contributors**

Spend five to twenty minutes to review the most promising contributors (who aren't already maintainers) you've had in your project, and think about their work and their judgment. What do they concentrate on? Are they better than you at anything? What would it take for you to entrust them with maintainer privileges?

#### Approaches to retain and upskill existing contributors

_Provide alternate structures for high-quality contributions from strong contributors._ One reason to promote contributors to co-maintainer is to get their expert advice and input more frequently, but in many cases, you don't have to share code commit privileges for the repository to share power and get input. Provide alternate structures for contribution:

* Give users privileges to triage issues in your bugtracker. Once you know a user has reasonable judgment, can take feedback well, and understands your project's features and workflow better than most users do, go ahead and give them privileges to resolve, close, merge, label, or assign issues.
* Do you have a private group chat that's only for the core team? Consider allowing the most productive contributors and helpful users in there even if they're not part of the core team. Social bonding using chat, video calls, meetups, and similar unstructured or semistructured gatherings can help people feel like part of a team, and cement their desire to help their friends make progress.
* Some people who inconsistently contribute have insufficient time to be official core contributors. Consider suggesting to them that they use another developer as a proxy, someone who can take their ideas as starting points and co-author the finished patches.
* Some contributors are subject matter experts in particular areas. You can create 3-5 person "tiger teams" or "advisory committees" of people who are specialist experts. Through meetings or through labels and notification settings, you can ask for those teams to review specific issues and patches, and possibly even give them final sign-off power.

_Ask them to review patches/pull requests._ Even before someone is a core team member with privileges to merge code into the main branch, their reviews can help find easy-to-notice problems, help them learn how the codebase works, and save time for other reviewers.

You can use technical tooling to help contributors get notified to review PRs. You can extend GitHub's functionality using labels, subteams, and tools like [zulipbot](https://github.com/zulip/zulipbot) to \[create teams and improve the specificity of notifications]\((https://zulip.readthedocs.io/en/latest/contributing/zulipbot-usage.html). Or: [carsonbot is an issue bot for the Symfony project that helps automate different issue and pull request workflows.](https://github.com/symfony-tools/carsonbot) Depending on who has write permissions to the repository, you may also be able to use a `CODEOWNERS` configuration file for GitHub automation (see [GitHub documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)). You could also develop tooling to automatically ping appropriate reviewers for each patch based on reviewers' commit history touching those files, but be cautious, as errors with this can lead to notification fatigue and reviewers feeling nagged.

_Personally invite them._ Many contributors assume that it's impolite to ask for maintainer privileges, and assume that they'll be invited if they're good enough. If you're not sure whether someone's interested, and you think they're a strong contributor, go ahead and ask them -- personally, not with a form letter.

_Follow up on interest systematically_: You don't have to manually remember whom you're trying to recruit and how they're doing. Check out what Asheesh Laroia and his colleagues in Debian did with [the Debian New Members site](https://nm.debian.org/), which is basically [a Trello board to track the progress of applicants and see whom to ping/remind](https://nm.debian.org/process/).

#### Approaches to attract new maintainer-track contributors

You can recruit people who aren't yet contributing to your project, and in particular, you can do this in a way that increases the chances those people will be future co-maintainers.

_Mentor interns_. Use Outreachy, Google Summer of Code, and similar mentorship programs. During internships, [ask your interns about their career plans](https://changeset.nyc/resources/career-advice-open-source-interns/) so you can help them find ways to pursue their career goals while continuing to contribute after the end of the internship; outline for them how they could become co-maintainers and how this would help them in their careers. [Continue to actively engage with your intern alumni after the internship](https://harihareswara.net/posts/2014/the-continuing-adventures-transitioning-from-intern-to-volunteer/).

_Hire contractors_. You can hire a contractor who is reasonably skilled in a domain relevant to your project, and work towards getting them knowledgeable enough about your specific project that everyone can feel comfortable promoting them to co-maintainer. Then, when you have available money again in the future, you can hire the contractor again to help speed up project work.

#### Exercise: make a draft plan to promote someone

Imagine that you are considering promoting an existing contributor to co-maintainer. Plan it out. What are your criteria? What schedule would you expect? What privileges would you offer, and in what order?

For some projects, this is a very quick process with a fairly low bar. They'll offer maintainer privileges to all consistent contributors, as long as they have good judgment and are in frequent communication with the rest of the core team. They look for enthusiastic contributors who have created issues and/or pull requests, and who continue to stick around and communicate after their first few PRs.

It's okay to have a more deliberate process; maybe you'd like a potential maintainer to take a week or two to shadow a current maintainer while they reply to issues and review patches before you give them the keys. Or maybe you are more willing to share the chat moderation and social media posting privileges than you are to enable someone to upload a new release tarball/executable.

Whether your plan would be 4 steps over four weeks or fifteen steps over eighteen months, having an outline will help you -- and candidates -- understand what to expect.
