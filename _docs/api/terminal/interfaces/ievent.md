---
title: IEvent
category: API-interfaces
layout: docs
---


# Interface: IEvent <**T, U**>

## Type parameters

▪ **T**

▪ **U**

## Hierarchy

* **IEvent**

## Callable

▸ (`listener`: function): *[IDisposable]({% link _docs/api/terminal/interfaces/idisposable.md %})*

*Defined in [xterm.d.ts:374](https://github.com/xtermjs/xterm.js/blob/4.14.1/typings/xterm.d.ts#L374)*

**Parameters:**

▪ **listener**: *function*

▸ (`arg1`: T, `arg2`: U): *any*

**Parameters:**

Name | Type |
------ | ------ |
`arg1` | T |
`arg2` | U |

**Returns:** *[IDisposable]({% link _docs/api/terminal/interfaces/idisposable.md %})*

an `IDisposable` to stop listening.
