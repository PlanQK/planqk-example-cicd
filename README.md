# planqk-example-cicd

This repository showcases how to use GitHub Actions to update PlanQK services.

## Project structure

The repository contains a scaffolded project structure, which can also be generated using the [PlanQK CLI](https://docs.platform.planqk.de/cli-reference.html).
After cloning/generating it, you should find the following structure:

```
.
├── Dockerfile
├── openapi-spec.yml
├── environment.yml
├── requirements.txt
├── planqk.json
├── input
│   └── ...
└── src
    ├── __init__.py
    ├── __main__.py
    ├── libs
    │   ├── __init__.py
    │   ├── return_objects.py
    │   └── ...
    └── program.py
``` 

> **IMPORTANT:**
> Leave the structure unchanged, then the deployment will succeed.
