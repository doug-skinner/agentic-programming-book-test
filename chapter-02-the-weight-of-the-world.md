# Chapter 2: The Weight of the World

Doug's alarm went off at 6:30 AM, which was already generous considering his calendar showed back-to-back meetings starting at 8:00. He'd been asleep for five hours—better than the night before, but still not enough to shake the fog of exhaustion that had become his constant companion.

In the shower, he ran through his mental checklist for the day. The incident post-mortem presentation needed finishing. The Q4 planning doc was due to Sarah by end of day. The performance review cycle was starting, which meant writing evaluations for eleven direct and indirect reports. And somewhere in there, he needed to actually write some code or at least review the hundred-plus pull requests waiting for his attention.

His wife, Michelle, was already at the kitchen table with their son, Jake, helping him with homework that was apparently due today despite being assigned three weeks ago.

"Morning," Doug said, pouring coffee into his travel mug.

"Did you remember Jake has a dentist appointment at 3:30?" Michelle asked, not looking up from the math worksheet.

Doug's stomach dropped. "I... have a sprint planning meeting at 3:00."

"Doug." Michelle finally looked at him, and he saw the frustration in her eyes. "You promised you'd take him this time. I've taken him to the last four appointments."

"I know, I'm sorry, it's just—this sprint planning has been on the calendar for weeks, and with everything happening at work—"

"Everything is always happening at work," Michelle said quietly. "That's the problem."

Doug didn't have a good answer for that. He kissed Jake on the head, grabbed his coffee, and headed out to face another day.

---

The ShopStream office was in a converted warehouse in SoMa, open floor plan with exposed brick and supposedly "collaborative" spaces that mostly just meant nowhere to focus. Doug's desk was in the middle of the engineering pit, surrounded by other engineers' desks, which meant constant interruptions.

He'd barely sat down when Lisa Park appeared at his elbow.

"Doug, do you have a minute? I'm blocked on the payment gateway integration."

Doug looked at his screen. His first meeting started in seven minutes. "Can you send me a Slack with the details? I'll look at it after standup."

"I did send a Slack," Lisa said. "Yesterday afternoon. And this morning."

Right. The messages he hadn't read. "Okay, pull up a chair, let's look at it now."

Fifteen minutes later, Doug had helped Lisa unblock herself and was now ten minutes late to the architecture review meeting. He speed-walked to Conference Room A, where five people were staring at laptops, waiting.

"Sorry, sorry," Doug said, sliding into a chair. "What did I miss?"

"We were just discussing the proposal to split the monolith into microservices," said Raj, bringing up a detailed architecture diagram on the screen. "I've outlined a six-month plan to extract the inventory service first."

Doug studied the diagram. It was thorough, well-thought-out, and probably something they should have done two years ago. It was also a massive undertaking that would consume enormous amounts of engineering time while delivering no new features to customers.

"This is great work, Raj," Doug said carefully. "But with the board's ninety-day timeline, I don't think we can commit to a six-month architectural overhaul."

Raj's expression hardened. "The ninety-day deadline is exactly why we need to do this. We can't keep building on this technical debt. Every new feature takes longer than the last because the codebase is a mess."

"I agree the technical debt is a problem—"

"Then let's fix it," Raj interrupted. "Or are we just going to keep slapping band-aids on everything until the whole system collapses?"

The room went silent. Doug felt everyone's eyes on him, waiting to see how he'd respond.

"Raj, I hear you," Doug said. "And you're right about the technical debt. But we also need to deliver value to customers in the next ninety days, or there won't be a system to refactor."

"So we're choosing short-term survival over long-term sustainability," Raj said flatly.

"I'm choosing to keep people employed," Doug said, and immediately regretted the sharpness in his tone.

Another awkward silence.

"Let's table this for now," Doug said. "We'll revisit the microservices proposal after we see what the new advisor recommends."

Raj closed his laptop with more force than necessary. "The advisor who's never seen our codebase and doesn't understand our constraints."

The meeting limped along for another thirty minutes before Doug escaped to his next meeting: sprint planning with Keisha Washington's team.

---

By noon, Doug had been in four meetings and hadn't written a single line of code. He grabbed a sad-looking salad from the break room and ate at his desk while catching up on Slack messages.

The engineering channel was a mix of technical questions, incident reports, and general complaints:

**Jen**: "Prod is slow again. Anyone else seeing this?"

**Lisa**: "Getting 500 errors on the checkout endpoint."

**Random Engineer**: "Is the deployment pipeline broken? My build has been running for an hour."

**Another Engineer**: "Can someone review my PR? It's been open for a week."

Doug took a bite of wilted lettuce and wondered if other engineering leads felt this way—like they were playing whack-a-mole with an infinite number of moles.

His calendar pinged. Company all-hands in Conference Room C in five minutes.

The all-hands meetings had become increasingly tense over the past year. Tom would present optimistic slides about growth and opportunity while everyone in the room did the math on their severance packages.

