---
source_repo: docker/cli
source_path: docs/reference/commandline/container_start.md
original_url: https://github.com/docker/cli/blob/master/docs/reference/commandline/container_start.md
published_at: 2025-11-21T13:27:37Z
---


<!---MARKER_GEN_START-->
Start one or more stopped containers

### Aliases

`docker container start`, `docker start`

### Options

| Name                  | Type     | Default | Description                                         |
|:----------------------|:---------|:--------|:----------------------------------------------------|
| `-a`, `--attach`      | `bool`   |         | Attach STDOUT/STDERR and forward signals            |
| `--checkpoint`        | `string` |         | Restore from this checkpoint                        |
| `--checkpoint-dir`    | `string` |         | Use a custom checkpoint storage directory           |
| `--detach-keys`       | `string` |         | Override the key sequence for detaching a container |
| `-i`, `--interactive` | `bool`   |         | Attach container's STDIN                            |


<!---MARKER_GEN_END-->

## Examples

```console
$ docker start my_container
```
