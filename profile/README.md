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

## Share your convention

If you have published a Zarr convention, please [add it to the table below](https://github.com/zarr-conventions/.github/edit/main/profile/README.md):

| Name | Description | UUID | Repository |
| ---- | ----------- | ---- | ---------- |
| geo-proj | Coordinate reference system information for geospatial data | f17cb550-5864-4468-aeb7-f3180cfb622f | <https://github.com/zarr-experimental/geo-proj> |
| spatial | Spatial coordinate information | 689b58e2-cf7b-45e0-9fff-9cfc0883d6b4 | <https://github.com/zarr-conventions/spatial> |
| multiscales | Multiscale layout of zarr datasets | d35379db-88df-4056-af3a-620245f8e347 | <https://github.com/zarr-conventions/multiscales> |
| license | License specifier for Zarr data | b77365e5-2b0c-4141-b917-c03b7c68e935 | <https://github.com/clbarnes/zarr-convention-license> |
| uom | Units of measurement for Zarr arrays | 3bbe438d-df37-49fe-8e2b-739296d46dfb | <https://github.com/clbarnes/zarr-convention-uom> |
