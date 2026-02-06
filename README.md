# Claude Code Skills

These are some skills I use on a regular basis while developing with Claude Code. These are 
experimental however, and for polished versions of these skills, please see the skills within 
[khaaliDimaag]().

## How the repo is structured

### [`_references`](./_references/)

This folder contains git submodules to skills from [skills.sh](https://skills.sh). The skills here 
are used as a reference to develop the skills within [`skills`](./skills/).

### [`skills`](./skills/)

This folder contains all the skills developed. They are prefixed by the language, tool, framework, 
or type. To view a list of all current skills, please see [this readme](./skills/README.md).

Each skill is in a folder using kebab-case with the format `{prefix}-{skill-name}`. The skill 
folder is structured as following,
```sh
- {prefix}-{skill-name}
| - {prefix}-{skill-name}-skill.md # the actual skill document
| - references/ # any references needed for the skill
```

#### Current Prefixes

- `cadence-`
- `django-`
- `docker-`
- `git-`
- `htmx-`
- `kdio-`
- `md-`
- `python-`
- `rust-`
- `solidity-`
- `tailwind-`
- `tauri-`
- `web3-`
  - `web3-cdc-`
  - `web3-evm-`
  - `web3-move-`

## Contributing

Contributions are very welcome! This is the process to do so,
1. Open a new issue in the repository using the template.
2. Clone and checkout a new branch prefixed with the issue number.
3. Develop the skill following the naming and folder guidelines.
4. Submit a PR!

## License

MIT. Do whatever with this as you wish.