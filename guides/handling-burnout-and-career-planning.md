# Handling Burnout and Career Planning

_This is a guide based on two Open Source Collective workshops led by Sumana Harihareswara of_ [_Changeset Consulting_](https://changeset.nyc) _in early 2022. It focuses on maintainer burnout and career planning for leaders of Open Collective-hosted open source software projects. Thanks, Sumana!_

## Start with the end

All maintainers eventually leave (or stop leading) projects.

In open source, this often happens messily, in a way that leaves users with unclear expectations and drains maintainers' morale as things shamble slowly to a stop. For example:

* none of the team will admit that the project is out of energy, so the public-facing communications are contradictory and set misleading expectations until a domain expiration or missed migration notice lead to an abrupt 404
* the lead maintainer refuses to either promote co-maintainers or address critical problems, so time and attention are wasted with a fork
* the sole maintainer completely disappears from public view or interaction, often due to feeling overwhelmed with obligation and compounding procrastination with anxiety over making up for lost time, and leaving users to find and share makeshift workarounds to their concerns
* maintainers think everything's quiet and it's safe to hand off maintainer control to a somewhat unknown contributor, who then turns out to be a malicious actor who inserts malware or other vulnerabilities into the code

As a maintainer -- and as a user -- you don't want those endings. It's worth taking a moment to imagine: what would a _good_ departure look like for your involvement with your project? Or, if you can't imagine any of these things feeling _good_, what endings or departures would be _better_ than the bad ones listed above -- clearer, more respectful, less wasteful?

Example better endings or departures:

* pass the project off sustainably to other maintainers
* work with upstreams or downstreams to merge your codebase into theirs, e.g., [Enigmail ending support for Thunderbird as Thunderbird added built-in PGP support](https://www.enigmail.net/index.php/en/home/news/71-2021-08-31-end-of-support-for-thunderbird)
* make an assessment that advances in other technologies render the need for the project obsolete, and archive the project to clarify expectations that there will be no further maintenance
* announce that the project is set to be sunsetted so your users can start planning their migrations, and [invite your users to crowdfund labor to keep it going or help them migrate to an alternative, as in this hypothetical example](https://harihareswara.net/posts/2021/what-would-open-source-look-like-if-it-were-healthy-video-transcript/#healthy-oss-legacy-ending)

Certainly none of these changes would be painless, and some of them place a substantial burden on users. But, unless you have ongoing and reliable support from your users, they can have no reasonable expectation that the project will continue to update or that you in particular will continue to maintain it. You might need to leave due to unavoidable personal circumstances, from leaving a job to having a child to dying. Or, technological changes could cause a project to wither or no longer be necessary, as when it's written in a language that popular operating systems stop supporting, or another tool grows to include your tool's functionality. An explicit, publicly announced, scheduled sunsetting of a project or maintainer departure is better because it gives everyone else a better chance to make and execute plans to take care of their own needs.

Maintainer activities, of course, aim to keep a project going; we want to avoid its end, and maybe we feel obligated to do so and thus feel conflicted and averse about the possibility of someday leaving. The point of this exercise is to concretely imagine what a positive (or less-painful) end could be for the project or for your participation, so you can potentially start building a path to it or noticing when it's time to switch to a Plan B that involves ending the project or your maintainership.

## Concrete steps towards maintainer succession

Consider this diagram of how people flow through a project:

<figure><img src="../.gitbook/assets/People Flow (2).png" alt=""><figcaption></figcaption></figure>

You can encourage healthy movement with steps such as:

* when people go from Contributor to Maintainer, or from Maintainer to Emeritus, [publicly salute all of them](https://guix.gnu.org/en/blog/2022/gnu-guix-maintainer-rotation/). This encourages other contributors to consider that they could earn promotion, and helps contributors and maintainers recognize that it's okay to leave after doing their bit.
* actively communicate with the people you might someday want to promote to co-maintainer. Many reticent contributors wait to be invited to co-maintain, or aren't certain how they need to grow to earn a promotion. Ask them about what their interests and help them understand what it would take for them to become co-maintainers. (More guidance is forthcoming in our "Recruiting and promoting maintainers" guide.)
* use rituals such as [the twice-yearly Volunteer Responsibility Amnesty Day](https://www.volunteeramnestyday.net/) to regularly take inventory of your volunteer responsibilities. Check with yourself, and end (or plan to end) the commitments you need to end – maybe by taking a break, or by rotating it on to someone else, or by sunsetting a project.
* use [GitHub's "assign a successor" setting](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) to ensure continuity in case you die.

## Perfectionism, procrastination, and burnout

Maintainers sometimes resist thinking about taking a break or leaving because we think no one else could do our work as well as we do it, or because we perceive ourselves to have made an unbreakable commitment, an obligation that nothing else can supersede (even our own mental health). We also procrastinate doing work we are averse to or afraid of, especially when we don't think we're up to doing it as well as it deserves. Here are some resources to help you reflect on these habits:

* on overcoming procrastination based on perfectionism: [Amandine Lee's "Risk Assessment Analogy"](http://amandinemlee.com/2018/10/28/A-Risk-Assessment-Analogy), discussing failure scenario generation, safety, and verification, says that knee-jerk caution can be reflex that leads to, as Lee calls it, "wasteful carefulness":
  * we often push to a small percentage of real traffic, do bug-bashes and conduct pre-mortems where we imagine different types of failures and what would have caused them. We're trying to smoke out the unknown unknowns that cause issues. It's a type of thinking I am actively learning how to lean into. As an optimist, someone who tends to seek out nuance, and a person who has a strong bias towards action, I tend to chafe against risk-aversion without a clear threat model. The term "Cover Your Ass" gets thrown around to describe extreme end of this - wasteful carefulness. .... ...People's intuitions and risk-friendliness also vary based on personality, and how they’ve seen things fail in the past. A lot of growing as an engineer is fine-tuning that initial response to design decisions.
* How do you tell the difference between needing a break and needing to stop? How can you decrease your involvement in a project without stepping away completely? ["On Noticing That Your Project Is Draining Your Soul"](https://harihareswara.net/posts/2017/on-noticing-that-your-project-is-draining-your-soul/) offers some guidance.
* "Wellness is not a state of mind, but a state of action. It is the freedom to move through the innate cycles and oscillations of being human - from effort to rest and back, from connection to autonomy and back, from adventure to homecoming and back. But we have been lied to our whole lives about what wellness 'should' look like, and rejecting that lie, all those myths about 'having it all' and 'finally achieving lasting peace' is how we create space in our lives for that free action through the cycle of being human." [Emily Nagoski and Amelia Nagoski, _Burnout_](https://www.burnoutbook.net/) (also check their list of [ways to complete the stress response cycle](https://ideas.ted.com/emotionally-exhausted-burnout-completing-stress-response-cycle/)

One hint that you might be burned out: when you even think about the project, you feel massive don't-wanna-get-out-of-bed aversion. Perhaps you should try a 3-month break from the project, temporarily, and at the end, see whether you have any desire to return to it.

## Career

_Are you in a job you want to be doing?_ This may go beyond your maintainership work. [Self-determination theory suggests](https://en.wikipedia.org/wiki/Self-determination\_theory#Basic\_psychological\_needs) that you need _autonomy_ (you get to choose what you do), _competence or mastery_ (you are good at your tasks and achieve the desired outccomes), and _connectedness or relatedness_ (you and others care for each other; some people connect this to _purpose_, i.e., you can see the connection between your efforts and progress towards a goal you care about). Are you getting these things in your current roles?

Here's a 20-minute exercise you can do to help map out what you want next in your career, remixed from [an exercise for Outreachy open source interns](https://changeset.nyc/resources/career-advice-open-source-interns/):

1. 5 minutes: _What specifically do I like about my current role: what would I like to get more of?_ (Think specifically: what languages, tools, people, activities, and conversations do you enjoy? If you can't think of anything in your current role, think about past jobs, volunteer roles, etc.)
2. 10 minutes: _What do I want next, and what are my constraints?_ (It's okay not to know! This is a good time to make a note to ask peers what they think you would be good at, and if you have peers you envy, ask them how they got where they are.)
3. 5 minutes: _What are my next steps?_ Examples: update your resume/CV, ask your friends to schedule some mock interviews, reply to people you met at conferences, blog about what kind of job you want, apply for a grant, apply to [Recurse Center](https://recurse.com) or talk to a venture capitalist.
