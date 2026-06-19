## The Open Syndrome Initiative 👋

**Machine-readable case definitions for public health surveillance.**

Visit: https://opensyndrome.org/

Case definitions are the backbone of disease surveillance; they determine what counts as a case of flu, dengue, or any other public health threat.
Today, most live as PDFs or plain text, meaning every system that needs them must re-interpret them from scratch.
The **Open Syndrome Definition (OSD)** is an open JSON format that makes these definitions machine-readable, version-controlled, and interoperable.

Our paper was published in the *Journal of Medical Internet Research*:

> Ferreira et al. **The Open Syndrome Definition as a Machine-Readable Standard for Public Health.** *J Med Internet Res* 2026;28:e86249. https://doi.org/10.2196/86249

## What's in this organization

**Format & data**
- [`schema`](https://github.com/OpenSyndrome/schema) -- JSON schema and JSON-LD context
- [`definitions`](https://github.com/OpenSyndrome/definitions) -- the case definitions dataset

**Tooling**
- [`open-syndrome-python`](https://github.com/OpenSyndrome/open-syndrome-python) -- Python library to parse, validate, and work with OSD definitions
- [`open-syndrome-r`](https://github.com/OpenSyndrome/open-syndrome-r) -- R package with the same capabilities
- [`editor`](https://github.com/OpenSyndrome/editor) -- Friendly UI interface to convert from text to JSON and vice-versa

**Platform**
- [`website`](https://github.com/OpenSyndrome/website) -- source for [opensyndrome.org](https://opensyndrome.org), including the data browser and contribution workflow

## Explore

- **Website & data browser:** [opensyndrome.org](https://opensyndrome.org)
- **Dataset on Hugging Face:** [opensyndrome/case-definitions](https://huggingface.co/datasets/opensyndrome/case-definitions)
- **Schema docs:** [opensyndrome.org/how/documentation](https://opensyndrome.org/how/documentation)

## Contribute

Submit a new definition via the [web form](https://opensyndrome.org/how/) or open a pull request in [`definitions`](https://github.com/OpenSyndrome/definitions). All submissions go through automated schema validation and community review.

Questions? [opensyndrome@anapaulagomes.me](mailto:opensyndrome@anapaulagomes.me)

