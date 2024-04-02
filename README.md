<p align="center">
    <img src="https://github.com/ricardoleal20/SemPyVer/blob/main/docs/img/logo.png" />
</p>
<p align="center">
    <b>Tool for teams that manage the creation and modification of the </b>CHANGELOG<b> based on a specified set of changes.</b>
</p>

![PyPi version](https://img.shields.io/pypi/v/sempyver?label=PyPi%20version&logo=PyPi&style=for-the-badge)
![Python versions supported](https://img.shields.io/pypi/pyversions/sempyver?label=Python%20Versions%20Supported&logo=Python&style=for-the-badge)
![Deployed](https://img.shields.io/github/actions/workflow/status/ricardoleal20/SemPyVer/publish.yml?branch=main&label=LAST%20VERSION%20DEPLOYED%20%F0%9F%9A%80&logo=Github&style=for-the-badge)
![License](https://img.shields.io/github/license/ricardoleal20/SemPyVer?color=%23808000&label=%F0%9F%93%84%20LICENSE&style=for-the-badge)

## Installation

To install `SemPyVer`, you can do it through pip:

```
pip install sempyver
```

Please consider that it requires `Python >=3.8`

## Usage

Sure! Here's an example of how you can write the usage instructions in English for the `README.md` file:

---

## Usage

This Rust package, `sempyver`, provides several command-line tools for managing project versions and changesets. Below are the available commands and their usage examples.

### Commands

#### `create`

Create a new changeset to document changes in the project.

```sh
sempyver create
```

This command creates a new changeset with the provided description. 

#### `list`

List all changesets created for the project.

```sh
sempyver list
```

This command displays a list of all changesets recorded in the project, along with their descriptions and types.

#### `bump`

Bump the project version according to the specified type.

```sh
sempyver bump
```

This command increments the project version based on the specified type: `major`, `minor`, or `patch`. It updates the version number in the project files accordingly.

Also, it deletes all the current `changesets` to avoid changes 

---

For more details on each command and its options, refer to the command-line help:

```sh
sempyver --help
```

## Contributing

Everyone can contribute. Before contributing, please read our [code of conduct](CODE_OF_CONDUCT.md).

To contribute to `SemPyVer`, follow these steps:

1. Fork this repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.

## License

Project Name is released under the [MIT License](LICENSE).

## Inspiration

Inspired by [Changesets](https://github.com/changesets/changesets).
