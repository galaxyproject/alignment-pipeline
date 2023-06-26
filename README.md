# Enable whole genome alignments in Galaxy

Enable generation of multiple genome alignments in Galaxy.

## Phase I

- Develop a Galaxy workflow for generation of pairwise alignments between large genomes using lastz based on either UCSC pipeline logic and/or [`make_lastz_chains`](https://github.com/hillerlab/make_lastz_chains).
- Use Frontera system for lastz jobs

## Phase II

- Explore "drop-in" replacament with [segalign](https://github.com/gsneha26/SegAlign)
- Combine multiple pairiwse alignment into multiple alignments using [`multiz`](https://github.com/multiz/multiz)

## Phase III
- Port [CESAR2](https://github.com/hillerlab/CESAR2.0) and [TOGA](https://github.com/hillerlab/TOGA) into Galaxy
- Demonstrate direct interoperability between CEASAR output and HyPhy selection analyses


