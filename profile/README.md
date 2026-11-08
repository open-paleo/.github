# Open Paleo

A community-maintained, version-controlled phylogenetic dataset for paleontology.

Open Paleo builds a structured, machine-readable dataset of paleontological taxonomy — rooted at **Life** and broad enough to accommodate any fossil taxon. All data is backed by published scientific literature, reviewed by maintainers, and validated by automated tooling.

Browse the dataset at **[open-paleo.org](https://open-paleo.org)**: a page for every genus, clade and cited work, with full-text search.

## Repositories

| Repository | Description |
|------------|-------------|
| [**data**](https://github.com/open-paleo/data) | The dataset — genus and clade files, phylogenetic tree, build scripts, and output files (JSON, YAML, Newick, NEXUS, BibTeX) |
| [**web**](https://github.com/open-paleo/web) | The website at [open-paleo.org](https://open-paleo.org) — a static site generated from the dataset's output, with a page for every genus, clade and cited work, indexes, and full-text search. Rebuilt whenever the dataset changes |
| [**corpus**](https://github.com/open-paleo/corpus) | Tools to build your own searchable library of the papers the dataset cites — fetching open-access PDFs, converting them to Markdown, full-text search, and a browser view of each paper beside its PDF. Ships code only, no papers |

## Contributing

We welcome contributions from paleontologists, enthusiasts, and anyone interested in open science. To contribute, open a pull request in the [data repository](https://github.com/open-paleo/data) that edits its YAML files directly; [CONTRIBUTING.md](https://github.com/open-paleo/data/blob/main/CONTRIBUTING.md) sets out the standards a change must meet. To report an error or ask a question, [open an issue](https://github.com/open-paleo/data/issues/new).

No institutional affiliation or special tools required — just a GitHub account and a published reference.

## License

All data is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the data for any purpose, including commercial use, as long as you provide appropriate attribution. The corpus tools and the website's code are licensed under the MIT License ([corpus](https://github.com/open-paleo/corpus/blob/main/LICENSE), [web](https://github.com/open-paleo/web/blob/main/LICENSE)).
