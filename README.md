# Hi, I'm James 👋

**Backend software engineer** in London, working in UK energy retail. I build Python services that model messy real-world workflows clearly and keep working when things fail.

## What I do

- **Now: OVO Energy, Data and AI Platform.** Backend for a self-service data-access workflow: a GraphQL integration, an event-driven listener with retry and backoff, and an idempotent scheduled sync that settles each request from its pull request. Python, GraphQL, GCP (Cloud Run), Kubernetes, Terraform.
- **Before: Quick Release.** Maintained the company's internal Django, Celery and Postgres platform used by all ~400 staff, and built change-management tools for Ford used daily by ~150 engineers (cut a six-hour daily task to under one hour).

## How I like to build

- Model the domain first: explicit states, one owner for each fact
- Make jobs idempotent, so running them twice changes nothing
- Separate errors to retry from errors to surface, so one bad record never blocks the rest
- Test it: pytest, mypy, and CI on every change

## Projects

- [**energy-data-quality-pipeline**](https://github.com/Webb-Site/energy-data-quality-pipeline): validation rules for customer, tariff and meter-reading data, loaded into DuckDB, with SQL checks and pytest
- **TrainBot** (team project): Django REST Framework API with spaCy entity recognition and fare logic that finds the cheapest journey
- **Cognitive decline detection** (dissertation): ML speech pipeline, ~81% accuracy

## Stack

`Python` `Django` `Django REST Framework` `Celery` `Postgres` `GraphQL` `pytest` `mypy` `GCP` `Docker` `Kubernetes` `Terraform` `GitHub Actions`

## Contact

[LinkedIn](https://www.linkedin.com/in/webb-site) · james@webbnet.org.uk
