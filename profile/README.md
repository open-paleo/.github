# Open Paleo

A community-maintained, version-controlled phylogenetic dataset for paleontology.

Open Paleo builds a structured, machine-readable dataset of paleontological taxonomy — rooted at **Life** and broad enough to accommodate any fossil taxon. All data is backed by published scientific literature, reviewed by maintainers, and validated by automated tooling.

Browse the dataset at **[open-paleo.org](https://open-paleo.org)**: a page for every genus, clade, rock unit, geologic stage and period, and cited work, an interactive tree, a world map, a glossary, and full-text search.

## Repositories

| Repository | Description |
|------------|-------------|
| [**corpus**](https://github.com/open-paleo/corpus) | Tools to build your own searchable library of the papers the dataset cites — fetching open-access PDFs, converting them to Markdown, full-text search, and a browser view of each paper beside its PDF. Ships code only, no papers |
| [**data**](https://github.com/open-paleo/data) | The dataset — genus and clade files, phylogenetic tree, build scripts, and output files (JSON, YAML, Newick, NEXUS, BibTeX) |
| [**glossary**](https://github.com/open-paleo/glossary) | Plain-English definitions of the anatomy, naming, family-tree and geology terms used in paleontology — one YAML file per term, built into JSON with a schema and TypeScript types. The website links these terms in its text to their definitions |
| [**media**](https://github.com/open-paleo/media) | Images for the dataset, for now outlines of genera and clades: one SVG and one YAML record per outline, naming the taxon it was drawn from, its creator, its source and its license, built into JSON with a schema and TypeScript types. The website shows them on genus and clade pages, each with its credit line |
| [**tools**](https://github.com/open-paleo/tools) | The tools built for the project, each its own package with its own version, changelog and license: the tree extractor, which reads phylogenetic trees from figure images into Newick and Nexus, and the outline tracer, which traces skeletal reconstructions into outlines for the media repository. You can use both on the website's [Tools](https://open-paleo.org/tools/) page |
| [**web**](https://github.com/open-paleo/web) | The website at [open-paleo.org](https://open-paleo.org) — a static site generated from the dataset's output, the glossary and the media, with a page for every genus, clade, rock unit, geologic stage and period, and cited work, plus the classification as an interactive tree, a world map, the glossary, and full-text search. Rebuilt whenever the dataset, glossary or media changes |

## Contributing

We welcome contributions from paleontologists, enthusiasts, and anyone interested in open science. To contribute, open a pull request in the [data repository](https://github.com/open-paleo/data) that edits its YAML files directly; [CONTRIBUTING.md](https://github.com/open-paleo/data/blob/main/CONTRIBUTING.md) sets out the standards a change must meet. To report a value that does not match the published literature, use the [Report an error](https://github.com/open-paleo/data/issues/new?template=correction.yml) form; for anything else, [open an issue](https://github.com/open-paleo/data/issues/new).

No institutional affiliation or special tools required — just a GitHub account and a published reference.

## License

Data and written content, such as the dataset and the glossary, are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): you are free to share and adapt them for any purpose, including commercial use, as long as you provide appropriate attribution. Each image in the media repository keeps the license it came with, recorded beside it. Code is licensed under the MIT License, except the outline tracer, which includes potrace and so is licensed under the GPL (version 2 or later). Each repository's LICENSE file gives its exact terms.
