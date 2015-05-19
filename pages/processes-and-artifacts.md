---
permalink: /processes-and-artifacts/
title: Processes and Artifacts
---
Processes and artifacts that can help rapidly organize a grouplet, as well as
maintain momentum, productivity, and morale.

- [The Two-Pager](#two-pager)
- [The Mission Statement](#mission)
- [Outcomes and Metrics](#outcomes)
- [Roles](#roles)
- [MacGuffin](#macguffin)
- [Recruiting](#recruiting)
- [Kick-Off Meeting](#kickoff)
- [Weekly Meetings](#meetings)
- [Task List](#tasklist)
- [Weekly Agenda](#agenda)
- [Breakout Meetings](#breakouts)
- [Artifacts, Assumptions, and Metrics](#metrics)
- [Chat Room](#chatroom)
- [Hub](#hub)
- [Fixits](#fixits)
- [Exit Strategy](#exit-strategy)

## <a name="two-pager"></a>The Two-Pager

When faced with the task of forming a new grouplet, a very useful exercise is
to write a two-page document describing the [Mission](#mission) of the
grouplet, its [Outcomes and Metrics](#outcomes), and the initial set of
[Roles](#roles) that will form the grouplet's basic structure. This two-pager
helps to clarify your thinking and course of action, and serves as an effective
[recruting artifact](#recruiting), as prospective volunteers can get a feel for
the grouplet very quickly and see how they may be able to pitch in and
contribute right away.

## <a name="mission"></a>The Mission Statement

It should go without saying that there should be a one-sentence mission
statement describing why the grouplet should exist. It is the reason for
starting a grouplet in the first place; if you can't articulate that reason
clearly, then maybe the grouplet shouldn't exist. It is also the first item in
your [recruiting toolkit](#recruiting), as it will be the first thing at the
very top of your [Two-Pager](#two-pager) artifact.

Here are a few examples:

- **18F Documentation Working Group:** Organize all of 18F’s information and
  make it universally accessible and useful, internally and externally.
- **18F Testing Grouplet**: Ensure the long-term success of 18F development
  projects by cultivating the best automated testing tools, practices, and
  training materials available.
- **18F Working Group Working Group**: To create an environment in which
  working groups and guilds can thrive and have a meaningful impact on 18F
  deliverables and operations.

## <a name="outcomes"></a>Outcomes and Metrics

The "Outcomes and Measures" process, or "Outcomes" for short, is a quarterly
process for setting goals and reviewing progress. It involves defining roughly
two-to-three high-level strategic "Outcomes" that support the team's overall
[mission](#mission), and defining a number of "Metrics" that aim to evaluate
progress toward the outcome. By framing the outcome in terms of problems
to solve or positive impact, this framework creates flexibility for people to invent their own creative solutions, and modify the specific approach, if needed.

### Outcomes

Each outcome should be about impact of your work, rather than the work product.  For example,
"increase the number of people below the poverty line who have access to food" instead of
"build a webapp to provide foodstamps" -- you may be tasked with the latter,
but your real goal is the former. Of course, for a single quarter, you will often
need to break down your project outcome into something you can accomplish in that time.

A good outcome will show progress toward a larger goal. It often takes some effort and
creativity by your team to come up with a way to measure the impact of your work.  If you
can't yet come up with metrics to determine your impact, consider that establishing
baseline measures could itself be an outcome. Learning about your target audience
will have tremendous value as you create a solution.  You can build prototypes or
create software designs as part of the work, but the outcome is how those activities
help you understand the impact (or potential impact) of the work.

### <a name="measures"></a>Measures and Metrics
Ideally you will measure something at the beginning of your work and then
at intervals.  Be careful not to be solely focused on quantitative data.
Especially at first, you will need to gather qualitative results to
validate that your work has impact.  Quantitative metrics will be important
to evaluate the impact as you scale your solution; however, when you are just getting
started is the time to come up with ideas of how you might quantitatively measure
impact and gather early data to compare to your qualitative assessments.

Measure results at regular intervals, which may be weekly, after each sprint or
monthly, depending on the cadence of your work. In order to meet quarterly
objectives, you will need to capture your results more frequently, evaluate,
and iterate to be confident that you are moving toward the desired outcome.

### <a name="review"></a>Review
At the end of the quarter, the team will review and assess each outcome
by its metrics.  This assessment must be thoughtful, rather than driven by
pure numbers.  The team is encouraged to have an open discussion which gathers
additional data from the team, in addition to reflecting on metrics:

1. Were there unexpected outcomes?  these could be positive or negative side-effects of the work
2. Have we noticed changes in behavior that are not captured in our metrics?  (these could be in our team, our solution, the target audience, or the surrouding ecosystem)
3. Have we learned something about our outcome?  is there anything that makes it less or more desireable? less or more urgent?
4. Are there additional outcomes we would like to consider?

Any reporting of metrics should include updates to outcomes and metrics, based
on what was learned.

Outcomes and metrics are designed to produce focus and align expectations.
This process serves to ensure the team is moving in the direction that the team
believes will have the most impact, making good progress according to its own
ambitions, abilities, and resources.

### <a name="examples"></a>Example of Effective Outcomes and Metrics
When prospective [recruits](#recruiting) and team members see a set of outcomes
and metrics, they can better understand the priorities and imagine how they can
contribute to achieving the goals. This increases effective collaboration and
boosts your credibility as a leader as someone who will ensure that their time is well-spent.

As an example, here are some 18F Engineering team Outcomes and Metrics:

**Outcome:** Streamline project deployment
* **Metric**: do we have clear measures of project deployment effort, including initial deployment, iterative updates to software, and ATO?
* **Metric**: time and effort of deployment (we expect to see a reduction by adding service integrations to the Cloud Foundry PaaS for RDS and Elasticsearch)

**Outcome:** Deliver quality products (with visible quality indicators on a dashboard)
* **Metric**: % projects with automated tests, 508 compliance, and
fully documented APIs [list shortened for the purposes of this example]


## <a name="roles"></a>Roles

Though a Grouplet leader (usually) isn't in a formal supervisory role over
other Grouplet members, there is still a strong need to establish a basic,
functional team structure. However, rather than adopting a heavy-handed
command-and-control style, have fun with the role names! The prospective
separation of responsibilities as defined in the [Two-Pager](#two-pager) give
prospective [recruits](#recruiting) a sense that the team is (or will become)
well-organized and efficient, while keeping the actual titles fun send a
message that the group is not about piling additional work onto people for the
sake of the organizer's personal ambition.

Good roles serve two critical functions: Delegation and Escalation. The
Organizers _should not_ be the only ones responsible for every detail of the
overall effort. Also, when responsibilities are clear, grouplet members may be
able to manage tasks by going directly to the appropriate role-holder, rather
than the Organizers having to remain in the critical path of every decision. In
other words, "creativity is pushed towards the edge of the organization". (Need
"Technical Impact" citation.)

As an example, here is the prospective list of 18F Testing Grouplet roles at
the time of writing:

**The Walrus (Organizers): <span class="role-ok">Mike Bland and Alison
Rowland</span>**<br/>
Assumes ownership of the overall effort. Responsible for: establishing
direction and priorities; delegating tasks; removing obstacles; and getting
his/her hands dirty when needed.

**Prime Mover (Manager): <span class="role-danger">Mike Bland</span>**<br/>
Ensures the meeting agenda is prepared and posted ahead of time; reserves the
meeting room and manages remote coordination; ensures that the Historian’s
minutes are posted in a timely manner.

**Historian: <span class="role-danger">Mike Bland</span>**<br/>
Responsible for documenting, summarizing, and archiving notable issues or
activities and their artifacts in a centrally-accessible repository. Meeting
minutes fall under this rubric.

**Minister of Communication: <span class="role-danger">Mike Bland</span>**<br/>
Ensures that the Slack channel and other communication media are accessible,
useful, and broadly used by the group. May suggest alternate communication
media or innovative uses of the media already in use.

**Ministers of Information: <span class="role-ok">Shawn Allen</span>**<br/>
Solicits and helps cultivate content; in this context, ensures that all
important information is integrated into or linked to by the Hub system, and
that missing information is actively solicited.

**Wordsmith: <span class="role-danger">Mike Bland</span>**<br/>
Explores and promotes standardized means of organizing artifacts and their
content, e.g. the use of tags, application of CSS styles, traditional SEO
techniques for organizing content and making it more easily discoverable.

**Hackers: <span class="role-ok">Shawn Allen</span>**<br/>
Responsible for the active development of any associated programs or systems.

Notice the number of roles with the organizers' names next to them in red. You
can point [recruits](#recruiting) at this list when pitching them, or during
the [Kick-Off Meeting](#kick-off), and explain this: _The grouplet's long-term
chances of success are inversely proportional to the number of Roles that have
the organizers' names next to them in red!_ People can quickly see where help
is most needed and jump in accordingly.

Also, there need not be a one-to-one correspondence between roles and
individuals. One person can serve more than one role, and one role can be
filled by more than one person. The important part is that the functions and
those responsible for them are made clear.

## <a name="macguffin"></a>MacGuffin

"[MacGuffin](http://en.wikipedia.org/wiki/MacGuffin)" is the film industry term
for an object that drives the action of the plot. In _Pulp Fiction_, it was
Marsellus Wallace's suitcase. In _Raiders of the Lost Ark_, it was the Ark of
the Covenant. It's handy to have a MacGuffin at the outset of the grouplet as
well.

A MacGuffin provides [recruits](#recruits) with tangible proof that the
grouplet exists and _is up to something._ It should be an artifact that invites
cultivation and can grow along with the grouplet itself, and can provide the
foundation for one or more of the grouplet's initial Outcomes and Metrics](#outcomes). Some examples:

- **18F Documentation Working Group:** [The 18F Hub](https://18f.gsa.gov/hub/)
- **18F Testing Grouplet**: [The 18F Automated Testing
  Playbook](https://github.com/18F/automated-testing-playbook/)
- **18F Working Group Working Group**: [The 18F Grouplet
  Playbook](https://github.com/18F/grouplet-playbook/)

## <a name="recruiting"></a>Recruiting

So you've defined a [Mission](#mission), broken out [Outcomes and Metrics](#outcomes), defined fun-sounding [Roles](#roles), started implementing a
[MacGuffin](#macguffin), and encapsulated all of this into a
[Two-Pager](#two-pager). Now you're ready to shop around for prospective
grouplet members!

There are two paths you can go by, but in the long run, there's still time to
change the road you're on:

- **One-on-One**: Set up brief appointments with prospective recruits to engage
  them in-person. Walk them through the [Two-Pager](#two-pager) and ask for
  their thoughts and opinions. If they seem into it, recruit them into one or
  more of the available [Roles](#roles).
- **Broadcast**: Send the [Two-Pager](#two-pager) out to a broad audience and
  respond to any bites. Follow up with one-on-one invitations, or announce the
  initial [Kick-Off Meeting](#kick-off) at the same time.

## <a name="kickoff"></a>Kick-Off Meeting

With your [Two-Pager](#two-pager) in-hand, use it as the official agenda for
the first Kick-Off meeting. Ideally you've already had a one-on-one [recruiting
chat](#recruiting) with most of the people in the room; this ensures that the
meeting goes quickly, and that other people besides the organizers have a
chance to speak about some of their own ideas.

## <a name="meetings"></a>Weekly Meetings

After the warm-fuzzies of the initial [recruiting phase](#recruiting) and the
[Kick-Off Meeting](#kick-off) have worn off, it's critical to maintain momentum
and team cohesion by holding brief weekly meetings, ideally only thirty
minutes. Though modern professionals have grown very wary of meetings, when run
well, they are the best tool in the box for making sure people continue to
identify with the grouplet and feel a sense of constant forward progress.

That said, it's incumbent upon the organizers to ensure these meetings are run
as well as possible. There should be a grouplet [Task List](#tasklist) that is
reviewed every week. The organizers should draft a [one-page Agenda](#agenda)
and publish it at least one day prior to each meeting, to give people an idea
of the week's business and to provide the opportunity to put new items on the
agenda. Given these items, the organizers should impress upon members that
everyone should come prepared to discuss the items for which they're
responsible, to make the best use of everyone's time.

One of the most important things to keep in mind: _take turns talking!_ No one
wants to be lectured at by any sort of leader for one minute, let alone thirty.
Do what you can to foster healthy, dynamic discussion between grouplet members,
_even if that means biting your tongue when no one will speak up!_ If you let
the group get used to you breaking all of the silences, it will gladly let you
continue to do so.

## <a name="tasklist"></a>Task List

The grouplet should maintain a centralized Task List to keep track of all the
different efforts underway, large and small. The beginning of each [weekly
meeting](#meetings) should be a very quick review of this list; items should be
added to it as necessary during the remainder of the meeting.

The point of the task list isn't to make members feel guilty for the tasks
they've not made progress on; as a volunteer effort, one should expect grouplet
tasks will often fall onto the backburner given higher-priority tasks from
members' officially-assigned projects. The point is to ensure that good ideas
and promising action items aren't forgotten, and to make a habit of celebrating
those items that are completed, so that members feel like their efforts are
recognized and appreciated.

Tracking tasks like this can also be useful for writing weekly status reports
or personal [snippets](https://18f.gsa.gov/2014/12/17/snippets/), as concrete
reminders of tangible progress.

A sharable medium for the list is best; this can be as basic as a shared
spreadsheet, or a full-blown issue tracker or project management program. As an
example, the [18F Documentation Working Group Trello
board](https://trello.com/b/cI4LmXOj/wg-documentation) is publicly-accessible.

## <a name="agenda"></a>Weekly Agenda

Publishing a one-page weekly agenda is one of the most important items for
ensuring [weekly meetings](#meetings) remain focused. Members who attend should
read the agenda ahead of time, know clearly what to expect during the course of
the meeting (in terms of structure, if not detail), and come prepared to
discuss any items for which they're responsible. If something they would like
to discuss is not on the agenda, they should be free to add it. The Historian
can then use the agenda document to keep the meeting minutes, which will help
reflect how closely the meeting stuck to the intended structure.

A sharable document works best for this, naturally, but an imperfect
something's better than nothing. A recommended structure for the document is:

- A link back to the previous week's agenda document
- A link to the grouplet's [Task List](#tasklist)
- Top-level agenda items, possibly followed by supporting comments or artifacts
- A spot for "other business" at the end, where the Historian can note other
  topics that may have arisen during the meeting

## <a name="breakouts"></a>Breakout Meetings

Sometimes topics will arise that are too large to discuss during the course of
the [weekly meeting](#weekly-meeting). Rather than let the [Agenda](#agenda)
fall by the wayside, it's good practice to announce a breakout meeting to
discuss one specific item. These meetings can actually be much longer than the
weekly meeting, since they will usually engage fewer people who are
particularly interested in the outcome of a single issue. Those who attend the
meeting will be expected to take notes or produce some other resulting
artifact to present at the following weekly meeting of the entire grouplet.

It's not always necessary for the organizers to be at every breakout meeting.
Given a cohesive [Mission](#mission), set of [Outcomes and Metrics](#outcomes), well-defined [Roles](#roles), and a well-maintained [Task
List](#tasklist), it's possible that a subset of members are aligned and
motivated enough to hold their own special meeting without oversight. This is
actually healthy for the grouplet, as members see themselves as autonomous
contributors within a community of peers, rather than mere followers of the
organizers. It's also a chance for members to takes turns driving meetings and
initiatives before inheriting the organizer role one day.

## <a name="metrics"></a>Artifacts, Assumptions, and Metrics

This exercise is about evaluating the assumptions behind the "Metrics"
component of the [Outcomes](#outcomes) process. Create a table
with three columns:

- **Doing/Building this:** A Key Result action or artifact
- **Will get us this outcome:** The intended impact of the Key Result
- **We'll know we are right when we see:** The measurable outcome of the Key
  Result that demonstrates the intended impact

Here's an example from the notes for an 18F Documentation Working Group
[Breakout Meeting](#breakouts) to discuss the group's 2015 Q1 Outcomes (credit:
Nick Brethauer):

<div class="table">
<div class="table-header-group">
  <div class="table-cell">Doing/Building this:</div>
  <div class="table-cell">Will get us this outcome:</div>
  <div class="table-cell">We’ll know we are right when we see:</div>
</div>
<div class="table-row">
  <div class="table-cell">bridging hub with Slack (e.g. slack channel where hub
  owner helps someone find answers on hub)</div>
  <div class="table-cell">People think about hub (remember it exists) and it
  becomes their goto source for getting questions answered</div>
  <div class="table-cell">Initial large number of Slack hub answer requests,
  and gradual decrease</div>
</div>
<div class="table-row">
  <div class="table-cell">MOVE content to hub</div>
  <div class="table-cell">Behavior of going to hub</div>
  <div class="table-cell">Observe content not being accessed elsewhere, observe
  usage on hub, reduction in questions asked on Slack</div>
</div>
</div>

## <a name="chatroom"></a>Chat Room

If it's convenient, having an online chat room in which members can discuss
grouplet business and make announcements is a great way to foster community
and make progress in between meetings. It's also a great way to ensure that
members distributed across multiple work sites remain fully-integrated into
pertinent discussions. 18F is a heavy user of [Slack](https://slack.com);
naturally every grouplet-like group has its own Slack channel for this
purpose.

## <a name="hub"></a>Hub

A "Hub" is basically an information radiator that enables grouplet members to
share and discover information easily. It can take the form of a shared drive,
a wiki page, a chat room channel, an issue tracker/project management tool, or
some combination of these tools and others. In the case of 18F, the
Documentation Working Group maintains the [18F Hub
project](https://18f.gsa.gov/2014/12/23/hub/) as a means of taking this
concept to the extreme for the entire team, not just for the working group
itself.

## <a name="fixits"></a>Fixits

Fixits are traditionally one-day sprints where people are asked to put aside
normal project work and focus on "important but not urgent" tasks. They are
also fantastic for rolling out new tools across an organization.

In practice, Fixits can be of any length and size. Organizing and/or
participating in a Fixit has many important side-benefits in addition to the
stated goals of the Fixit itself:

- Fixits focus both organizers and participants on concrete goals that
  contribute to an overall strategic objective.
- Motivation for participation can take the form of prizes for participation,
  recognition for good deeds, and a sense of good karma from doing the right
  thing.
- Fixits punctuate the larger "story arc" of overall culture-change with
  exciting events that raise the morale of everyone involved, thanks to all
  the positive energy that's generated.
- Fixits often advance the state-of-the-art by focusing energy and momentum to
  push beyond a tipping point, ratcheting the overall culture-change effort up
  to a new plateau.

## <a name="exit-strategy"></a>Exit Strategy

A healthy grouplet doesn't depend on the vision and effort of one or two
people. As an organizer, you should start scouting for a successor on day one.
Cultivating members to rise up through the ranks helps the grouplet remain
vibrant and active, and will one day free you to move on to new challenges
with the comfort of knowing that the team you helped to build continues to
thrive.
