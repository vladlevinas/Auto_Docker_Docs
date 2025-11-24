---
source_repo: docker/cli
source_path: docs/reference/commandline/context_export.md
original_url: https://github.com/docker/cli/blob/master/docs/reference/commandline/context_export.md
published_at: 2025-11-24T13:32:44Z
---


<!---MARKER_GEN_START-->
Export a context to a tar archive FILE or a tar stream on STDOUT.


<!---MARKER_GEN_END-->

## Description

Exports a context to a file that can then be used with `docker context import`.

The default output filename is `<CONTEXT>.dockercontext`. To export to `STDOUT`, 
use `-` as filename, for example:

```console
$ docker context export my-context -
```
