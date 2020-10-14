# Competency - GitHub Actions

GitHub Actions are an API for cause and effect on GitHub: orchestrate any workflow, based on any event, while GitHub manages the execution, provides rich feedback, and secures every step along the way. With GitHub Actions, workflows and steps are just code in a repository, so you can create, share, reuse, and fork your software development practices.

## How do you prove it?
* You can create a continuous integration workflow for a project that automatically runs tests for your code and uses branch protection to only allows pull requests to be merged if the tests pass.
* You can create a workflow that produces packages (such as NPM packages) and uploads them to GitHub Packages or another package hosting service.
* You know how to securely store secrets within GitHub, and are aware of the security risks in not doing so.
* You know how to cache dependencies using `actions/cache@v2` in order to speed up workflows.
* You know how to add conditional steps, such as `if: github.event.pull_request.draft == false`, to a job.
* You know how to use `upload-artifact` and `download-artifact` actions in order to persist and share data across workflows.
* You know how to add actions from the GitHub Marketplace to your workflow.
* You know how to create workflow templates and use templates created by others.
* You are aware of the different mechanisms for triggering a GitHub Actions workflow and the use cases of each.
* You are aware of the difference between workflows, events, jobs, steps, actions, and runners.

## How do you improve it?
* Read the [docs](https://docs.github.com/en/free-pro-team@latest/actions)