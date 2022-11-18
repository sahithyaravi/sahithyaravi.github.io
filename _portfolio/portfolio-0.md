---

title: "Multi-event commonsense in event coreference resolution"
excerpt: "Event coreference models cluster metions pertaining to the same real-world event.
Recent models rely on contextualized representations to recognize coreference among lexically or contextually similar mentions. However, models typically fail to leverage commonsense inferences, which is particularly limiting for resolving lexically-divergent mentions. We are working on a model that extends event mentions with temporal commonsense inferences. Given a complex sentence with multiple events, e.g.,“the man killed his wife and got arrested”, with the target event “arrested”, our model generates plausible events that happen before the target event – such as “the police arrived”, and after it, such as “he was sentenced”. We generate such inferences by fine-tuning GPT-3 on limited human annotations. We show that incorporating such inferences into an existing event coreference model improves its performance, and we analyze the coreferences in
which such temporal knowledge is required."
collection: portfolio
---

