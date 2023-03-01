# Growing Your Contributors

_This is a guide based on an Open Source Collective workshop led by Sumana Harihareswara of Changeset Consulting in February 2022. It focuses on growing contributor bases for Open Collective-hosted open source software projects._

### First, an overview: engagement/retention funnel

![A figure showing the contributor funnel, with more users, fewer contributions, even fewer maintainers, and ultimately a large emerita base. Along the way, attrition lessens the pipeline, with the crux of the funnel being the maintainers.](<../.gitbook/assets/People Flow.png>)

Here's a diagram describing how open source projects engage, retain, and lose people. You may recognize this as an "engagement funnel"; projects attract users, some of whom convert into contributors, and some of those convert into maintainers. (This diagram oversimplifies; some contributors were not initially users.) And eventually, maintainers leave or step down; some of them disappear while some remain in the project spaces.

A key thing to notice here is that _retention_ is possibly more important than attracting contributors in the first place. Attracting new contributors without working to retain existing contributors can be a waste of effort; the funnel is a leaky sieve. Some attrition is normal and inevitable -- we don't know precisely how much, and this is the sort of thing researchers are figuring out -- but if you've never made an effort to retain contributors, there's probably some room for improvement.

For instance, to help retain infrequent contributors who have stopped initiating contribution but still respond to questions and requests, you can set up expert teams focusing on specific topics/domains and suggest that people join those teams. This makes a way for those contributors to stay connected and keep providing expertise, and sometimes -- spurred by a conversation -- they'll go on to do work on relevant issues.

### Why grow?

Instead of reflexively thinking "growth = good," it's worth stepping back and considering what specific problems you could solve, or opportunities you could use, with a larger contributor group. What capabilities would help your project in new ways? Examples:

* to accomplish a project roadmap faster
* to increase marketing and developer relations capacity, so that more people will talk about the project in various settings and and attract more contributors and sponsors
* to increase maintainer capacity and [improve bus factor](https://harihareswara.net/posts/2015/how-to-improve-bus-factor-in-your-open-source-project/), e.g., get comaintainers to co-lead so an existing maintainer can step back a bit or entirely and deal with burnout
* to increase general project resilience, e.g., get less dependent on 1-2 companies which currently provide most of the work

Thinking about your goals can help you focus your retention and recruitment efforts.

### Specific things you can do

Retain your existing contributors by better understanding what they want and need.

Make a list of some high-potential contributors, e.g., 10 people who have contributed in the past year, and start making specific plans to talk with them:

* Find out more about what they want, why they are contributing to the project, and how you can help them with that. For example, if an engineer is contributing to your project to learn a new language, ask whether she'd like to explore using newer language features in the project.
* Ask them for advice; this not only gets you useful advice, but conveys to them that you value their opinion.
* Make some synchronous social/chat or coworking times available, such as online chat, videocalls, livestreams or open Jitsi/Zoom videocalls. Consider a more low-key structure such as "let's all cowork together", or set up a recurring stream (YouTube/Twitch) where you work on the project, show your environment setup and take questions. Or lead a more discussion-centric "office hours"/"open hours" chat, which can be "about anything" or carry a loose agenda such as "questions about the recent release". (This can also help you constructively funnel discussion of a particular current controversy.) This helps contributors who are interested in friendship grow into friends through increased conversation, proximity, and consistent interaction. Contributors with social ties to a project are more likely to stick around.

Recruit new contributors by easing their path to contribution and making it easy for them to find you and feel welcome.

* Check that you have a guide or checklist for new contributors, and work through it yourself to ensure it's reasonably complete.
* Pay for a [developer experience audit](https://changeset.nyc/resources/installation-audit.html) in which a new contributor tries to get your development environment up and running, and documents or fixes all the snags along the way. Example vendors to hire for this: [Open Tech Strategies](https://opentechstrategies.com/), [Maintainer Mountaineer](https://maintainer.io/), [Changeset Consulting](https://changeset.nyc/), [pubstruct](https://pubstruct.com/), or [Galaxy Rise](http://www.galaxyriseconsulting.com/). If you can't afford to pay, ask new contributors to [write a tech discovery report](https://diff.wikimedia.org/2014/03/25/seeing-through-the-eyes-of-new-technical-contributors/), and use it to fix problems they ran into. Try to get a fresh audit from new contributors regularly, perhaps every 6 months, to keep up with changes -- in your own setup process and in the larger world (operating system upgrades, etc.).
* When you do outreach, leverage the power of groups. Find local meetups/colleges/universities and offer "intro to open source contribution" workshops with them. This way, you can recruit groups of people who will consider your project special because you are local, And, since people like to hang out with their friends, getting a pre-existing friend/social group into your project increases the of likelihood of retention for the whole group.
* Personally invite individual users or other potential contributors to contribute; some people don't feel comfortable showing up and trying stuff unless someone invites them.
* Create structured opportunities for new contributors to interact with you and come aboard. You can join well-known apprenticeship programs like [Google Summer of Code](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) and [Outreachy](https://www.outreachy.org/), or run courses like [Drupal Ladder](https://slidedeck.io/fureigh/get-more-contributors), but even if you don't have the dedicated mentorship time for those efforts, you can try smaller initiatives. For example, to improve communication and grow relationships, run regular "PR test Fridays" -- every Friday, make experts available who will help newcomers walk through how to test pull requests and help with the code review load.
* Every few days, look at recently merged pull requests and patches, and thank contributors and ask them whether they'd like a next issue to work on. Per [Mozilla's analysis of new contributor trends](https://wiki.mozilla.org/Contribute/analysis) (see [the "Measuring Engagement" presentation for more details](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g4435d357b\_20)), this kind of invitation within 24-48 hours is much more likely to retain the contributor's momentum and enthusiasm than if you wait a week. In fact, constructive criticism that arrives quickly is more likely to keep the contributor engaged than uniformly positive feedback that takes a week to arrive!
* If you have trouble keeping up with GitHub notifications to make sure you get reminders to review new pull requests, you can extend GitHub's functionality using tools like [zulipbot](https://zulip.readthedocs.io/en/latest/contributing/zulipbot-usage.html) to create teams and improve the specificity of notifications.
* If you have many incoming newbies, create regularly scheduled or ongoing spaces for new contributors to get help. For instance, in your chat, create a "new contributors" channel and ask existing volunteers to form a team to help find them a first task and onboard them. As an example, see [the Teahouse at English Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Teahouse/About) which helps new contributors acculturate to Wikipedia norms. Also see the videocall/chat/stream suggestion from the retention section above.

As you recruit new volunteers, you will find that some participants provide poor quality work and are slow to learn enough to contribute effectively. [Here's how to work with them.](https://harihareswara.net/posts/2017/how-to-teach-and-include-volunteers-who-write-poor-patches/) It's ok to deflect some people into contributions they can do so you can concentrate on others -- but also, encouraging someone in this category can sometimes help you nurture someone who will be a really enthusiastic contributor in user support, marketing, or other areas.
