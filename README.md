# git

Simple role for Ansible, which installs git client

## Usage (example)

```yaml
    - role: git
```

### Install git, git-lfs and activate for users

```yaml
- role: git
  git_lfs:
    enabled: true
    users:
      - user1
      - user2
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `git_setup` | `full` | Setup mode. |

## FAQ

...

## Useful links

- [Official documentation](https://git-scm.com/doc)

## TODO

- ...
