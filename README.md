<!-- Generated with Stardoc: http://skydoc.bazel.build -->

# Bazle/skylark rule(s) to process GraphViz.

## `MODULE.bazel`

```
bazel_dep(
    name = "com_github_bcsgh_graphviz",
    version = ...,
)
```

<a id="gen_dot"></a>

## gen_dot

<pre>
load("@com_github_bcsgh_graphviz//graphviz:graphviz.bzl", "gen_dot")

gen_dot(<a href="#gen_dot-name">name</a>, <a href="#gen_dot-src">src</a>, <a href="#gen_dot-out">out</a>, <a href="#gen_dot-format">format</a>)
</pre>

Process a .dot file.

**ATTRIBUTES**


| Name  | Description | Type | Mandatory | Default |
| :------------- | :------------- | :------------- | :------------- | :------------- |
| <a id="gen_dot-name"></a>name |  A unique name for this target.   | <a href="https://bazel.build/concepts/labels#target-names">Name</a> | required |  |
| <a id="gen_dot-src"></a>src |  The .dot file.   | <a href="https://bazel.build/concepts/labels">Label</a> | required |  |
| <a id="gen_dot-out"></a>out |  The target file name.   | <a href="https://bazel.build/concepts/labels">Label</a> | required |  |
| <a id="gen_dot-format"></a>format |  The output file format.   | String | optional |  `"png"`  |


## Setup (for development)
To configure the git hooks, run `./.git_hooks/setup.sh`
