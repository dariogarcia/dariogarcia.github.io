---
layout: post
title: A new Platform for Science & Research
date: 2021-12-14 00:00:00 +0300
description: The process by which research gets published is severely flawed. The whole system is based on old principles, and obsolete in the face of new technology. We identify those problems, their solutions, and propose a new platform for science to organize it.
img: research.jpg 
tags: [Science, Research, Organization]
---

We propose a new structure for scientific reviewing, publication and dissemination. To do so, we first identify the main problems in how research works today.

### Scientific Issues:

A significant part of today's scientific research (particularly the one originating at public institutions) is driven by the need to publish. The value of a researcher is determined by the yearly number of scientific papers written, by the reputation of the journals or conferences where those papers are published, and by the number of researchers that reference (i.e., cite) those publications in their own work. The first factor values quantity, not quality. The second rewards elitism, and puts lots of power on the hands of a few editors. The third is a measure of scientific relevance, but not of scientific quality. This far from perfect ecosystem has caused systemic problems in science. Such as:

* Opaque Evaluation: Current paper evaluations (i.e., journal/conference reviews) are rarely published, removing all responsibility and accountability from anonymous reviewers. This may lead to subjective, or plain arbitrary reviews, which in turn result in unfair decisions. Once a paper is published, readers are unaware of the issues found by evaluators, and have a harder time at identifying the limitations of published research.

* Unsuited Evaluation: Current evaluation is made by a few volunteers who may not be experts on the topic. These reviewers are forced to decide on the value of some piece of research without being fully aware of the state-of-the-art or its overall context.

* Unrewarded Evaluation: While having one of the most complicated and relevant roles in the scientific cycle, good reviewers (e.g., thorough, detailed, well-argued) are not rewarded. Additionally, posterior readers will not be able to benefit from their work due to opaque evaluation. Nonetheless, the first step in any scientific career is, or should be, reading and criticizing lots of papers to properly understand the current state-of-the-art, as well as the contents and structure of a good paper.

* Lack of Replicability: Replicability is not a must for most publications, and papers which try to replicate other's work are not favored for publication. However, replicability is an essential part of consistent research, and should be actively encouraged.

* Urge for Publication and Abandoned Research: Scientists are forced to publish several papers per year, regardless of their actual relevance. This favors short-lived research and the abandonment of challenging topics. The lack of consistent research makes it harder for science to reach the public.

* Scientific Paper Visibility is Unscientific: Papers visibility is directly affected by the impact factor of the journal or conference where it is published. Popular papers appear higher on search engines which results in a rich get richer process that impoverishes science. Journal/Conference impact factors supposedly determine their relevance, and consequently the visibility of published papers. However, impact factors are not a well-defined score, and are linked to a given journal/conference, not to the papers themselves. As such, it is useless for evaluating paper quality. At the same time, impact factors are used by institutions to evaluate the contributions of researchers. This leads researchers to pursue publications of those venues instead of producing quality research.

* Scientific Authorship & Contribution: Papers today may have from one author, to dozens of them. This dilutes the relevance of each researcher with regard to their own work, and complicates the task of attribution. It is often the case that one or more authors have not read the paper they sign, owning the right to authorship by rank or reputation.

* Limited State-of-the-art: Researchers are responsible for contextualizing their work on previous research, understanding the context and implications of their work. As the number of research works grows, it quickly becomes unfeasible to find, read and integrate every related work. 

Ok, so these are the problem. Seem like a lot. Let's see if we can find a few solutions.

### Solutions

* Transparent Evaluation: Evaluation of papers should be an open and continuous process. Readers should be aware of the criticisms, as well as the expertise of critics. Unsigned reviews should remain a possibility to foster free criticism, but that ought not to be the only way. Reviews should be reviewed, and reviewers should be accountable for their input.

* Idoneous Evaluation: For every research contribution there is a community, large or small, with the most knowledge on the topic. That is the community of researchers also working on the same area. These researchers will typically read and assess the relevance of papers in their field when working on their own research. This means the reading effort is already being done by the experts in the field, just not publicly. These experts on the topic are the best possible reviewers of a work, as they are selfishly interested in understanding every aspect of their related work.


* Recognized Reviewers: Writing good reviews takes time and effort, but their benefits are huge for science. Good reviewers (e.g., thorough, detailed, well-argued) should be acknowledged by the community, and should get proper recognition and reward.

