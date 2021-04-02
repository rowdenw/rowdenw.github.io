---
discussion_id: Grown-Up-Thinking
excerpt: According to Gregory Bateson, the major problems in the world are the result of the difference between how nature works and the way people think. How can we learn to think in better ways?
layout: post
mermaid: true
tags:
  - existential risk
  - growing up
title: Grown-Up Thinking
---

> The major problems in the world are the result of the difference between how nature works and the way people think.

~ Gregory Bateson[^1]

Major problems in the world--[nuclear war](https://80000hours.org/problem-profiles/nuclear-security/), [climate change](https://80000hours.org/problem-profiles/climate-change/), [pandemics](https://80000hours.org/problem-profiles/global-catastrophic-biological-risks/), [artificial intelligence](https://80000hours.org/problem-profiles/positively-shaping-artificial-intelligence/), biotechnology, etc.--mean that we have a nonzero [probability of self-annihilation]({% post_url 2021-01-26-Estimate-Galactic-ETI %}). How can we learn to think in ways that better understand?:

* foreign relations between nuclear powers,
* climatic systems,
* ecosystems,
* intelligent decision-making systems,
* etc.

Herb Koplowitz notes:

> Barry Commoner (quoted in M. Bateson, 1972) and G. Bateson (1972) refer to the inability of adults, scientists, and laymen alike to understand cyclical, patterned phenomena such as interpersonal relationships and a variety of biological processes because they attempt to understand cause-and-effect patterns as linear.[^2]

Koplowitz sees three groups of stages in adult cognitive development:[^3]

* pre-logical,
* logical, and
* post-logical.

Into these groups I'll place stages of [vertical development]({% post_url 2021-03-07-What-Is-Growing-Up %}) (using [Bill Joiner](https://changewise.biz/?page_id=249&..)'s names), and discuss example problems, solutions, and tools from my [workday experience](https://rowdenw.github.io/about/) with management that illustrate how we can think in more complex, systemic, and interdependent ways.[^4]

## Pre-Logical Thinking

Pre-logical thinking is from birth to preteen: Explorer, Enthusiast, and Operator. During the Explorer stage a child develops "object permanence" in what Piaget called the sensorimotor stage, which you can see in a [video on Piaget's Stages of Development](https://www.youtube.com/watch?v=TRF27F2bn-A). During the Enthusiast stage a child learns identity ("I," "me," "mine") and representational thinking (language).[^5]

The Operator stage, or (United States) grade school years, is the earliest developmental stage that persists into adulthood in noticeable numbers: Susanne R. Cook-Greuter's 1999 study of 4510 United States adults scored 4.3% at either the Enthusiast or Operator stage.[^6] You can see the [inability to see another person's point of view](https://youtu.be/TRF27F2bn-A?t=190). This is [Piaget's "concrete operational stage](https://youtu.be/TRF27F2bn-A?t=254)." The Operator externalizes blame,[^7] and when there are signs of trouble they find the cause in someone or something else. Others are to blame, "not me."

![Family Circus Not Me PB (1980 Fawcett)](https://d1466nnw0ex81e.cloudfront.net/n_iv/600/2111858.jpg)

Pre-logical thinkers also think of events as a consequence of the events that immediately precede them,[^3] the *post hoc ergo propter hoc* fallacy.

<div class="mermaid">
graph LR
	B ==> A

	classDef default fill:#FFFFFF, stroke:#FFFFFF
</div>

## Logical Thinking

### Conformer

For most girls, the Conformer stage starts at 11 or 12 years old, while for most boys it starts at 12 or 13 years old. The Conformer stage is well-established by 14 or 15 years old.[^5] This is the early stage in what [Piaget called "formal operations](https://youtu.be/TRF27F2bn-A?t=349)," which includes the ability to use hypotheses for deductive reasoning. Cook-Greuter's 1999 study scored 11.3% of adults at this stage, but a study of United States supervisors found 8.2%, and a study of United Kingdom consultants found 1.7%.[^8]

The Conformer stage responds to signs of trouble by identifying conflict, negative emotion, nonconformity, the outsider, or a rule or standard violation.[^9] Consequently one way to mature thinking is to notice situations in which it is not clear who is "wrong."[^10] One tool for this is a retrospective on failures and successes, using Norm Kirth's Prime Directive:[^11]

> Regardless of what we discover, we must understand and truly believe that everyone did the best job he or she could, given what was known at the time, his or her skills and abilities, the resources available, and the situation at hand.

Another approach to support more mature thinking is [working backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html), for example an [innovation game plan](https://youtu.be/aRff0Fe-3Tk). This can expand thinking beyond a single step to a chain of cause and effect.

<div class="mermaid">
graph LR
	S[ ] -.-> D ==> C ==> B ==> A

	classDef default fill:#FFFFFF, stroke:#FFFFFF
</div>

### Expert

The Expert stage begins in late adolescence for people who go on to become managers, further developing abstract operations. While perhaps 10% of managers remain in a pre-Expert stage, approximately 45% profile at Expert.[^5] Tools to support decision-making at this stage include [current reality tree](https://www.optimalservicemanagement.com/blog/theory-of-constraints-using-a-current-reality-tree/), [decision journals](https://barryoreilly.com/explore/blog/good-to-great-decisions/), and [futures wheel](https://en.wikipedia.org/wiki/Futures_wheel). While these continue to use linear chains of cause and effect, they broaden thinking to consider multiple causes and multiple effects.

<div class="mermaid">
graph LR
	C((C)) ==> A((A))
	C ==> B((B)) ==> A

	classDef default fill:#FFFFFF
</div>

### Achiever

Around 35% of managers profile at Achiever, using full formal operational thinking.[^5] The challenge with linear thinking is identifying the origin of a cause-and-effect chain. The [micromanagement trap](https://www.informit.com/articles/article.aspx?p=1675546&seqNum=6) illustrates the differences of perspective that can occur about "Who started it?" A manager can see their lack of delegation as due to the problems caused by an employees' lack of competence, while an employee can see their lack of competence as a result of lack of experience with real problems.

<div class="mermaid">
graph TD
	subgraph b[Employee's View]
		bM[Manager doesn't delegate] ==>
		bE[Employee lacks experience] ==>
		bP[Employee causes problems]
	end
	subgraph a[Manager's View]
  	aE[Employee lacks experience] ==>
		aP[Employee causes problems] ==>
		aM[Manager doesn't delegate]
	end

	classDef default fill:#FFFFFF, stroke:#FFFFFF
	style a fill:#FFFFFF
  style b fill:#FFFFFF
</div>

A coach might observe that both views can be true in a loop rather than a chain of cause-and-effect.

<div class="mermaid">
graph TD
	subgraph c[Coach's View]
  	cE[Employee lacks experience] ==>
		cP[Employee causes problems] ==>
		cM[Manager doesn't delegate] ==> cE
	end

	classDef default fill:#FFFFFF, stroke:#FFFFFF
	style c fill:#FFFFFF
</div>

In this example you can see that the employee's and manager's views are subsets of the coach's view. Seeing both the employee's and manager's point of view as subsets makes the coach's view more complex than the view of either the employee or the manager.

<div class="mermaid">
graph LR
	vE[Employee's view]		-.->S1[ ]
	vM[Manager's view]		--> S2[ ]
	vC[Coach's view]	==> S3[ ]

	E[Employee lacks experience] ==>
	P[Employee causes problems] ==>
	M[Manager doesn't delegate] ==> E
	M -.-> E -.-> P
	E --> P --> M
	
	classDef default fill:#FFFFFF, stroke:#FFFFFF
	linkStyle default interpolate basis
</div>

A tool to support thinking at this stage is a [causal loop diagram](https://en.wikipedia.org/wiki/Causal_loop_diagram). These diagrams can show the positive or negative influence of each factor: delegation increases competence, which reduces problems. The fewer problems occur, the more comfortable delegation is, and conversely the more problems occur, the more uncomfortable delegation is. These three variables--delegation, competence, and problems--are interdependent.

<div class="mermaid">
graph TD
	D[Delegation] =="+"==>
	C[Competence] =="-"==>
	P[Problems]		=="-"==> D

	classDef default fill:#FFFFFF, stroke:#FFFFFF
	linkStyle default interpolate basis
</div>

This cause-effect cycle illustrates the consequences of a reinforcing feedback loop:

* Decreasing delegation reduces competence which increases problems which in turn reduces delegation--a *vicious circle*.
* Conversely, increasing delegation increases competence which decreases problems which in turn increases delegation--a *virtuous circle*.

![Calvin and Hobbes by Bill Watterson for August 29, 1988](https://assets.amuniversal.com/c3548f40dec20131719a005056a9545d)

You can see examples of reinforcing feedback loops causing vicious circles in animal behavior, organizational behevior, and international relationships:

* A stampede is an example of a vicious circle.
* In an organization that exerts command and control, reinforcing feedback loops can exist in dominance and submission between people in unequal categories. Dominant behavior encourages submissive behavior which in turn encourages more dominant behavior. 
* This can also occur in competitive relationships between rivals in equal categories, for example the vicious circle of the Cold War arms race, when increasing the US arsenal justified increasing the arsenal of the USSR, which in turn justified increasing the US arsenal even more.[^12]

<div class="mermaid">
graph TD
	subgraph c[ ]
		A[US amasses<br>nuclear<br>weapons] =="+"==>
		R[USSR<br>amasses<br>nuclear<br>weapons] =="+"==> A
	end

	subgraph b[ ]
		D[Dominant<br>Behavior] =="+"==>
		S[Submissive<br>Behavior] =="+"==>  D
	end
	
	subgraph a[ ]
		N[Number of<br>Sheep Running] =="+"==>
		P[Overall Level<br>of Panic] =="+"==>  N
	end
	
	classDef default fill:#FFFFFF, stroke:#FFFFFF
	linkStyle default interpolate basis
	style a fill:#FFFFFF, stroke:#FFFFFF
	style b fill:#FFFFFF, stroke:#FFFFFF
	style c fill:#FFFFFF, stroke:#FFFFFF
</div>

Various colloquial sayings illustrate the experience of reinforcing feedback loops, whether it is a vicious circle or a virtuous circle.

| Vicious Circle                                               | Virtuous Circle                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| "We're going to hell in a hand-basket."<br>"We're taking a bobsled ride down the chute."<br>"We're spiralling toward oblivion."<br>"Whe're shuffling the chairs on the Titanic." | "The sky's the limit."<br>"We're on a roll."<br>"This is our ticket to heaven." |

Once you see cause and effect as cyclical, you can shift away from solutions that require locating the source of the problem. A circle has no beginning or end. To solve the problem, find the place with the most "[leverage](http://donellameadows.org/archives/leverage-points-places-to-intervene-in-a-system/)" to change the cycle of cause and effect.[^13] As with a lever, a small force can result in a large effect if a reinforcing feedback loop is involved.

## Post-Logical Thinking

The view of the coach on the micromanagement trap between manager and employee illustrates the Catalyst stage, in which one is aware of context, of owning a perspective, and of patterns of behavior--and is tolerant of difference.[^14] An estimated 5% of managers profile at Catalyst.[^5] This is the first stage in a shift to a complex view of cyclical causes among interdependent variables in a system--a shift to post-logical thinking. Events and even logical arguments can be viewed in context, leading to more abstract discussions of "systems dynamics" and defining the boundaries of the system itself.[^3]

Systems consciousness increases at the next stage, Co-Creator, in which one is engaged in the complex interweave of relationships,[^15] participating with a perspective on system evolution, rather than solving or intervening.  An estimated 4% of managers profile at Co-Creator.[^5]

Thus the development of post-logical thinking (perhaps using some of these tools) offers hope for evolving our approach to foreign relations between nuclear powers, climatic systems, ecosystems, intelligent decision-making systems, etc.--and increasing humanity's probability of survival.

## Notes

[^1]: Bateson, N. (2011) _[An Ecology of Mind: A Daughter’s Portrait of Gregory Bateson](http://www.anecologyofmind.com/)_.
[^2]: Koplowitz, H. (1984) A Projection Beyond Piaget’s Formal-Operations Stage: A General System Stage And A Unitary Stage. In Armon, C.; Commons, M.L.; Richards, F. _Beyond Formal Operations: Late Adolescent and Adult Cognitive Development_; Praeger: New York; [ISBN 978-0-275-91139-3](https://isbn.nu/9780275911393).
[^3]: Koplowitz, H. (1987) Post-Logical Thinking. In _Thinking: The Second International Conference_; Perkins, D.N., Lochhead, J., Bishop, J.C., Eds.; 1st edition.; Routledge; [ISBN 0-89859-805-2](https://isbn.nu/0898598052).
[^4]: Petrie, N. (2014) _[Vertical Leadership Development–Part 1: Developing Leaders for a Complex World](https://14226776-c20f-46a2-bcd6-85cefe57153f.filesusr.com/ugd/a8b141_65db299b1e274cdc84e3de48016b9862.pdf)_; Center for Creative Leadership.
[^5]: Joiner, W.B.; Josephs, S.A. (2006) Leadership Agility: Five Levels of Mastery for Anticipating and Initiating Change; 1st edition.; Jossey-Bass: San Francisco; [ISBN 978-0-7879-7913-3](https://isbn.nu/9780787979133).
[^6]: "Enthusiast" and "Operator" are called "Implusive" and "Opportunist", respectively, in Cook-Greuter, S.R. (2013) [Nine Levels Of Increasing Embrace In Ego Development: A Full-Spectrum Theory Of Vertical Growth And Meaning Making](http://www.cook-greuter.com/Cook-Greuter%209%20levels%20paper%20new%201.1'14%2097p%5B1%5D.pdf). *Prepublication version*, 97.
[^7]: "Operator" is called "Opportunist" in Torbert, W.R. (n.d.) [The Seven Levels of Leadership Development and Their Impact](https://www.gla.global/the-glp/levels-of-leadership-development/).
[^8]: Numbers are for "Conformist" in Cook-Greuter, S.R. (2013) [Nine Levels Of Increasing Embrace In Ego Development: A Full-Spectrum Theory Of Vertical Growth And Meaning Making](http://www.cook-greuter.com/Cook-Greuter%209%20levels%20paper%20new%201.1'14%2097p%5B1%5D.pdf). *Prepublication version*, 97.
[^9]: See "Diplomat" description in Torbert, W.R. (n.d.) [The Seven Levels of Leadership Development and Their Impact](https://www.gla.global/the-glp/levels-of-leadership-development/).
[^10]: William R. Torbert and Elaine Herdman Barker (n.d.). The Global Leadership Profile: Action-Logic Descriptions for Coaches.
[^11]: Kerth, N.L. (2001) _Project Retrospectives: A Handbook for Team Reviews_; Dorset House: New York; [ISBN 978-0-932633-44-6](https://isbn.nu/9780932633446).
[^12]: Gregory Bateson called the second two examples "complementary schismogenesis" and "symmetrical schismogenesis," respectively, in Bateson, G. (1972) _Steps to an Ecology of Mind: Collected Essays in Anthropology, Psychiatry, Evolution, and Epistemology_; 1 edition.; University of Chicago Press: Chicago; [ISBN 978-0-226-03905-3](https://isbn.nu/9780226039053).
[^13]: See Meadows, D. (1999) [Leverage Points: Places to Intervene in a System](http://donellameadows.org/archives/leverage-points-places-to-intervene-in-a-system/). *The Academy for Systems Change*.
[^14]: See "Redefining" description in Torbert, W.R. (n.d.) [The Seven Levels of Leadership Development and Their Impact](https://www.gla.global/the-glp/levels-of-leadership-development/).
[^15]: See "Transforming" description in Torbert, W.R. (n.d.) [The Seven Levels of Leadership Development and Their Impact](https://www.gla.global/the-glp/levels-of-leadership-development/).

