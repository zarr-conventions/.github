# Zarr Adoption Conventions

**Feedback is very welcome on about this framework for Zarr Conventions. Please join the [discussion on V1 of the Zarr Conventions Framework](https://github.com/orgs/zarr-conventions/discussions/24).**

This organisation contains documentation and tooling to help define and share Zarr Adoption Conventions.

## What is a Zarr Adoption Convention?

A Zarr Adoption Convention (Zarr convention, for short) is simply a way of using Zarr to store data for a particular domain, application or purpose.
For example, a Zarr Convention can define a set of attributes for storing specific metadata that helps downstream applications provide special behaviour and users interpret the data.

## Define your own convention

To define and share your own convention:

1. [**Create a new GitHub repo** using the zarr-conventions template](https://github.com/new?template_name=template&template_owner=zarr-conventions)
1. **Create a UUID** to use as a globally-unique identifier for your convention. 
1. **Edit the README.md** in your repo to describe your usage convention for developers and users.
1. **Edit or remove the schema.json** file in your repo to define validation constraints on your metadata.
1. Commit your changes and **make a GitHub release** so you have a stable version of your spec and schema to point to.
1. **Share your convention** with the community (see below).

## Convention Maturity

We have adapted the maturity classification system used by the STAC ecosystem. There are many conventions being built with Zarr, but they have varying degrees of maturity. All community conventions
listed here included must include a maturity classification, so that Zarr conventions users can easily get a sense of how
much they can count on the convention. Currently, it's recommended that convention developers self-assess the maturity in their README. We may evolve to a more centralized maturity assignment process in the future.

| Maturity Classification | Min Impl # | Description                                                                                                                                                | Stability                                                                                                                                       |
| ----------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Proposal                | 0          | An idea put forward by a community member to gather feedback                                                                                               | Not stable - breaking changes almost guaranteed as implementers try out the idea.                                                               |
| Pilot                   | 1          | Idea is fleshed out, with examples and a JSON schema, and implemented in one or more libraries. Additional implementations encouraged to help give feedback | Approaching stability - breaking changes are not anticipated but can easily come from additional feedback.                                      |
| Candidate               | 3          | A number of implementers are using it and are standing behind it as a solid convention. User can generally count on an convention at this maturity level.    | Mostly stable, breaking changes require a new version and minor changes are unlikely. The convention has a code owner, designated in its README. |
| Stable                  | 6          | Highest current level of maturity. The community of convention maintainers commits to a STAC review process for any changes, which are not made lightly.    | Completely stable, all changes require a new version number and review process.                                                                 |
| Deprecated              | N/A        | A previous convention that has likely been superseded by a newer one or did not work out for some reason.                                                   | DO NOT USE, is not supported                                                                                                                    |

Maturity mostly comes through diverse implementations, so the minimum number of implementations
column is the main gating function for an convention to mature. But convention authors can also
choose to hold back the maturity advancement if they don't feel they are yet ready to commit to
the less breaking changes of the next level.

## Share your convention

If you have published a Zarr convention, please [add it to the list below](https://github.com/zarr-conventions/.github/edit/main/profile/README.md):

* f17cb550-5864-4468-aeb7-f3180cfb622f — [https://github.com/zarr-experimental/geo-proj](https://github.com/zarr-experimental/geo-proj)
* 689b58e2-cf7b-45e0-9fff-9cfc0883d6b4 - [https://github.com/zarr-conventions/spatial](https://github.com/zarr-conventions/spatial)
* d35379db-88df-4056-af3a-620245f8e347 - [https://github.com/zarr-conventions/multiscales](https://github.com/zarr-conventions/multiscales)
