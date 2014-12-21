---
layout: page
title: Query-by-Example Spoken Term Detection
group: main
---
{% include JB/setup %}

Download the thesis: [PDF](download/thesis_fapso.pdf)

Additional materials to my thesis, notes, source code of tools and relevant scripts.

## WFSTcn QbE system

Tools for FST composition and extracting detections are in the [FST repository](https://github.com/michalfapso/FST)

	git clone git@github.com:michalfapso/FST.git

### Scoring tool

The kws_scorer tool is included in the [Lattice Search Engine repository](https://bitbucket.org/michalfapso/lse). Please, follow the README.md in the repository to run the kws_scorer.

	git clone git@bitbucket.org:michalfapso/lse.git
	cd lse/LSE_2.x/kws_scorer
	make dist
	less scripts/score.sh
