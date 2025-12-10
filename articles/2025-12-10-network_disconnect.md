---
source_repo: docker/cli
source_path: docs/reference/commandline/network_disconnect.md
original_url: https://github.com/docker/cli/blob/master/docs/reference/commandline/network_disconnect.md
published_at: 2025-12-10T13:36:28Z
---


<!---MARKER_GEN_START-->
Disconnect a container from a network

### Options

| Name            | Type   | Default | Description                                      |
|:----------------|:-------|:--------|:-------------------------------------------------|
| `-f`, `--force` | `bool` |         | Force the container to disconnect from a network |


<!---MARKER_GEN_END-->

## Description

Disconnects a container from a network. The container must be running to
disconnect it from the network.

## Examples

```console
$ docker network disconnect multi-host-network container1
```


## Related commands

* [network inspect](network_inspect.md)
* [network connect](network_connect.md)
* [network create](network_create.md)
* [network ls](network_ls.md)
* [network rm](network_rm.md)
* [network prune](network_prune.md)
* [Understand Docker container networks](https://docs.docker.com/engine/userguide/networking/)
