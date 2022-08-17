- https://agilemanifesto.org/
- {{tweet https://twitter.com/_workchronicles/status/1499659722093432832}}
- Main problems of [[Agile]] (long rant):
	- Values:
		- Individuals and interactions over processes and tools
			- Individual victories vs systematic victories
			- The [[process]] should be an [[asset]], not a [[liability]] ([[asset-liability duality]]), i.e. it needs to be preferred, or improved until preferred
		- Working software over comprehensive documentation. Alternatives:
			- Code is documentation: [[elegance]]
			- Documentation runs: [[literate programming]] (consider: Jupyter notebook, presentation with hidden code cells)
			- Documentation is the [[tests]] / spec: [[TDD]]
		- Customer collaboration over contract negotiation. Risks:
			- [[moving the goalposts]]
			- [[adding epicycles]], especially when failure is not acknowledged or causes are not properly diagnosed
			- [[delusion]], [[confirmation bias]], [[Clever Hans]]
				- https://xkcd.com/882/
	- Principles (only a few to comment, they are in fact not too bad):
		- Our highest priority is to satisfy the customer through early and continuous delivery of valuable software
			- This is OK, but extremely dangerous
			- The point should be solving problems, feedback on the solution may not help to understand the problem
			- Understanding what users want does not imply understanding what users need
			- See Homer Simpson's car design
		- The most efficient and effective method of conveying information to and within a development team is face-to-face conversation
		- Working software is the primary measure of progress
			- It may be a [[delusion]] though
		- Simplicity--the art of maximizing the amount of work not done--is essential
			- This is in fact good, but not always applied properly
			- IMHO, to work less: smooth processes, tools for automation, more planning, i.e. finding out by thinking rather than by coding
			- Bad application
		- The best architectures, requirements, and designs emerge from self-organizing teams
			- That is good, considering [[Conway's law]]
			- Few organizations have this level or maturity, though, making this point a perfect excuse to blame the bad application of the agile principles, rather than the Agile manifesto, it seems to be here just to provide [[plausible deniability]]
		- At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly
			- If the most senior staff had to define a [[process]], that would be a problem for the [[plausible deniability]]
			- Instead, focus on the behavior (or attitude) of the least senior staff. What could go wrong?
			- While constant improvement of the process is important and necessary, it is also delicate and it may backfire
				- It has to be done in a proper way, as scientific as possible
				- Otherwise, the result is pseudoscience, superstition, and bullshit
				- The behavior may adjust to spurious correlations, or overfit to anecdotal events, possibly outliers
			- At regular intervals provides regularly adjusting the narrative
- Core issue
	- If the project is easy, agile might help:
		- Agile eliminates a lot of _(potential)_ bureaucracy that would make the problem harder
		- You may choose instead [[common sense]]. Agile may help to compensate for a lack thereof
		- Agile is vague and ambiguous enough for an easy project to become a hell of epicycles if applied in a not entirely unusual way: disregard thinking, planning, and understanding, prioritize feedback, building, and iterating
	- If the project is hard, agile might not help:
		- The space of solutions is large, most are bad, even among the ones that "seem to work"
		- There are more delusions of solutions than in fact good solutions, result: [[cargo cult]], [[Clever Hans]]
		- It is possible to spend infinite time exploring:
			- local maxima neighborhoods, without moving to better neighborhoods
			- infinite branches that contain no good solutions
		- Eventually, this may lead to loss of credibility, but it may happen in many different ways:
			- Internal to the [[organization]]: in [[pathological organizations]] decision makers lead technical people without decision power, the least flattering may be chosen as escape goats
				- Paradoxically, when mistakes have been made by decision makers, the least flattering technical people may be "less wrong" and may have been criticizing those mistakes
				- Peak pathological organization:
					- > "I was not mistaken, if you had you followed my instructions properly and worked 80h/week, we would now have a perfectly working submarine made of cheese! The only problem is your defeatist attitude!"
			- Among clients: requires rebranding (the former branding is the escape goat)
				- I can imagine that eventually companies run out of chances to keep doing the same mistakes with different names, but:
				  > "No man ever steps in the same river twice, for it's not the same river and he's not the same man." -- Heraclitus

 			    If the river is fast enough, the man may not need to change to fish new fishes and keep the cash flow, indefinitely
				- i.e. eventually, but indefinitely
			- Using the technology or the technological limitations as the escape goat
			  collapsed:: true
				- We just need:
				  * more training data
				  * more training time
				  * more GPUs/TPUs
				  * more development time
				  * more epicycles
				- Alternatively:
				  * Logic symbols cannot do that, we need embeddings
				  * Embeddings cannot do that, we need logical rules
				  * etc.
				- The result may be bad reputation for some technology, which is normally not appreciated for the practitioners of that technology. This bad reputation may be deserved or undeserved
					- But by definition in the context of this paragraph, the actual problem were decision makers, exploring the wrong space for solutions, and not the technology, which is then chosen as the escape goat, i.e. it is undeserved
			- "Eventually" is far in the future: then anything is accepted as "it has always been this way"
				- No loss of credibility, disruption as a "new way" of doing things
			- Everybody (incl. competitors) loses credibility: skepticism, cynicism, [[kakonomy]], or [[market for lemons]]
