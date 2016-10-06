---
layout: post
title: Conditioning on a Collider
---

I'm trying to come up with a cute, terse way to illustrate the phenomenon of conditioning on a collider and I'm actually having a hard time summarizing it.  Mostly because I just read a rigorous paper discussing all the insiduous details of colliders, and I absolutely love rigor and details and want to tell you all about it!  But I'll suppress the urge.  This is the cliff notes version.  Enjoy.

Conditioning on a collider is a special case of selection bias, where the sample studied doesn't accurately reflect the makeup of the population that we wish to draw conclusions about.  The selection bias occurs because inclusion in the sample is determined based upon two (usually independent) factors. It's tough to conceptualize without an example so let's dive right in.

Admission to Princeton University is based upon a lot of factors, including grades, scores, recommendations, extracurriculars, and a  personal essay.  Let's roll up all these factors and just call them "high school record".  Obviously, the process is complicated and subjective, but let's just agree that the admission committee looks at each applicant's high school record and accepts the top 5% of students.  

Now suppose the Princeton Committee for Diversity & Inclusion surveys the student body and discovers a shocking paucity of left-handed, red-headed, hermaphrodites (henceforth referred to as LRHs) among the university community.  The Diversity Committee writes a strongly-worded letter to the Admissions Committee suggesting that they accept all LRH applicants going forward.  

Five years later, the first batch of LRH students graduates with the rest of their class. How do you think they fared academically at Princeton?

Now, I have no reason to believe that handed-ness, hair color, or hermaphrodite status has any correlation with academic performance or even intelligence in the general population.  But the LRH students aren't competing against the general population.  They are competiting against Princeton undergrads, most of whom were specifically chosen for their intelligence and past academic performance.  So I'd expect those LRH to do very, very badly at Princeton.

Let's recap what happened. Princeton obtained a sample of students, each of whom fulfilled at least one of two, independent critera: 1) outstanding high school record 2) LRH status.  Even though these criteria are independent in the general population, the way that the sample was chosen *induced a negative correlation between the two groups within the sample*.  And that's conditioning on a collider.
