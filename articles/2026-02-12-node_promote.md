---
source_repo: docker/cli
source_path: docs/reference/commandline/node_promote.md
original_url: https://github.com/docker/cli/blob/master/docs/reference/commandline/node_promote.md
published_at: 2026-02-12T07:51:05Z
---


<!---MARKER_GEN_START-->
Promote one or more nodes to manager in the swarm


<!---MARKER_GEN_END-->

## Description

Promotes a node to manager. This command can only be executed on a manager node.

> [!NOTE]
> This is a cluster management command, and must be executed on a swarm
> manager node. To learn about managers and workers, refer to the
> [Swarm mode section](https://docs.docker.com/engine/swarm/) in the
> documentation.

## Examples

```console
$ docker node promote <node name>
```

## Related commands

* [node demote](node_demote.md)
* [node inspect](node_inspect.md)
* [node ls](node_ls.md)
* [node ps](node_ps.md)
* [node rm](node_rm.md)
* [node update](node_update.md)
