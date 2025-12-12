# Chapter 9: Resistance

The engineering all-hands on Friday morning started normally enough. Sarah walked through the usual updates: hiring progress, infrastructure improvements, upcoming company events. But Doug could feel the tension in the room. Word about the pilot team's success had spread, and not everyone was happy about it.

"Before we wrap up," Sarah said, "I want to talk about the agentic AI pilot we've been running with Keisha's team. Doug, can you share an update?"

Doug stood and pulled up the metrics dashboard on the big screen. He'd rehearsed this presentation, anticipating questions, but he still felt nervous.

"For the past four weeks, we've been running an experiment with one team. The goal was to see if we could improve flow—get features from idea to customer faster, without sacrificing quality."

He clicked through the slides. "The results have been promising. Cycle time reduced by 85%. Defect rates down. Team satisfaction up. We're shipping valuable features at a pace we haven't seen before."

He paused, waiting for questions. They came immediately.

A senior engineer named Mike spoke up. "So AI is writing all their code now?"

"No," Doug said. "AI is assisting with code review, test generation, and some automation. The engineers are still doing the creative work—architecture decisions, feature design, problem-solving. The AI handles repetitive tasks and catches common issues."

"Sounds like you're replacing engineers with AI," Mike said.

"We haven't reduced headcount," Doug countered. "We've increased output. Same team size, more value delivered."

"For now," Mike said. "But once management sees they can get the same work from fewer people—"

"That's not the goal," Sarah interjected. "We have infinite demand for software. The question isn't whether we need fewer engineers. It's whether we can help our engineers be more effective."

Raj raised his hand. "I've been shadowing the pilot team this week. I want to address Mike's concern directly."

All eyes turned to Raj. Doug held his breath.

"I was skeptical," Raj said. "Very skeptical. I thought this was going to be overhyped tools that promised magic and delivered garbage. But after watching how the team actually uses AI, I have a different perspective."

He stood. "The AI doesn't replace engineering judgment. It amplifies it. Lisa—a junior engineer with less than a year of experience—shipped a refactoring that I would have been proud of. Not because the AI wrote it for her, but because the AI helped her learn faster. It showed her patterns, explained trade-offs, caught mistakes she didn't have the experience to see yet."

Raj looked around the room. "For senior engineers like me, it's different but equally valuable. I don't need AI to teach me patterns. But I do need something to handle the boring stuff—checking for null references, pointing out obvious performance issues, verifying that I'm following our style guide. That frees me up to focus on architecture and mentoring."

"But what about job security?" Mike pressed. "If AI can do the boring stuff, why would companies hire as many engineers?"

"Because the boring stuff isn't the valuable stuff," Raj said. "The valuable stuff is understanding customer needs, designing systems that scale, making architectural decisions, collaborating with product. AI can't do that. AI can help us do that better."

Another engineer, David from security, spoke up. "What about security? How do we know AI-generated code suggestions don't introduce vulnerabilities?"

"Good question," Doug said. "We've actually seen the opposite. The AI flags security issues more consistently than human reviewers. It caught three potential SQL injection vulnerabilities that made it through human review in the past. David, I'd love your input on this—can we set up time for you to review the security aspects?"

David looked surprised to be invited in. "Yeah, I'd be interested in that."

"What about the rest of us?" This was from an engineer Doug didn't recognize. "We're stuck with the old process while the pilot team gets all the cool tools. When do we get access?"

"That's exactly what I wanted to discuss," Sarah said. "We're planning to expand. But we want to do it sustainably. Doug?"

Doug pulled up the next slide. "We're looking to add two more teams in the next two weeks. Teams that volunteer, that want to try this approach. Then, if those teams also see good results, we'll continue expanding gradually. Our goal is to have half the engineering organization on the new tools by end of quarter."

"Why so slow?" the same engineer asked. "If it's working, why not roll it out to everyone now?"

"Because we're still learning," Doug said. "Every team is different. What works for Keisha's team might need to be adapted for infrastructure or customer experience. We want to learn from each wave of adoption and improve the process."

"Also," Maya added from the back of the room—Doug hadn't even known she was there—"forced change creates resistance. Change that people opt into creates ownership. We want teams to choose this because they see the value, not because leadership mandated it."

An uncomfortable silence followed.

Then Mike spoke again. "I appreciate the explanation, but I'm going to be honest: I don't trust this. We've seen a lot of fads in software development. Agile, DevOps, microservices—all promising to revolutionize how we work. Some helped, some didn't. This feels like another fad."

"That's a fair concern," Maya said, walking to the front. "May I?"

Sarah nodded.

"Mike's right," Maya said. "Software development has seen a lot of fads. And the worst thing we could do is treat agentic AI like a silver bullet that will magically fix everything. It won't."

She paused, making eye contact with skeptics around the room. "What makes this different isn't the technology itself. It's that we're being intentional about changing how work flows. The AI is a tool, not a solution. The solution is reducing wait times, eliminating bottlenecks, empowering engineers to own features from start to finish."

"We could do that without AI," Mike said.

"You could," Maya agreed. "But you haven't. Why not?"

Mike opened his mouth, then closed it.

