# Trigger Another Repo's Workflow


This repo is an example of triggering a Github Action in another repo upon any commits to the `main` branch.

This workflow requires a Personal Access Token to be created with `repo` and `workflow` scopes.

Refer to this [repo](https://github.com/benhpoh/workflow-dispatch-receiver/blob/main/.github/workflows/workflow-dispatch.yml) for an example on the receiving end.

The full step by step write-up on this 2 part process is detailed in this blog post: [blog.benhpoh](https://blog.benhpoh.com/2022/01/21/trigger-another-github-repos-workflow/)