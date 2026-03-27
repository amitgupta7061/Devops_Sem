# Day 9 - Docker Compose Fundamentals

> Date: 27-03-2026

## Topics covered
1. Why Docker Compose is useful for multi-container apps
2. Structure of a `docker-compose.yml` file
3. Core Compose keys: `services`, `volumes`, `networks`
4. Service dependencies with `depends_on`
5. Environment variables and `.env` usage in Compose
6. Running, stopping, and inspecting Compose applications

## Tasks completed
- Understood when to use Compose instead of multiple `docker run` commands
- Learned the minimum YAML structure required for a working setup
- Practiced connecting app and database services on a shared network

## Practice done
- Created a basic Compose file with two services (`web`, `db`)
- Added a named volume for database persistence
- Tested startup and teardown lifecycle with Compose CLI

## Next class plan
- Compose for development workflows (override files, profiles, scaling)
