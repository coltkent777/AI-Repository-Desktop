# AI Art Framework Repository

> **Purpose**
>
> This repository is the single source of truth for all approved
> artwork, campaigns, characters, locations, items, logos, and framework
> rules.
>
> Its purpose is to preserve artistic consistency, campaign continuity,
> and creative intent so that future AI-generated artwork remains
> faithful to the approved vision without requiring the user to
> repeatedly describe established information.

------------------------------------------------------------------------

# Repository Philosophy

Every piece of approved information has **one canonical home**.

The repository stores **reusable knowledge, not reusable prompts**.

When artwork is requested, ChatGPT is responsible for assembling a
complete image-generation prompt from the approved repository
information. The user should never need to manually combine information
from multiple files.

The goal of this repository is consistency first. Creativity should
always build upon approved information rather than replace it.

------------------------------------------------------------------------

# AI Design Principles

When using this repository, ChatGPT should always follow these
principles:

-   Consistency is more important than novelty.
-   Approved information always outweighs assumptions.
-   If multiple interpretations are possible, ask rather than guess.
-   Reuse approved design language whenever possible.
-   Build upon existing work instead of reinventing it.
-   Repository knowledge is persistent; the current user request defines
    only the scene being created.
-   Treat every approved document as part of a connected knowledge base.
-   Never contradict approved repository information.

------------------------------------------------------------------------

# Repository Structure

``` text
README.md                  ← Start Here

framework/
    README.md              ← Artistic philosophy and global framework rules

workflow/
    README.md              ← AI operating procedure and prompt assembly process

templates/
    *.md                   ← Reusable templates

campaigns/
    README.md              ← Campaign organization

campaigns/<Campaign>/
    Campaign-specific documents
```

------------------------------------------------------------------------

# Document Authority

When information exists in multiple places, resolve it in the following
order:

1.  Current User Request
2.  Campaign-specific Documents
3.  Framework Documentation
4.  Templates
5.  Repository Defaults

If approved documents conflict, stop and ask the user before proceeding.

------------------------------------------------------------------------

# Approval Policy

Nothing becomes permanent until explicitly approved.

**Workflow**

Draft

↓

Review

↓

Revision

↓

Approved

↓

Locked

Locked information must never be changed without explicit user approval.

------------------------------------------------------------------------

# AI Responsibilities

Before generating artwork, ChatGPT should:

1.  Read this README.
2.  Read the Framework README.
3.  Read the Workflow README.
4.  Read the Campaigns README.
5.  Read all referenced Character, Location, Item, and Logo documents.
6.  Ask clarifying questions if required information is missing.
7.  Assemble a complete image-generation prompt using approved
    repository information.
8.  Add only the scene-specific details supplied in the current request.
9.  Generate the final image.

**ChatGPT is responsible for assembling the final prompt submitted to
the image generator. The user is not expected to manually combine
repository information.**

------------------------------------------------------------------------

# Repository Rules

-   Never assume missing information.
-   Ask clarifying questions whenever needed.
-   Preserve approved information.
-   Maintain consistency across all artwork.
-   Follow the approved framework philosophy.
-   Campaign documents are the canonical source for campaign-specific
    information.
-   Respect locked documents.
-   Never overwrite approved content without explicit approval.

------------------------------------------------------------------------

# Navigation

After reading this document, continue in the following order:

1.  `framework/README.md`
2.  `workflow/README.md`
3.  `campaigns/README.md`
4.  The appropriate campaign folder and its documents.

Following this sequence ensures every image is generated using the
complete approved knowledge base.
