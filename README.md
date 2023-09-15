# Common Workflows

This project groups a list of reusable workflows that are used by external projects.

## How does it work?

Workflows are created/modified in the `src` folder, and processed by [Workflow Preprocessor](https://github.com/unknorg/workflow-preprocessor)
which outputs valid GitHub workflows to `.github/workflows/*workflow-name*.gen.yml`

Do not edit the generated workflows, since they will be overwritten anyway on the next generation.

## Project templates

Project templates can be found in the folder [project-templates](/project-templates), these are meant to be plug&play.

**You must ensure that the needed variables/secrets are defined in your repository/organization**.