# Chapter 8: Small Wins

Three weeks into the pilot, Doug was starting to believe.

It was Friday afternoon, and he was in Conference Room D with Keisha and Maya, looking at the metrics dashboard they'd built to track the pilot team's progress. The numbers were compelling:

**Week 1 vs Week 3:**
- Average code review time: 72 hours → 4 hours (94% reduction)
- PRs merged per week: 8 → 23 (188% increase)
- Defects found in code review: 12 → 31 (159% increase)
- Defects found in production: 5 → 1 (80% reduction)

"The defect numbers are the most interesting," Keisha said. "We're catching more issues before they hit production, which means the code going out is actually better quality, even though we're shipping faster."

"How's the team feeling about it?" Maya asked.

"Mixed, but mostly positive. Lisa is all in—she says she can't imagine going back. Carlos is cautiously optimistic. Priya is still skeptical about some things but admits it's helping."

Doug pulled up another chart. "What about cycle time?"

Keisha clicked through to the feature delivery metrics. "This is the big one. Look at this."

The chart showed features from inception to production. The pilot team had shipped three complete features in three weeks. For ShopStream, that was unprecedented.

"What were they?" Maya asked.

Keisha listed them: "Enhanced search filters, a new customer dashboard, and improved error messages throughout the checkout flow. None of them huge, but all of them valuable. And combined, they've already reduced support tickets by eighteen percent."

"That's real customer impact," Doug said. "Mark must be happy."

"Mark is confused," Keisha said with a laugh. "He keeps asking what changed. He's not used to engineering delivering this fast."

Doug's phone buzzed. Speak of the devil—it was Mark, asking for a meeting next week to discuss "the new process."

"So it's working," Maya said. "But tell me about the challenges. What's not working?"

Keisha's smile faded slightly. "The AI test generation is hit or miss. Sometimes it suggests brilliant test cases we hadn't thought of. Other times it suggests tests that don't really make sense for our codebase. The team is learning to filter the good from the noise, but there's a learning curve."

"That's normal," Maya said. "What else?"

"Integration with our CI/CD pipeline has been rocky. We've had a few false positives where the AI flagged issues that weren't actually issues, and that slowed down deployment. We're tuning it, but it's not perfect."

"Nothing is perfect," Maya said. "Perfection isn't the goal. Better is the goal. Are you better than three weeks ago?"

"Absolutely," Keisha said without hesitation.

"Then keep learning and keep improving. What about team morale?"

Keisha pulled up the team satisfaction survey they'd been running weekly. "This is interesting. Look at the question about 'feeling productive.'"

The chart showed a clear upward trend. Week 1: 4.2 out of 10. Week 3: 7.8 out of 10.

"They feel like they're actually accomplishing things," Keisha said. "Wei told me yesterday that for the first time in months, he doesn't feel like he's constantly waiting for someone else. Lisa said she feels like a 'real engineer' now that she can ship features instead of just working on pieces that sit in review forever."

Doug felt a warmth in his chest. This was why he'd gotten into software in the first place—to build things, to solve problems, to create value. Not to manage bureaucracy and attend meetings about meetings.

"There's something else," Keisha said, pulling up Slack. "Look at this."

She showed them a thread in the #engineering channel. Engineers from other teams were asking about the pilot. What tools were they using? How did they get access? Could their team try it too?

"We have a demand problem," Keisha said. "People want in."

"That's a good problem," Maya said. "But we need to be careful. Scaling too fast, before we've really learned what works, would be a mistake. How do you feel about running for another three weeks before we expand?"

"I think that's wise," Keisha said. "We're still learning. And I want to see these results hold up over time."

Doug nodded. "Agreed. Let's get to six weeks, show consistent results, then talk about how to expand."

"In the meantime," Maya said, "let's prepare. Document what you're learning. Create a playbook for other teams. Identify what works, what doesn't, and what needs to be adapted for different contexts."

"I can help with that," Doug said. "And we should probably do a presentation for leadership. Show them the results, get their buy-in for expansion."

"Good idea," Maya said. "Let's aim for week six. That gives us three more weeks of data and time to prepare."

---

Monday morning, Doug arrived to find Raj waiting at his desk.

"We need to talk," Raj said.

Doug's stomach tightened. Raj's skepticism had been quiet but persistent, and Doug had been waiting for the other shoe to drop.

"Sure. What's up?"

"I've been watching the pilot team's code reviews," Raj said. "I'm on the review list for some of their PRs since I'm familiar with that part of the codebase."

"And?"

"And I'm seeing code I've never seen from some of these engineers. Lisa, for example. She submitted a refactoring of the inventory service last week that was genuinely impressive. Smart use of caching, clean abstraction, good error handling. Lisa's talented, but three months ago, she was still learning our patterns."

Doug wasn't sure where this was going. "The AI helps her—"

"I know it helps her," Raj interrupted. "That's my point. It helps her punch above her weight. And it's not just Lisa. Carlos shipped that checkout improvement in three days. Three days for something that would have taken us three weeks before. The code is good. Actually, it's very good."