"I'll tell you why," Maya continued. "Because the coordination costs are too high. With traditional tools and processes, you need separate code review, separate QA, separate deployment specialists. The wait times are inherent to the model. AI doesn't eliminate those roles—it reduces wait times so the experts can focus on high-value work instead of routine tasks."

"It still feels like replacement," Mike muttered.

"Then help us prove it isn't," Maya said. "Join the next wave. Use the tools. See for yourself whether they help you or threaten you. The data will speak for itself."

Mike didn't respond, but he didn't look convinced either.

Sarah wrapped up the meeting. "Look, change is hard. I get it. But we have a choice: adapt and improve, or maintain the status quo and watch the company fail. I'm choosing to adapt. I hope you'll join us."

As people filed out, Doug noticed the conversations. Some engineers were excited, asking how to volunteer their team. Others were skeptical, clustering together with concerned looks.

Raj approached Doug. "That was rough."

"Yeah," Doug agreed. "Mike's not going to come around easily."

"Mike's scared," Raj said. "He's a senior engineer who's built his career on being the expert, the person who knows more than anyone else about the codebase. AI threatens that identity."

"What do we do about it?"

"Give him space. Don't force it. Some people will need to see it working for others before they're willing to try. But Doug—" Raj lowered his voice. "Don't let fear slow you down. Mike's concerns are valid, but they can't veto progress."

---

That afternoon, Doug met with David, the security engineer who'd asked about vulnerabilities. Doug had invited him to review the AI code review tool's security scanning capabilities.

David spent an hour going through the tool, testing it with deliberately vulnerable code, reviewing its suggestions. Doug watched, nervous about what he'd find.

Finally, David leaned back. "Okay, this is actually impressive. It caught things I would have caught, plus a few I might have missed. The false positive rate is a bit high—it flagged some things that aren't actually vulnerabilities in our context—but overall, it's solid."

"So you're comfortable with it from a security perspective?"

"I'm comfortable with it as an assistant," David said. "I wouldn't trust it blindly. But as a first line of defense that catches obvious stuff and flags potential issues for human review? Yeah, this works."

"Would you be willing to say that in writing? Maybe do a security review and publish your findings to the team?"

David thought about it. "Yeah, I can do that. It might help address some of the concerns."

"That would be huge. Thank you."

As David left, Doug felt a small win. One skeptic addressed. How many more to go?

His phone buzzed. A Slack message from an engineer named Tomás, who worked on a different team:

> "I heard about the pilot. My team wants in. What do we need to do?"

Doug smiled and typed back: "Let's talk Monday. I think your team would be a great fit for the next wave."

Another message came in, this time from Michelle, the QA lead:

> "We need to talk about the pilot team's testing approach. Some concerning patterns I'm seeing."

Doug's smile faded. He typed: "Conference room in 10 minutes?"

When Michelle arrived, she had printouts of test reports. "Look at this. The pilot team's test coverage is down from last month. 76% coverage now versus 82% before."

"But their defect rate in production is down," Doug pointed out.

"I know. That's what's confusing me." Michelle spread out the reports. "They're writing fewer tests, but catching more bugs. It doesn't make sense."

"May I?" Doug pulled up the pilot team's testing dashboard. "They're using AI-assisted test generation. The AI suggests edge cases they might not have thought of. So they're writing fewer tests overall, but the tests they're writing are more targeted at actual risk areas."

"That could be good or could be dangerous," Michelle said. "How do we know they're not missing critical test cases?"

"Fair question. What if you worked with the pilot team for a week? Review their testing strategy, see where the gaps are, help them improve? Your expertise could make this even better."

Michelle considered this. "I'd need Sarah's approval to shift my time."

"I'll talk to Sarah. This is important."

"Okay," Michelle said. "But Doug, I'm serious about this. Quality can't be sacrificed for speed."

"I agree completely. That's why I want you involved."

After Michelle left, Doug sat back and rubbed his eyes. Every step forward seemed to create two new challenges. Skeptics to convince. Processes to adapt. Concerns to address.

His phone rang. It was Sarah.

"Tom wants a board update on the pilot next week," she said without preamble. "He wants to show momentum."

"We have good metrics," Doug said.

"He wants more than metrics. He wants a roadmap for company-wide adoption. How fast can we scale?"

"Sarah, we've talked about this. Scaling too fast—"

"I know. But the board is impatient. We have six weeks left on their ninety-day deadline. They want to see transformation, not just a successful pilot."

Doug felt the pressure building. "Let me talk to Maya and Keisha. We'll put together options."

"By Monday," Sarah said. "Tom wants to review before the board meeting."

After she hung up, Doug sat in the quiet conference room, feeling the weight of it all. The pilot was working. People were excited. But also scared. And now leadership wanted to accelerate before they'd really proven sustainability.

His phone buzzed with a text from Emily: "Can you help with my science project tonight?"

Doug looked at the clock. 5:30 PM. He'd promised to be home by 6:00.

He closed his laptop and stood up. The challenges would still be there tomorrow. His daughter wouldn't be seven forever.

On his way out, he passed the pilot team's area. They were wrapping up for the day, talking and laughing. They looked like a team that was winning.

Whatever resistance they faced, whatever challenges lay ahead, that sight made it worthwhile.

Change was never easy.

But maybe, just maybe, it was worth it.
