# ODM Example Project

An example [OPA](https://github.com/open-policy-agent/opa) Rego project using [ODM](https://github.com/johanfylling/opa-dependency-manager) for dependency management.

This example project implements a simple policy that requires a [git dependency](https://github.com/johanfylling/odm-example-dependency).

## Running the sample

Update project dependencies:

```bash
odm update
```

Evaluate the policy:

```bash
odm eval -- 'data.example' -f pretty
```
