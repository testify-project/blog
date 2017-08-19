---
layout: post
title: Ctrl-Alt-Delete Your QA Team
feature-img: "img/cover_black_white.png"
---

There isn’t a nice way to say this, but having a dedicated software QA team is a waste of time, energy and money. This is especially true if your QA team is comprised of non-engineers. I am not trying to be facetious or provocative, I am saying this having witnessed ineffective QA teams in action at organizations of various sizes. These experiences left me questioning the purpose of having a QA team. Sure, we’ve all learned from various teachers, peers, textbooks, consultants and speakers that the purpose of having a QA team is "to catch and prevent software defects before a product or service is delivered to clients," but is this really true?

There isn't a lot of research in the area of software testing. The most recent is [The Economic Impacts of Inadequate Infrastructure for Software Testing][nist-report] report published by *National Institute of Standards and Technology (NIST)* in 2002. In its report, NIST said nothing about having a separate QA team being advantageous. It did, however, say there is a need to test our software and improve our testing infrastructure. The NIST also made the following observation:

> All developers of financial services software agreed that an improved system for testing was needed. They said that an improved system would be able to track a bug back to the point where it was introduced and then determine how that bug influenced the rest of the production process. Their ideal testing infrastructure would consist of close to real time testing where testers could remedy problems that emerge right away rather than waiting until a product is fully assembled. The major benefits developers cited from an improved infrastructure were direct cost reduction in the development process and a decrease in post-purchase customer support. An additional benefit that respondents thought would emerge from an improved testing infrastructure is increased confidence in the quality of the product they produce and ship. The major selling characteristic of the products they create is the certainty that that product will accomplish a particular task. Because of the real time nature of their products, the reputation loss can be great (p. 21).

It’s pretty hard to argue with a real-time testing infrastructure being ideal. But, it’s also hard to argue that having a separate QA team helps us realize this ideal. In fact, having separate engineering and QA teams creates an [accountability gap][accountability-gap] and turns quality assurance into something aspirational rather than a commitment that must be met.

Good engineers take pride in writing quality code and believe it’s their responsibility to ensure code they deliver meets requirements and is well tested. Good QA testers equally take pride in applying counterfactual thinking to discover and report as many bugs as possible. Of course engineers and QA testers don't always catch bugs prior to the software being released. Given limited resources and time, it’s quite impossible to catch all bugs prior to release. However, someone has to be accountable for quality.

So who is responsible for quality assurance when things don't go as planned? The engineers? The QA testers? Or both? If the engineers are responsible for quality assurance, then why do we need a separate QA team? Why not directly assign quality assurance to the engineering team? If the QA team is responsible for quality assurance, does that absolve the engineers who acutely write the code from producing quality workmanship? If both the engineering and QA team are responsible for quality assurance, which team do you then hold accountable for quality issues? I would hope it’s the engineering team as they produce the software in the first place.

The late statistical quality control guru [Harold F. Dodge][harold-dodge] once said "you can't inspect quality into a product." Inspecting software to spot bugs before a client sees them is a path to failure. If the process that produced the software is bad, the process needs to improve. So how do we improve the process? For starters, provide [clean coding][clean-coding] and [secure coding][secure-coding] training for your engineers. Next, provide [guidelines][semantic-testing], [testing tools][testify-project] and infrastructure to effectively test their code.

It's comforting to have a QA team validating the work of engineers. Experience, however, shows that QA teams are rarely involved in the software development decision-making process and require guidance from the engineering team with respect to understanding the product, new  features and how to test them. This sort of arrangement is neither equitable nor sustainable as the industry shifts towards continuous integration and continuous delivery (CICD). Why encumber your engineering team with additional level of indirect responsibility? Or put your QA team in a constant position of playing catchup? Let the engineering team own quality assurance and hold it accountable for the quality of their workmanship.

[nist-report]: https://www.nist.gov/sites/default/files/documents/director/planning/report02-3.pdf
[accountability-gap]: https://www.partnersinleadership.com/insights-publications/the-accountability-gap
[harold-dodge]: https://en.wikipedia.org/wiki/Harold_F._Dodge
[clean-coding]: https://cleancoders.com/
[secure-coding]: https://www.securecoding.cert.org/confluence/display/seccode/SEI+CERT+Coding+Standards[semantic-testing]: https://semantictesting.org
[semantic-testing]: https://semantictesting.org
[testify-project]: https://testifyproject.org
