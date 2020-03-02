---
permalink: /
---

# ADPT Document Schema

This repository holds all the JSON schemas related to the <a
href="https://espositoandrea.github.io/adpt.github.io"><abbr title="AsciiDoc
Publishing Toolbox">ADPT</abbr></a> project. Every schema is accessible in this
website.

## The available schemas

Here is a list of the defined schemas. The main one is "Document": this contains
the definition of a document that can be managed using ADPT. All the other
schemas are used by the Document as references. This separation is used to
improve the readability of the main schema and to apply the principle of <a
href="https://en.wikipedia.org/wiki/Separation_of_concerns" target="_blank"
rel="noopener noreferrer">Separation of Concerns</a>.

- [The "Document" schema](schemas/document.schema.json)
- [The "Author" schema](schemas/author.schema.json)