"So... you're saying it's working?"

Raj was quiet for a moment. "I'm saying I was wrong to be as dismissive as I was. The results are there. But I have questions."

"Shoot."

"First, what happens to skill development? If junior engineers are getting AI help for everything, are they really learning, or are they just getting good at prompting AI?"

It was a fair question. "Lisa would say she's learning more, not less. The AI explains its suggestions. It shows her patterns she wouldn't have known to look for. It's like having a patient mentor available all the time."

"Maybe," Raj said. "I'd want to talk to her about that. Second question: what about the rest of us? We're still drowning in code reviews and slow processes while the pilot team operates in a different universe. It's creating tension."

"I know. That's why we're planning to expand—"

"When?" Raj asked directly. "Because right now, it feels like there are two classes of engineers. The pilot team with the magic tools, and the rest of us grinding away in the old system."

Doug felt the weight of that. "Six weeks. We want to make sure it's sustainable before we scale."

"Six weeks is a long time when you're watching other people succeed while you're stuck," Raj said.

"What if," Doug said slowly, "you were part of the next expansion? Not just evaluating, but actually using the tools?"

Raj looked surprised. "Me?"

"You're a staff engineer. You set patterns for others. If you adopt this and it works for you, that sends a powerful message."

Raj considered this. "I'd want to understand it thoroughly first. Not just use tools blindly."

"Fair. What if you spent time with the pilot team this week? Shadow them. Ask questions. See how they're actually using AI, not just what the results are."

"I could do that," Raj said. "And I want access to the metrics. All of them, not just the highlights."

"Done. I'll send you the dashboard link."

Raj stood to leave, then paused. "Doug, I'm not trying to be difficult. I care about this place. About doing things right."

"I know. That's why I want you involved."

After Raj left, Doug sent a quick message to Keisha: "Raj wants to shadow the team this week. Can you facilitate?"

The response was immediate: "Absolutely. This could be good."

---

Wednesday afternoon, Doug was in a planning meeting with Mark when his phone buzzed with an alert from the metrics dashboard. He glanced at it: the pilot team had just deployed their fourth major feature in three weeks.

Mark was mid-sentence about Q4 roadmap priorities when he stopped. "You're not listening."

"Sorry," Doug said. "The pilot team just shipped another feature."

"Another one? How many is that?"

"Four in three weeks."

Mark pulled out his laptop and opened the feature tracking board. "Four features that were on our roadmap? Real features?"

"Real features with real customer value," Doug confirmed.

Mark stared at the screen. "Doug, we shipped eleven features last quarter. Across the entire engineering team of eighty people. Eight engineers just shipped four features in three weeks. What the hell changed?"

"The system changed. We reduced wait times, improved flow, gave them tools that multiply their leverage."

"The AI stuff," Mark said.

"The AI stuff, yes. But it's more than that. It's about optimizing for flow, not local efficiency. About reducing coordination costs. About—"

"I don't need the theory," Mark interrupted. "I need to know if we can do this for the whole team. Can we?"

"We're planning to expand at week six."

"Not fast enough," Mark said. "The board wants to see results. We have six weeks left in the quarter. If we could scale this—if even half the team could operate like the pilot team—we could actually hit our Q4 goals. Maybe exceed them."

"Mark, we can't scale too fast. We need to—"

"Doug, I'm not saying abandon caution. But I am saying opportunity cost is real. Every week we don't scale this, we're losing potential value. How can we accelerate?"

Doug thought about it. Maya's advice echoed: scale sustainably. But Mark had a point about opportunity cost.

"What if we identify two more teams for week four?" Doug suggested. "Teams that are ready, that want to try this. We don't force it, we let them opt in. We give them the same support we gave the pilot team. We see if the results replicate."

Mark nodded. "Do it. Who should the teams be?"

"I need to talk to Sarah and the other engineering managers. But teams that are high-functioning, willing to experiment, and working on valuable features."

"Talk to them today," Mark said. "I want to present a scaling plan to the board next week."

After the meeting, Doug found himself back in front of his laptop, looking at the engineering team org chart. Who would be good candidates for the next wave?

He sent messages to three engineering managers: Keisha (the pilot team), Rahman (who led the infrastructure team), and Yuki (who led the customer experience team). Could they meet tomorrow to discuss expansion?

All three responded within minutes: Yes.

Doug's calendar pinged with a reminder: Emily's parent-teacher conference at 4 PM. He'd almost forgotten.

He checked the time: 3:15. He could make it if he left now.

On his way out, he passed Lisa at her desk. She was in what looked like deep focus, code on one screen, AI suggestions on another, music playing through her headphones.

She looked up as he passed and gave him a thumbs up and a huge smile.

That smile made everything worthwhile.

Doug grabbed his coat and headed out. For once, he was going to make it to the family commitment on time.

And for once, he had good news to share: things were actually getting better.

Small wins, he thought. But wins nonetheless.

And sometimes, small wins were exactly what you needed to keep going.
