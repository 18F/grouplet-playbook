---
permalink: /education-and-advocacy/
title: Education and advocacy
---
This page contains models and strategies for driving adoption of best practices throughout a
development culture.

- [Abandon data and absolute reason](#abandon-data)
- [Everything is not for everyone](#everything-is-not-for-everyone)
- [Crossing the chasm](#crossing-the-chasm)
- [The chasm](#the-chasm)
- [“Poor quality” code not an issue](#poor-quality-not-an-issue)
- [Case study: Google's testing grouplet](#googles-testing-grouplet)
- [Seize the teachable moments!](#seize-the-moment)
- [Play the long game](#play-the-long-game)

## <a name="abandon-data"></a>Abandon data and absolute reason

Best practices are often more about _avoiding_ visible impact than _producing_
it. Such negative impact is practically [impossible to
prove](http://mike-bland.com/2012/07/10/test-mercenaries.html#mercs-proving-negatives).
Hence, when it comes to driving adoption of best practices, in general,
experience is the most effective form of persuasion.

Given the distribution of the [diffusion of innovations
model](http://en.wikipedia.org/wiki/Diffusion_of_innovations), it's
inevitable that some will attempt to thwart your efforts to promote certain
practices by demanding data proving its effectiveness. Disregard those who
protest in this way: A demand for data proving the effectiveness of automated
testing is [cowardice masquerading as
reason](http://martinfowler.com/articles/testing-culture.html#change-stand).

Alternatively, turn the argument around: Ask for the data that conclusively
made the case for using programming language X, or text editor Y, or hosting
platform Z.

## <a name="everything-is-not-for-everyone"></a>Everything is not for everyone

Taking Test-driven development (TDD) as an example, the end result is well-tested
code. TDD is not the only means to get there. The goal is to promote best
practices that people perceive as having value based on their own experience
rather than coersion or academic purity.

## <a name="crossing-the-chasm"></a>Crossing the chasm

Geoffrey A. Moore’s book *[Crossing the
Chasm](http://en.wikipedia.org/wiki/Crossing_the_Chasm)* first explains the
different segments of the bell curve-shaped diffusion of innovations model:

![Diffusion of Innovations and the Chasm](../assets/images/the-chasm.jpg)<br/>
_Image by Catherine Laplace based on other illustrations of the “Crossing the
Chasm” model._

- **Innovators and Early Adopters**: Partners-in-crime, believe in principle,
  help each other clarify concepts, principles, priorities.
- **Early Majority**: Persuaded by results, reason, positive experience.
- **Late Majority**: Persuaded by common practice, lack of friction.
- **Laggards**: Abandon them. They're useless, dead weight.

The Innovators and Early Adopters comprise the Instigators. It's their
responsibility to cross the “chasm” identified by Moore as the gap between the
Early Adopters and the Early Majority. Crossing the Chasm is what determines
the success or failure of an initiative, as crossing it is necessary to
achieve widespread adoption.

## <a name="the-chasm"></a>The Chasm

Using automated testing adoption as an example, the “chasm” may be
characterized as:

- Slow and/or incorrect builds
- Ignorance of principles, techniques, and idioms
- Poor management and development culture

The chasm is best crossed via persuasion, not force (laggards
notwithstanding). Albert Wong’s “Rainbow of Death” model from “[Large Scale
Development Culture Change: Google and the U.S.
Government](https://18f.gsa.gov/2014/12/11/large-scale-development-culture-change/)”
describes a progression of activities Instigators must undertake to lead the
Early Majority across the chasm.

![Crossing the Chasm via the Rainbow of
Death](../assets/images/crossing-the-chasm-rainbow-of-death.jpg)<br/>
![Close-up of Crossing the Chasm via the Rainbow of
Death](../assets/images/rainbow-of-death.jpg)<br/>
_Images by Catherine Laplace based on other illustrations of the “Crossing the
Chasm” model and Albert Wong’s framework image._

Fulfilling each step is necessary to producing lasting, positive change. By
moving from one step to the next (conceptually; in reality many efforts must
happen in parallel), the Early Majority is transformed from Dependent upon
the Instigators to Independent:

- **Intervene**: Instigators do the work.
- **Validate**: Instigators validate the efforts of the Early Majority.
- **Inform**: Instigators provide technical information and training to the
  Early Majority.
- **Inspire**: Instigators motivate the Early Majority and help them feel that
  their work is valuable.
- **Mentor**: Instigators build strong relationships with Early Majority
  members.
- **Empower**: Early Majority members are able to do the work, with ongoing
  support from Instigators.

## <a name="poor-quality-not-an-issue"></a>“Poor quality” code not an issue

“Poor quality” code is not part of the chasm. It's a symptom, not a cause.
Spread ideas and remove obstacles, and the code will improve.

## <a name="googles-testing-grouplet"></a>Case study: Google’s Testing Grouplet

Google's **Testing Grouplet** was a team of volunteers pooling their 20 percent time
to drive adoption of automated developer testing, in the most serious and fun
ways possible. Some of the more significant efforts included:

- **Test Certified**: a concrete roadmap towards sound automated testing.
- **Testing on the Toilet**: a weekly, one-page flyer published in restrooms
  company-wide to introduce testing concepts and tool developments. Started in
  2006 and still running today (January 2015), it proved a fantastic,
  distributed volunteer task. It started and standardized conversations, both
  inside and outside the Testing Grouplet, avoiding the echo chamber effect.
- **Test Mercenaries**: hands-on internal consultants that helped teams move
  up the Test Certified ladder. They also both informed internal tool
  development and drove company-wide tool adoption.
- **Fixits**: limited-time, all-out efforts to address “important but not
  urgent” tasks and roll out new tools. Fixits built momentum and morale, and
  the focused effort overcame huge obstacles, setting the stage for future
  developments.

This is how these efforts and a few others fit into the "Rainbow of Death"
model:

![The Google Testing Grouplet's Rainbow of
Death](../assets/images/testing-grouplet-rainbow-of-death.jpg)<br/>
_Derived from Albert Wong’s original framework slide from a Google-internal
tech talk._

## <a name="seize-the-moment"></a>Seize the teachable moments!

“goto fail” and Heartbleed were prime examples of why unit testing is so
critical. Both bugs were unit-testable, as proven by the working code in the
“[Finding More Than One Worm in the
Apple](http://queue.acm.org/detail.cfm?id=2620662)” and “[Goto Fail,
Heartbleed, and Unit Testing
Culture](http://martinfowler.com/articles/testing-culture.html)” articles.

When such opportunities to demonstrate the importance of best practices arise,
we can seize the chance to publish articles, give presentations, and refer to
existing works. Such activities build a body of knowledge and give our
arguments scholarly weight.

When making our arguments, it’s important to emphasize “why” we follow a
practice as well as “how.” The “why” may be obvious to the Instigators who
already “get it” but not necessarily to everyone.

## <a name="play-the-long-game"></a>Play the long game

Lasting change never comes quickly. Eschew
_[authoritah](http://shop.southparkstudios.com/SOUTH-PARK-CARTMAN-POSTER-You-will/A/B00302A3OI.htm)_;
you know telling programmers “do as I say” is a recipe for disaster!

Understand that the problem isn’t purely technical, and it isn’t just about the
value of a particular practice. It’s about the “chasm”. Hearts and minds must
be persuaded (Early Majority), won (Late Majority), or conquered (laggards).
