# Chapter 5: Seeing the System

Doug spent the weekend thinking about Maya's question. What if the problem wasn't the people, but the system?

He'd always thought about work at the task level: finish this code review, fix that bug, attend this meeting, unblock that person. But he'd never really thought about the system—the invisible architecture of processes, handoffs, and constraints that determined how work actually flowed through the organization.

Or more accurately, how it didn't flow.

Sunday evening, instead of watching TV with his family, Doug found himself in his home office with a notebook. Michelle had given him a look—the "you're working again?" look—but she'd seen something different in his eyes and let him be.

At the top of a blank page, he wrote: "How does work actually happen at ShopStream?"

Then he started mapping it out. Not the official process documented in Confluence, but the real process. The one that involved Slack messages at odd hours, hallway conversations, waiting for people to return from vacation, meetings to schedule meetings.

He started with a simple user story: "As a customer, I want to see product recommendations on the home page."

Step 1: Someone (customer success? marketing? a random customer email?) suggests the idea.

But wait—before Step 1, there's Step 0: How does the idea even get captured? Doug added notes:
- Ideas come from: Customer feedback, competitor analysis, executive requests, engineering suggestions, random Slack messages
- Ideas land in: Jira, Productboard, email threads, lost forever

He'd never thought about how much friction existed just in the "capture an idea" phase.

Step 2: Product team evaluates and prioritizes.

But when? Mark's team had a prioritization meeting every two weeks. So right there, average wait time: one week. And what if the idea wasn't compelling enough to make the cut? Did it get re-evaluated? Lost? Forgotten?

Doug kept mapping. By the time Michelle called him to bed at 11:30 PM, he'd filled fourteen pages with notes and arrows and question marks. The system was even more complex than he'd realized.

And that was for one feature. One simple feature.

---

Monday morning, Doug arrived at the office early, his notebook in hand. He'd sent Maya an email Sunday night: "I want to take you up on your offer. When can we talk?"

She'd responded within minutes: "Tuesday afternoon, 3 PM. Conference Room D."

For the first time in weeks, Doug felt something other than dread about a meeting. He felt curiosity.

But first, he had to get through Monday. The board meeting was at 10 AM, and Tom wanted the incident post-mortem presentation ready by 9:30.

Doug spent two hours putting together slides that essentially said: "We had a cascading failure because our systems are fragile and our processes are slow. We're working on fixing it." He tried to spin it more positively, but that was the truth underneath all the corporate language.

At 9:45, Sarah called him into her office.

"The board meeting is happening without us," she said, looking at her laptop screen. "Tom and Maya are presenting first. We're on standby in case they need us."

"Should I be worried?"

"I don't know," Sarah said honestly. "Tom's been locked in meetings with Maya all weekend. I haven't seen what they're preparing."

They waited. Doug checked his email. Responded to Slack messages. Reviewed a pull request. The minutes crawled by.

At 11:15, Sarah's phone rang. "Okay... yes... we'll be right there."

She hung up and looked at Doug. "They want us in the board room. Both of us."

---

The board room was on the top floor, with floor-to-ceiling windows overlooking the city. Doug had only been in it twice before—once when he was hired, and once for a company-wide celebration that now seemed like it had happened in another lifetime.

Tom sat at the head of the table, looking more energized than Doug had seen him in months. Maya sat beside him, calm and present. Around the table were the board members: Amanda Foster, the VC who'd given them the ninety-day ultimatum; two other investors Doug didn't know well; and the CFO.

"Doug, Sarah, thanks for joining us," Tom said. "We've been discussing Maya's initial assessment and recommendations. I wanted you to hear this directly."

Maya stood and walked to the whiteboard. With a few quick strokes, she drew a diagram:

```
IDEA → DESIGN → DEVELOP → TEST → DEPLOY → MEASURE
```

"This is your current value stream," Maya said. "From idea to customer value. Now, let me show you what we discovered."

She added numbers below each arrow:
```
IDEA →(7 days)→ DESIGN →(12 days)→ DEVELOP →(8 days)→ TEST →(11 days)→ DEPLOY →(9 days)→ MEASURE
```

"Total cycle time for a medium-complexity feature: forty-seven days. And that's an average—some features take months."

She circled the 8 days under DEVELOP. "This is the actual value creation time. The time engineers spend writing code. Eight days out of forty-seven."

She drew a big circle around all the other numbers. "This is waste. Not because people are lazy—everyone is working incredibly hard. But because the system creates waiting, handoffs, rework, and coordination overhead."

Amanda Foster leaned forward. "We knew things were slow. But I didn't realize it was this bad."

"It gets worse," Maya said, not unkindly. "This is just for features that make it through. Doug, how many feature ideas are in your backlog right now?"

Doug had looked at this last week. "Four hundred and sixty-three."

"And how many features did you ship last quarter?"

Sarah answered this one: "Twelve. No, wait—eleven. One got rolled back."

"So you have a forty-two-to-one ratio of backlog to delivery," Maya said. "Which means the average feature idea will wait roughly twelve quarters—three years—before even being considered. Most will never be built at all."

The room was silent.

