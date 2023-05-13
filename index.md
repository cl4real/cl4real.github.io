---
layout: default
---

# Call for papers

Current supervised machine learning approaches have shown extraordinary
capabilities in solving complex tasks, but the resulting models still lack the typical
human skill of being able to sequentially learn and remember how to perform
multiple tasks, or to deal with changing data distributions. Continual learning
approaches aim at tackling these limitations, by devising techniques that allow
models to retain or refresh the knowledge of previously-learned tasks, thus
preventing "catastrophic forgetting".

This family of approaches has recently attracted a lot of attention, but experimental
evaluations have been mostly limited to constrained and artificial scenarios (e.g.,
presence of hard boundaries between tasks; assumption that classes cannot
reappear in later tasks, lack of correlation between consecutive tasks, etc.). This can
undermine the applicability of continual learning to real-world problems: for example,
robotics would benefit from autonomous agents that are able to adapt to new terrains
while still being able to navigate on the ones they already know; in medicine, privacy
concerns may limit the availability of historical data, and domain shifts (e.g., imagery
acquired by new equipment or disease progress) would require that models be able
to process both data from the old distribution, now unavailable for training, and the
new one.

To tackle the challenges posed by such settings, common pitfalls and possible
amendments of the classical scenarios have to be investigated in the next few years.
Therefore, this workshop aims to promote and attract research on less studied
aspects of continual learning, from new benchmarks to evaluation protocols, thus
integrating the current methodological research efforts with a more practical and
application-oriented perspective.

The workshop aims to attract novel and original contributions exploring the
intersection of continual learning and real-world applications. Expected submissions
should cover, but are not limited to, the following topics:
* investigations and proposals of metrics to better qualify the performance of
continual learning approaches in the context of realistic problems;
* novel continual learning benchmarks that go beyond the classical settings,
focusing on one or more key aspects that characterize applications;
* case studies of deployment and integration of continual learning approaches
to real-world problems;
* methodological contributions that focus on key aspects of realistic
applications.
