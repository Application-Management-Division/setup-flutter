[//]: # (TEMPLATE INSTRUCTIONS — delete this block before committing)
[//]: # (Profile: library)
[//]: # (Asset key: api_reference)
[//]: # (Destination: docs/api-reference.md)
[//]: # (Purpose: Authoritative public API surface documentation for this library.)
[//]: # (How to use:)
[//]: # (  1. Copy this file to docs/api-reference.md in your library repository.)
[//]: # (  2. Replace every [placeholder] with real values.)
[//]: # (  3. Add one entry per exported symbol following the patterns below.)
[//]: # (  4. If your toolchain auto-generates API docs, this file may serve as the)
[//]: # (     hand-authored supplement — link to the generated output from the header.)
[//]: # (  5. Delete this instruction block before committing.)
[//]: # (  6. Declare the path in your docs-manifest.yml under assets.api_reference.)

# API Reference — [library-name] v[version]

> **Stability:** [Stable | Beta | Experimental]  
> **Language:** [Python 3.x | TypeScript | Go | …]  
> **Package:** `[package-name]`  
> **Source:** [`[repo-name]`](https://github.com/Application-Management-Division/[repo-name])  
> **Generated docs (if available):** [link to auto-generated reference]

This document covers every public symbol exported by **[library-name]**.
Internal symbols (prefixed `_` in Python, unexported in Go, etc.) are not listed here.

> **Version note:** This reference reflects **v[version]**. For older versions see the
> [CHANGELOG](../CHANGELOG.md).

---

## Contents

- [Installation](#installation)
- [Quick start](#quick-start)
- [Classes](#classes)
  - [[ClassName]](#classname)
- [Functions](#functions)
  - [[function_name]](#function_name)
- [Types and interfaces](#types-and-interfaces)
- [Exceptions and errors](#exceptions-and-errors)
- [Constants and enumerations](#constants-and-enumerations)
- [Configuration](#configuration)
- [Deprecation notices](#deprecation-notices)

---

## Installation

```bash
# [Package manager command — e.g. pip, npm, go get]
[install command]
```

Minimum runtime requirement: [Python ≥ 3.10 | Node ≥ 18 | Go ≥ 1.21 | …]

---

## Quick start

```[language]
# Minimal working example that demonstrates the most common use case.
[import or require statement]

[two to five lines of example code]
```

---

## Classes

### `[ClassName]`

> **Module / package path:** `[package-name].[module]`  
> **Since:** v[version]  
> **Stability:** [Stable | Beta | Experimental]

[One-sentence summary of what this class represents and its primary responsibility.]

#### Constructor

```[language]
[ClassName](param1: [Type], param2: [Type] = [default], **kwargs)
```

| Parameter | Type | Required | Default | Description |
|---|---|---|---|---|
| `param1` | `[Type]` | Yes | — | [What param1 controls or represents.] |
| `param2` | `[Type]` | No | `[default]` | [What param2 controls.] |

**Raises**

| Exception | Condition |
|---|---|
| `[ExceptionType]` | [When this is raised.] |

#### Methods

##### `method_name(param: Type) -> ReturnType`

[One-sentence description of what this method does.]

```[language]
# Example
instance = [ClassName](param1=[value])
result = instance.method_name(param=[value])
```

| Parameter | Type | Required | Description |
|---|---|---|---|
| `param` | `[Type]` | Yes | [Description.] |

**Returns:** `[ReturnType]` — [What the return value represents.]

**Raises:** `[ExceptionType]` — [When.]

---

<!-- Repeat the above block for each class. -->

---

## Functions

### `[function_name](param1, param2)`

> **Module:** `[package-name].[module]`  
> **Since:** v[version]

[One-sentence description of what this function does.]

```[language]
from [package-name] import [function_name]

result = [function_name](param1=[value], param2=[value])
```

#### Parameters

| Parameter | Type | Required | Default | Description |
|---|---|---|---|---|
| `param1` | `[Type]` | Yes | — | [Description.] |
| `param2` | `[Type]` | No | `[default]` | [Description.] |

#### Returns

`[ReturnType]` — [What the return value represents and when it may be `None` / empty.]

#### Raises

| Exception | Condition |
|---|---|
| `[ExceptionType]` | [Condition that triggers this.] |

#### Notes

[Edge cases, performance characteristics, thread-safety guarantees, or caveats.
Delete this subsection if there is nothing to note.]

---

<!-- Repeat the above block for each public function. -->

---

## Types and interfaces

### `[TypeName]`

> **Since:** v[version]

[Description of what this type or interface models.]

```[language]
# Type definition or interface body
[TypeName] = [definition]
```

| Field / Property | Type | Description |
|---|---|---|
| `field1` | `[Type]` | [Description.] |
| `field2` | `[Type]` | [Description.] |

---

## Exceptions and errors

| Exception | Inherits from | When raised |
|---|---|---|
| `[ExceptionName]` | `[BaseException]` | [Condition.] |

---

## Constants and enumerations

### `[EnumName]`

| Member | Value | Description |
|---|---|---|
| `[MEMBER]` | `[value]` | [Description.] |

---

## Configuration

[Describe any environment variables, configuration files, or initialisation options
that affect library behaviour globally.]

| Variable / Key | Type | Default | Description |
|---|---|---|---|
| `[CONFIG_KEY]` | `[Type]` | `[default]` | [Description.] |

---

## Deprecation notices

| Symbol | Deprecated since | Removal target | Replacement |
|---|---|---|---|
| `[old_symbol]` | v[version] | v[future version] | `[new_symbol]` |

---

## Changelog

See [CHANGELOG.md](../CHANGELOG.md) for a full release history.
