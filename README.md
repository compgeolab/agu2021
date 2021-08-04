# Python-based workflows for small-to-medium sized data: what works, what doesn't, and what can be improved

Leonardo Uieda<sup>1</sup>,
Santiago Soler<sup>2,3</sup>

> <sup>1</sup>Department of Earth, Ocean and Ecological Sciences, School of Environmental Sciences, University of Liverpool, UK
> <br>
> <sup>2</sup> CONICET, Argentina
> <br>
> <sup>3</sup> Instituto Geofísico Sismológico Volponi, UNSJ, Argentina

This is an invited talk for the first part of this session, with 10 minute
talks featuring "demonstrations of open source software and technology tools,
and using open science data platforms" followed by a panel discussion.

| | Information |
|---:|:----|
| doi | [TBD](https://doi.org/TBD) |
| Abstract | ADD LINK AND ID |
| Session | [Open Science in Action: Data, Software, Access, Science](https://agu.confex.com/agu/fm21/prelim.cgi/Session/122142) |
| When | TBD |

## Abstract

For over a decade there has been a lot of attention devoted to "big data" and
the challenges that arise from it.
However, many scientists (ourselves included) still mostly deal with data of
small to medium size.
For the sake of this presentation, we will define this as "data that can fit in
the memory of a modest computer" (roughly the order of 10s of gigabytes in
2021).
Though perhaps not as exciting, there are still challenges to building
reproducible research pipelines for analysing and modelling data of this scale:

1. Binary data or files larger than a few 10s of megabytes are difficult to
   manage in version control systems, which are built for code (i.e., plain
   text).
1. Python tools tend to evolve at a fast pace, making analysis pipelines
   difficult to reuse and replicate without significant effort even one or two
   years later.
1. Jupyter notebooks are extraordinary for interactive exploration but still
   come at the sacrifice of collaborative development and workflow automation
   (though tools like [nbflow](https://github.com/jhamrick/nbflow/) and
   [jupytext](https://github.com/mwouts/jupytext) offer a glimpse of a better
   future).
1. Publicly available geophysical data and models are relatively common on the
   internet but often don't have open and permissive licenses or don't clearly
   indicate that they do.

In this presentation, we will demonstrate the workflow that we have been
establishing at the [Computer-Oriented Geoscience Lab](https://www.compgeolab.org/) 
for building
"[repro-packs](https://lorenabarba.com/blog/how-repro-packs-can-save-your-future-self/)"
for our papers and projects.
We use a combination of virtual environments, data download and caching tools,
notebooks, Makefiles, and data repositories to provide others with the means to
reproduce and build upon our work.
We will also share some of the unsolved challenges that we have encountered and
our dreams for an ideal workflow.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br>
This content is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution
4.0 International License</a>.
