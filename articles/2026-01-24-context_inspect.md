---
source_repo: docker/cli
source_path: docs/reference/commandline/context_inspect.md
original_url: https://github.com/docker/cli/blob/master/docs/reference/commandline/context_inspect.md
published_at: 2026-01-24T13:29:59Z
---


<!---MARKER_GEN_START-->
Display detailed information on one or more contexts

### Options

| Name             | Type     | Default | Description                                                                                                                                                                                                                                                        |
|:-----------------|:---------|:--------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `-f`, `--format` | `string` |         | Format output using a custom template:<br>'json':             Print in JSON format<br>'TEMPLATE':         Print output using the given Go template.<br>Refer to https://docs.docker.com/go/formatting/ for more information about formatting output with templates |


<!---MARKER_GEN_END-->

## Description

Inspects one or more contexts.

## Examples

### Inspect a context by name

```console
$ docker context inspect "local+aks"

[
  {
    "Name": "local+aks",
    "Metadata": {
      "Description": "Local Docker Engine",
      "StackOrchestrator": "swarm"
    },
    "Endpoints": {
      "docker": {
        "Host": "npipe:////./pipe/docker_engine",
        "SkipTLSVerify": false
      }
    },
    "TLSMaterial": {},
    "Storage": {
      "MetadataPath": "C:\\Users\\simon\\.docker\\contexts\\meta\\cb6d08c0a1bfa5fe6f012e61a442788c00bed93f509141daff05f620fc54ddee",
      "TLSPath": "C:\\Users\\simon\\.docker\\contexts\\tls\\cb6d08c0a1bfa5fe6f012e61a442788c00bed93f509141daff05f620fc54ddee"
    }
  }
]
```
