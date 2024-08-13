# reusable-workflows

Check out my reusable workflows in the [`.github/workflows`](https://github.com/joshjohanning-org/reusable-workflows/tree/main/.github/workflows) directory! 🚀 ✨

## Releasing

Create a release manually by incrementing to the next semver version. The [workflow](https://github.com/joshjohanning-org/reusable-workflows/blob/main/.github/workflows/update-major-version-tag.yml) will rotate the latest major tag automatically afterwards.

## Calling Workflows

These repos are referencing the reusable workflows in this repository:

- [joshjohanning-org/terraform-tailspin-github-actions-and-azdo-demo](https://github.com/joshjohanning-org/terraform-tailspin-github-actions-and-azdo-demo/blob/main/.github/workflows/terraform.yml) (using [OIDC with `job_workflow_ref`](https://josh-ops.com/posts/github-actions-oidc-reusable-workflows/))
- [joshjohanning-org/environments-deployment](https://github.com/joshjohanning-org/environments-deployment/blob/main/.github/workflows/cicd.yml) (sample workflow using environments)
- [joshjohanning-org/reusable-workflow-secrets-inherit-sample](https://github.com/joshjohanning-org/reusable-workflow-secrets-inherit-sample/blob/main/.github/workflows/ci.yml) (using `secrets: inherit`)
- [joshjohanning-org/simple-docker-action](https://github.com/joshjohanning-org/simple-docker-action/blob/main/.github/workflows/docker-publish.yml) (building and publishing a Docker image)
- [joshjohanning-org/docker-build-publish-deploy](https://github.com/joshjohanning-org/docker-build-publish-deploy/blob/main/.github/workflows/docker-image.yml) (another Docker build/publish example)
- [joshjohanning-org/oidc-claims-demo](https://github.com/joshjohanning-org/oidc-claims-demo/blob/main/.github/workflows/azure-oidc-demo.yml) (Azure OIDC demo)
- [joshjohanning-org/repo-rules-security-checks-demo](https://github.com/joshjohanning-org/repo-rules-security-checks-demo/blob/main/.github/workflows/security-checks.yml) (using org-level repo rulesets and the "required status checks" to enforce security requirements)
