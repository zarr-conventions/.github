# Zarr Conventions

This organisation contains documentation and tooling to help define and share Zarr Conventions.

## What is a Zarr Convention?

A Zarr Convention is simply a way of using Zarr to store data for a particular domain, application or purpose.
For example, a Zarr Convention can define a set of attributes for storing specific metadata that helps downstream applications provide special behaviour and users interpret the data.

## Define your own convention

To define and share your own convention:

1. [Create a new GitHub repository using the zarr-conventions template](https://github.com/new?template_name=template&template_owner=zarr-conventions)
1. Create a new UUID to use as a globally-unique identifier for your convention. 
1. Edit the README.md document in your GitHub repo to describe your usage convention for developers and users.
1. Optionally, edit the schema.json file in your GitHub repo to define validation constraints on your metadata.
1. Commit your changes and make a GitHub release so you have a stable version of your spec and schema to point to.
1. Share your convention (see below).

## Share your convention

If you have published a Zarr convention, please [add it to the list below](https://github.com/zarr-conventions/.github/edit/main/README.md):

* UUID — website
