# [DocOps](https://docops.info)<sup>🔗</sup>

DocOps describes the method of using human readable and editable plain text documentation as source for applying changes in another system. By keeping both parts in sync, the documentation becomes the single source of truth for both humans and computers

## Foundation

In the spirit of the DevOps movement the DocOps method combines human written documentation with it’s execution on the system it documents. Making human written documents executable just like an applications.

The majority of documentation artifacts and system state consist of content that rarely changes. Only small but important parts are changed regularly. This is the sweet spot where the DocOps concept provide a benefit by making sure that the regularly changed content is always up-to-date.
DocOps is in general the concept of having an executable documentation, or enrichment of documentation based on execution results.

## Principles

When applying the DocOps Method this principles will serve as guardrails.

- Documentation has a dual purpose.
- Documentation part for humans also make sense even without execution part in place.
- Documentation is single source of truth.
- DocOps Systems are idempotent multiple executions will produce the same result.
- DocOps System can be implemented one-way or round-trip.
- A system that only generates documentation from code isn’t following the DocOps concept.
- A system that modifies or enriches the documentation is within DocOps.

## Differentiation from other Methods

DocOps as described on the internet prior 2018, 2019 as Documentation with Dev Tools and Mindset.

### GitOps, ChatOps and DocOps

What is the differentiation to other potential similar concepts.

[TODO]

## Tools

As with all xyzOps concepts tools are the mortar that make bricks stick together.
As of now there aren’t any tools that are specifically designed

## Examples

[TODO]

## Best Practice

Example of good and bad DocOps practice:

**Scenario:**
Generate Reverse Proxy Config for HAProxy/Nginx from documentation. Provide markdown example. 

**Good Practice:**
Do ... [TODO]

**Bad Practice:**
Enriched documents should be up to date or the enriched content should be valid for a long period of time at least double the mean time between average document generation. 

## Alternatives Concepts

**Code too Docs**
An existing common practice is to enrich the existing documentation with code execution results. In this case the user is editing the config files and scripts and as an output of this the documentation is updated with predefined injection points.

## Contribution

Be part of the DocOps movement, as the concept and practice are still evolving there are many opportunities and possibilities to contribute and influence the direction. You don’t have to be a developer or alike to contribute. Everyone with a brain is welcome.

### Ideas

This is a short list of topic that are alway welcome and simple to accomplish.

- Promote the DocOps concept to your co-worker, friends, Blog posts and Social Media. Explain what it is and how it should work.
- Review the overall documentation, correct typos and wording to describe better the concept. Make the text more understandable to a wider audience.
- Translate the concept into you own language.
- Search for tools and examples that follow the DocOps principles and post about them. Let the creators know they are following the DocOps principles if don’t know it yet.

More to come in the future on https://DocOps.info
