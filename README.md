# Tag SemVer Action

- [Tag SemVer Action](#tag-semver-action)
  - [Input Parameters](#input-parameters)
  - [Workflow Examples](#workflow-examples)
  - [Reference](#reference)
  - [Contributing](#contributing)

**Universal Actions** are GitHub Composite Actions that are highly reusable, maintainable and can adapt to work with multiple types of project. They are born to abstract the underlying commands and logics to achieve a specific task, enabling DevOps Engineers to focus on the most crucial parts of their implementation and reduce an amount of time to repeatedly write these actions.

**Tag SemVer** is an Universal Action created to automatically show and push (optional) a tag using Semantic Versioning strategy.

## Input Parameters

| Parameter Name          | Required? | Type    | Default Value  | Description                                |
| ----------------------- | --------- | ------- | -------------- | ------------------------------------------ |
| gitversion-version-spec | false     | string  | 6.0.x          | Version to be used for GitVersion          |
| push                    | false     | boolean | false          | Whether to push the SemVer tag to GitHub   |
| use-config-file         | false     | boolean | false          | Whether to use your own config file        |
| config-file-path        | false     | boolean | gitversion.yml | The path of the config path for GitVersion |

## Workflow Examples

## Reference

## Contributing