"Now, I want to be clear," Maya continued. "This is not unique to ShopStream. This is the pattern I see in most organizations that haven't fundamentally rethought how they work. And it's not sustainable, especially not in a competitive market where customer expectations are accelerating."

"So what do we do?" Tom asked.

Maya smiled. "That's where it gets interesting. We're at an inflection point in how software organizations can operate. The technology now exists—I'm talking about agentic AI, but also modern DevOps practices, cloud-native architecture, modern tooling—to reduce cycle time by an order of magnitude. Not ten percent faster. Ten times faster."

"That sounds impossible," Amanda said.

"Five years ago, it would have been," Maya agreed. "But I've personally helped three companies achieve similar transformations. The technology exists. The practices exist. What's required is a willingness to fundamentally rethink how work happens."

She turned to Doug and Sarah. "Which is why I want to propose an experiment. We take one team—a team willing to try new approaches—and we run a twelve-week pilot. New tools, new processes, new mindset. We measure everything: cycle time, quality, team satisfaction. And we see if we can prove that a different way is possible."

"And if it works?" Tom asked.

"If it works, we scale it. Gradually, sustainably. We don't force change top-down. We let success speak for itself."

"And if it doesn't work?" Amanda asked.

Maya met her gaze. "Then you'll have data showing it doesn't work, and you can make informed decisions. But I believe it will work. I've seen it work. And I think you have everything you need to make it happen."

Tom looked at Doug. "What do you think? Would you be willing to run this pilot?"

Doug felt everyone's eyes on him. This was it—the moment where he could play it safe, say it was too risky, point out all the reasons it might fail.

Or he could take the leap.

He thought about the feature timeline he'd mapped. Seventy-eight days for a button. He thought about his daughter's disappointed face when he missed her recital. He thought about the exhaustion in Keisha's voice when she'd said twelve percent.

"I'm in," Doug said. "But I'll need support. Authority to change processes for the pilot team. Protection from the usual bureaucracy. And I'll need Keisha Washington's team—they're ready for this."

"Done," Tom said. "Whatever you need."

Amanda Foster spoke up. "I want to see weekly metrics. Cycle time, deployment frequency, quality indicators. And I want to see business impact—customer satisfaction, feature adoption, revenue impact."

"Absolutely," Maya said. "Transparency is essential. We'll measure everything."

"Then let's do it," Amanda said. She looked at Tom. "You've got your ninety days. Use them wisely."

---

After the meeting, Doug found himself in the elevator with Maya.

"That was intense," Doug said.

"That was necessary," Maya replied. "The board needs to see you're serious about change. And you need air cover to actually make change."

"I still don't know what I'm doing."

"That's okay," Maya said. "We'll figure it out together. Tomorrow, 3 PM. Bring your notebook."

The elevator doors opened and she walked out, leaving Doug standing there, feeling a mix of excitement and terror.

He'd just committed to transforming how his team worked in twelve weeks, using technologies and practices he barely understood, while the board watched every metric and the ninety-day countdown ticked away.

No pressure.

---

Doug spent the rest of Monday telling people about the pilot. First Keisha, who reacted with cautious enthusiasm.

"What exactly are we piloting?" she asked.

"Honestly? I'm still figuring that out. But basically, we're going to rethink how we work. New tools, new processes, focus on flow instead of process compliance."

"And if it doesn't work?"

"Then at least we tried something different instead of slowly drowning in the status quo."

Keisha laughed. "You know what? I'm in. My team is so burned out, we're willing to try anything."

Next was Raj, who was predictably skeptical.

"So let me get this straight," Raj said. "You're going to experiment with one team while the rest of us keep dealing with the same broken processes?"

"For now, yes. If it works, we scale it."

"And if it doesn't?"

"Then you can say 'I told you so' and we'll go back to how things were."

"Things aren't working now," Raj pointed out.

"Exactly. So what do we have to lose?"

Raj was quiet for a moment. "I want to be involved. Not on the pilot team, but I want to see what you're doing. Review the results. Be part of the evaluation."

Doug hadn't expected that. "Really?"

"I care about this place," Raj said. "Even if I'm skeptical about magical solutions. If there's a better way to work, I want to understand it."

"Deal," Doug said.

By the end of the day, word had spread through the engineering team. The reactions ranged from excited (Lisa) to cynical (some of the senior engineers who'd seen transformation initiatives come and go) to curious (most people).

Doug sent an email to the pilot team—Keisha's group of eight engineers—asking them to block Thursday morning for a kickoff meeting.

Then he opened his notebook and started making a list of questions for Maya:
- What tools do we need?
- How do we change processes without getting pushback?
- What does "agentic AI" actually mean in practice?
- How do we measure success?
- What if people resist?
- What if I screw this up?

He stared at that last question for a long moment, then crossed it out. Fear of failure was understandable, but it couldn't drive decisions. Not anymore.

Doug closed his notebook and looked around the office. Most people had gone home. The fluorescent lights hummed overhead. His computer screen glowed with unread notifications.

For the first time in months, Doug didn't feel overwhelmed by it all. He felt something different.

He felt ready.

The system was broken. Everyone knew it. But now, finally, they had permission to fix it.

Or at least to try.

That would have to be enough.