Doug grabbed his laptop and headed to the largest conference room, which was already packed. He found a spot standing in the back next to Keisha.

"How's your day going?" Keisha whispered.

"If one more person asks me for 'just five minutes,' I'm going to start charging rent for space in my calendar," Doug whispered back.

Keisha smirked. "I had someone ask me if I could 'just quickly' review their architectural proposal. It was forty-seven pages."

Tom Bradley strode to the front of the room, his usual charismatic energy slightly dimmed. He clicked through to his first slide: "ShopStream: The Path Forward."

"I know the past few days have been challenging," Tom began. "The Black Friday incident was unacceptable, and I take full responsibility for—"

"With all due respect," someone called out from the middle of the room—David Okonkwo from the security team—"taking responsibility doesn't mean much if we keep having the same incidents."

Tom paused, clearly not expecting to be interrupted. "You're absolutely right, David. Which is why I'm excited to announce that we're bringing in some expert help."

He gestured to the side of the room, and Doug noticed for the first time a woman sitting quietly in one of the chairs against the wall. She was probably in her early fifties, with gray-streaked black hair pulled back in a simple ponytail. She wore jeans and a blazer, and she was watching the room with an expression of calm interest.

"This is Dr. Maya Patel," Tom said. "Many of you might know her name. She was the CTO of DataFusion before they sold to Microsoft for two billion dollars. She's advised half a dozen unicorn startups on technical transformation. And she's agreed to work with us to help turn things around."

The room broke into murmurs. Doug studied Maya. She didn't look like the typical consultant—no expensive suit, no polished presentation, no air of superiority. She just looked... present.

"I'm not here to tell you what to do," Maya said, standing up. Her voice was quiet but clear, and somehow it commanded attention. "I'm here to observe, to listen, and to ask questions. Over the next week, I'll be shadowing different teams, understanding how work flows through the organization. Or doesn't flow, as the case may be."

A few people chuckled nervously.

"I know you're all working incredibly hard," Maya continued. "I can see it in your faces. Long hours, constant firefighting, never enough time to do things right. But hard work alone isn't enough. We need to work differently. And that starts with understanding what's really happening."

Doug found himself nodding. At least she wasn't coming in with a pre-packaged solution.

"I'll be around all week," Maya said. "If you see me lurking, don't change what you're doing on my account. I'm here to learn your reality, not a sanitized version of it."

After the meeting, Doug was heading back to his desk when he felt a tap on his shoulder. He turned to find Maya standing there.

"Doug Mercer?" she asked.

"That's me."

"I was hoping I could shadow you for a few hours this afternoon," Maya said. "Tom mentioned you were one of the senior engineering leads who's been here through most of the company's growth."

Doug thought about his calendar. Sprint review at 2:00, the planning doc he needed to finish, the dentist appointment he was probably going to miss, the hundred pull requests waiting for review.

"Sure," he said, because saying no to a board-appointed advisor seemed like a bad career move. "Though I should warn you, it's mostly just meetings and putting out fires."

"That," Maya said with a slight smile, "is exactly what I want to see."

---

Maya was true to her word. She sat quietly in the corner during Doug's sprint review, taking notes. She watched him field a dozen interruptions between meetings. She observed him spend twenty minutes helping a junior engineer debug a problem that turned out to be a missing semicolon.

She didn't ask questions. She just watched.

It was unnerving.

By 3:15, Doug had missed Jake's dentist appointment. Michelle's text was brief: "Really, Doug?"

Doug stared at his phone, a familiar shame settling in his chest. He'd done it again. Chosen work over family. Except it didn't feel like a choice—it felt like drowning.

"Everything okay?" Maya asked.

Doug looked up. She was still there, notebook in hand, expression neutral.

"Missed my son's dentist appointment," Doug said, not sure why he was telling her this. "Again."

Maya nodded slowly. "May I ask you something?"


"Sure."

"How many hours did you work last week?"

Doug thought about it. "I don't know. Sixty? Seventy? There was the Black Friday incident, so that kind of messed up the count."

"And the week before that?"

"Probably similar."

"How long can you sustain that pace?"

Doug laughed bitterly. "Apparently, I can't. I'm missing my kids' lives. My wife is frustrated. I'm exhausted all the time. But what's the alternative? There's too much work and not enough people."

"Is that true?" Maya asked. "Not enough people? Or not enough capacity?"

"Same thing, isn't it?"

"Is it?" Maya didn't wait for an answer. "I'll let you get back to work. Thank you for letting me observe."

She left, and Doug sat there, staring at his screen full of unfinished tasks, wondering what the difference was between not enough people and not enough capacity.

His calendar pinged. Another meeting in five minutes.

Doug closed his eyes for just a moment, trying to remember what it felt like to not be this tired, and then he grabbed his laptop and headed to Conference Room B.

The weight of the world was on his shoulders, and it was getting heavier by the day.
