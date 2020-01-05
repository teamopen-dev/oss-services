# OSS services

A collection of tools meant to improve access and reduce 'cost of forking' for open-source projects.

## Assumptions

This is intended as shared infrastructure, so **we don't trust the admins**.
Either data and control is handed to the project community, or we handle public data only.

The basic building block to run infrastructure on will be **Docker, in swarm mode**.
While an arbitrary choice, it's a good way to make the services declarative that many devs are familiar with.

## Structure

`/stacks` include services to be run on a Docker swarm.

`/hosts` include scripts to set up Docker hosts for the swarm.