* Replicability by Default: Contributions which cannot be replicated are of no relevance. Authors should be encouraged to facilitate the replicability of their work. Contributions replicating the work of others should also get proper recognition. The importance and visibility of papers should be directly related to their replicability.

* Perpetual evaluation: Research should be continuously under review. As a result of other people's contributions, research should be improved and extended. Authors should be encouraged to take into account and apply comments or findings made by the community. This would result in more complete contributions which would remain relevant for longer periods.

* Objective Paper Visibility: Paper visibility should be based on aspects like overall evaluation, citations, replicability, continued interest, and others. Research should be characterized and ranked by any combination of these factors.

* Explicit Author Contribution: Papers should have a limited set of contribution types. For example, original concept (the happy idea needed in many steps of the research project), design & refinement (the continuous planning and reconsideration of research) and implementation (conducting experiments, transforming ideas into reality).

* State-of-the-art Expansion: The creation of the state-of-the-art part of a paper could be done collaboratively. Authors of other works, or conocieurs of other research papers could enhance a new paper by contextualizing it beyond their original authors knowledge. This would provide a much richer background to papers, as well as identify potential side effects, applications and flaws of a research contribution.

### A New Platform for Research

The previously proposed solution is hard to implement in today's regime of private publishers and corporative venues. To implement all proposed solutions, we propose a new platform for research. In this system, there are two main types of contributions, original and enhancing ones. Additionally, there's authors, who can be attributed with either type of contributions.

#### A few constants

* Author commitment rate (ACR) in the order of 10.
* Minimum open time (MOT) in the order of 1 year

#### Original Research Contributions (ORC)

An ORC is one which can be differenciated from the state of the art by itself. A work producing it's own hypothesis. 

Each ORC has a reliabilty and relevance score, which are initialized to a basic value when the contribution is first made public. The basic reliability and relevance comes from the ORC authors', as a commitment to the work. This is returned to their correponding owners as the ORC gains it's own reliability (reviews, replications and reproductions) and relevance (citations, dissemination) from other sources. 
Good reviews by confident and expert authors will increase the ORC reliability, up to a certain threshold. To get beyond that an ORC needs to be replicated and/or reproduced at least once by a public and non-conflicting author. 
Citations to the ORC from reliable and relevant papers provide relevance, as well as liked dissemination works linked to the ORC.
* Relevance and reliability gain follows a sigmoid, starting slow, peak gradient at the middle, and asymptoting to a maximum.
* Initial reliability/relevance of an ORC: Each author of the ORC must commit 1/ACR of it's own reliability/relevance to the ORC. If one or more authors do not have enough uncommited reliability/relevance, the ORC cannot be made public.

An ORC has set of authors, public or private, each with a percentual contribution to the work. This is added individually to the platform, iterating until unanymous agreement. Reliability and relevance produced by the ORC is split among authors accordingly.

An ORC can be open or closed. When submitted, it is open, and it will remain so for MOT time. Beyond that point, the ORC authors can decide to close it at any time. When closed, an ORC can no longer recieve reviews, and can no longer be modified. Instead, it can receive commentary regarding its historical perspective. Once closed it cannot be reopened. 

#### Enhancing Research Contributions

Enhancing research contributions are those that are built to support, complement or extend other contributions. Free of purpose in itself, beyond that of improving another contribution. There are several types of enhancing contributions: Reviews, 

##### Reviews 

Each review is associated with an ORC. It can have one or more authors, public or private. In either case, the platform validate and publishes potential conflicts. Having a conflict is not forbidden for review authors, but it must be clearly declared and disclosed. A review has the overall ORC score (1-5), a self-assessed expertisee and confidence, and the reliability of the authors.

* Review scores are
  * 1, full reconsideration: The ORC has fundamental flaws and no contribution. Not worth fixing. Suggested withdrawl. Review must refute the contributions argued in the ORC, and identify a list of major problems.
  * 2, major changes needed: While there is an original contribution, the ORC has major flaws. These need to be addressed before the work can be allowed to have its own relevance and reliability. Review must clearly indicate the strong points and most relevant weak points of the ORC. 
  * 3, minor changes needed: The contribution is clear, and can be properly presented with changes in a few areas. The ORC is relevant and reliable. Review must contain a summary of the contribution, and a list of minor changes to apply.
  * 4, improvements possible: The ORC is a solid piece of science that has no relevant flaws and is highly relevant. A few improvements are possible. The review must list those, together with an argumentation on the strong points of the ORC.
  * 5, outstanding: Flawless and extremly relevant. Short summary of the main contributions.

