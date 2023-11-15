---
title: "Distributed Systems Research"
date: 2023-11-08T09:02:09-08:00
author: Shayan Hosseini
draft: true
---

I recently finished my Master's at UBC. I applied to grad school in the winter
of 2019 aiming to do distributed systems research. At the time, I didn't have a
specific research problem in mind to work on. I mean I still don't have one
honestly, but at least I have a better idea about what I want to do. 

Anyway, I ended up at UBC working with Ivan. In the first meeting Ivan asked me
if you have an idea you can start working on that, otherwise, you can join one
of my ongoing projects. I joined the PGo project, because it was kind of
interesting and I felt it's a better fit for me compared to the rest of the
projects. PGo is a project in the intersection of distributed systems and formal
verification. Also, I was like it's an opportuinity for me to learn. I didn't
have the chance to do distributed systems research during my undergrad. No one
in my undergrad school did research in this area and the internship I did at Max
Planck was on the theory side of the things, plus it was short.

PGo has a wide scope including formal modeling, compiler design, distributed
transaction processing, and systems optimization. I worked on systems-side of
PGo from January 2021, when I started my MSc, to October 2022 when I was
polishing the last bits for ASPLOS artifact evaluation. Earlier around December
2021 we had submitted PGo to OSDI 2022, but we got rejected. Starting 2022 from
January 2022 till April I was mostly busy with coursework. From May to July I
worked on improving our evaluation and in July we submitted to ASPLOS and this
time it got accepted.

I spent the summer of 2022 at Microsoft Research working on datacenter
networking. It wasn't my field exactly, but I took the opportuinity to go there,
explore and learn. I got an optimization problem to solve. From all the
approaches out there, we decided to use reinforcement learning, because we
thought the problem is too hard for other optimization techniques. Also, I'm not
an optimization person. But also the state space of the problem was too big for
RL to do anything meaninful. Anyway, it wasn't a successful project, but I read
some networking papers and learned basics of RL.

Back to UBC again, in November I ambiously decided to start working on a new
proejct. The ideas around PGo were all on the verification or PL side of the
project, but I wanted to work on core distributed systems problem. Ivan
suggested an interesting idea to build an abstraction based on the promises in
the first round of Paxos. There are some similarities in these promises, leases,
and the notion of locking in the PBFT-like protocol. More on this in a blog post
later. 

Starting working on this promises project, I realized I missed out many
essential papers on distirbuted systems, mostly around consensus. I had read
some in the grad distirbuted systems course I had before, plus, the ones I
mostly skimmed through and just saw the presentation in the conferences. During
this time I realized designing distributed protocols is super fun and
appreciated TLA+ power once again. However, I had to abandon the promise project
because we couldn't get anything publishable out of it. The closest idea we had
was already published at NSDI a couple of year back. Another unsuccessful
project after the one at Microsoft Research.

I wrote my thesis on the stuff that I did around PGo, which is cool and you
should check it out. What I realized is that I'm interested in distributed
consensus. I still don't have a problem to work on but there are a ton of things
to learn. At this point I'm not pursuing a PhD or don't infinite funds to learn
and read full-time. However, I want to pursue my interest in distributed
consensus. Sooo, I'll be reading some essential papers in this area and will be
writing about them here too. Stay tuned!

https://shayanh.notion.site/Readings-in-Distributed-Consensus-7429bc2274694e8e92f1dfe999a03182?pvs=4
