protocols
=========

This repo collects and maintains standardized wet-lab protocols used in natural product (drug) discovery. 

These protocols are collected in the scope of the [NPs4NPs initiative](https://github.com/nps4nps).


Contents
-----------------
- [Overview](#overview)
- [How to Contribute](#how-to-contribute)
- [Limitations](#limitations)
- [Attribution](#attribution)
- [For Developers](#for-developers)

## Overview

Protocols are essential for reproducible research. 
Yet, protocols do not exist independent of research, warranting iterative improvements and amendments leading to new versions of the protocol. 
Traditional documentation formats such as research articles or lab journals are poorly suited to represent such iterative improvements due to their lack of in-built version control and attribution mechanisms.
These limitations become even more pronounced when multiple research groups want to coordinate on specific procedures.

To address these issues, members of the [NPs4NPs initiative](https://github.com/nps4nps) have begun to track their natural product research protocols within this GitHub repository.
Inspired by software engineering, protocols are version-controlled, changes are registered and reviewed, and credit can be given in a fine-grained manner.
Importantly, each version of each protocol can be accessed via an URL and shared freely. 
Additionally, webhooks to Zenodo allow automated archiving and also provide a mechanism to register a permanent DOI (digital object identifier).

We are particularly interested in covering the natural product (drug) discovery workflow with a set of generally applicable, standardized protocols.
Such a set of protocols would

- Improve comparability of research results between laboratories
- Facilitate the exchange of materials and personnel
- Increase research quality with a set of validated and established protocols

If you want to print the protocols or convert them to PDFs, you can do this with several [online tools](https://print.markdown.janqi.com/).

## How to Contribute

### New protocols

We welcome the addition of new protocols, provided that they:

- Are related to the natural product (drug) discovery workflow
- Are sufficiently different from protocols already present in this repository
- Are practically used in your own work or are derived from published literature (but not verbatim copies)

If your protocol is within these constraints, we are very happy to receive your request in form of an **Issue**.

#### Formatting and naming

Please follow the structure of the [protocol template](template_protocol.md) when preparing your protocol.

The protocol should be formatted in `markdown`.

Please name your protocol following the convention `your-awesome-protocol-YYMMDD.md`

### Existing protocols

To change one of the existing protocols, discuss first with one of the maintainers. 
After approval, a pull request with the proposed changes can be opened.

## Limitations

- Individual protocols do not receive a DOI. If you are in need of one, feel free to deposit your protocol on [protocols.io](https://www.protocols.io/)
- Protocols are limited to use cases in natural product (drug) discovery and related fields.

## Attribution

### License

Protocols should specify their own license terms. This can also encompass a reference to an article (e.g. often the case with cultivation media.)
In case no license terms have been specified, we use the [MIT License](licenses/MIT) as our fallback license.

## For Developers

### Introducing changes

To ensure persistent URLs, this repository employs releases with semantic versioning.
The following workflow guides you through the update procedure.

1. Create a new branch and make your changes. 
2. Update the [CHANGELOG file](CHANGELOG.md), increasing by minor version only.
3. Create a pull request and request a review by one of the maintainers.
4. Once the pull request has been approved, merge it into the main branch.
5. Add your name to the CITATION.cff file.
6. Create a new release. This will automatically update the corresponding Zenodo repository.