Published reviews can be upvoted by the community, and even recommended them for integration into the ORC. Either of those cases provides relevance to the authors of the review. Reviews with scores of 2, 3 and 4 can also include a list of changes on the ORC, addressing the points identified in the same review.

Popular reviews which include a list of changes, can be requested for integration. This can only be authorized by the original authors of the ORC. When this is the case, the work is coordinated, authorships to the ORC are added as well as the corresponding percentatges. Reliability and relevance scores are recomputed, becoming larger because of the inherited relevance and confidence from the integrated review, but also splitting among more, since the number of authors is increased.


* Meta-reviews:
  * These are associated to a review, a sota expansion or a summarization and dissemination. Include a score of either "disagree", "lacks relevance", and "relevant & agree". Limited to a single author.
  * Have a minimum size, proportional to the size of the review.
  * Metareviews contribute with minimal reliability to metareview author.
  * Can be up/down voted
* Replication/Reproduction of original research
  * Must come together with code and data
  * Enough replications/reproductions make the relevance of an original work definitive.
* Dissemination
  * Works that make accessible the content of an original review
  * Have a score of relevance from the community.
  * Can be approved or disapproved by the authors of the original contribution
  * Relevance works as with reviews

Each of these contributions has an associated author. Although public anonymity is optional and recommended, this would be unveiled if a red flag is raised on their work (e.g., false authorship of a contribution, prevaricating reviews, false replication report, plagiarism in reviews/summaries/dissemination produced).

#### Authors

* Authors have a reliability, relevance, and a list of authored contributions.

public/private authors

conflicting authors

right to flag. 

reliability can be commited
limiting the number of concurrent ORCs from the same author. 

* The initial reliability and relevance is zero. At first, reliability can be gained by doing enhancing contributions. Relevance is gained with citations.

* When doing original contributions, author's must donate a fixed fraction of their gained reliability, which is eventually returned with the addition of enhancing contributions that increase the work's reliability.

* If an author has no fraction left of its reliability, no original contributions can be made. Reliability can always be gained though enhancing contributions. 

* Authors are encouraged to evaluate and take into account the enhancing contributions to their work, using it to improve their own research. Updated versions of original contributions can be made in collaboration with the enhancing contribution author's, and increase the relevance and reliability of the original work, based on the community interest in the enhancing contribution. 

* Authors can request reviews of their work to specific users. Typically, those involved in the same field, or being cited by the original work.

* Authors gain additional relevance by doing enhancing contributions on those original ones citing them.

#### Moderators

Each year, authors with relevance and reliability are invited for moderation. This means resolving disputes, as authors from the platform request the attention of a moderator (e.g., offensive content, paper rebutals, plagiarism claims). All such disputes, together with any actions taken, get logged for accountability.

### Ethical considerations

Should the system enforce the use of ethical reviews and enviromental assesments in ORCs?

Is the system resistant to manipulation, power concentration and abuse?

### The case of Artificial Intelligence

AI has a set of particularities that deserve to be discussed separately. For research done in this area, we must consider into account issues like model bias (particulary in machine learning). At the moment, there is no incentive for analyzing, rating and reinforcing or deleting bias from trained and released models. As a result, the majority of released models are not safe to use in practice, a feature that is also inherited by all models build on top (a very popular practice known as transfer learning).

In order to make the cost of bias worthwhile, we need to demand it and reward it. This must involve all actors involved in research:

* Funding agencies should include non-optional debiasing requirements on all calls made public.
* Research institutions which target AI models should include structural units focused on bias, to ensure no dangerously biased models or research is released.
* Publication venues and/or reviewers should demand debiasing proof and effort on all relevant research. Failing yo comply should entail desk reject.


### References

[Kriegeskorte, Nikolaus, Alexander Walther, and Diana Deca. "An emerging consensus for open evaluation: 18 visions for the future of scientific publishing." Frontiers in computational neuroscience 6 (2012).](http://journal.frontiersin.org/article/10.3389/fncom.2012.00094/full)
