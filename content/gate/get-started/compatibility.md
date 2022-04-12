---
title: Compatibility
pcx-content-type: compatibility
weight: 5
meta:
  title: Server Compatibility
---

# Server Compatibility

Gate is compatible with many Minecraft server implementations.
The expectation is that if the server acts like vanilla, Gate will work,
and we make special provisions for modded setups where we can.

Gate is compatible with Minecraft 1.7.2 through the latest version
and we maintainers update Gate as soon as a new Minecraft version is released.

## Paper

We highly recommend using [Paper](https://papermc.io/) for running a server in most cases.
Gate is tested with the most used versions of it.

You can use `modern` forwarding (like Velocity does) if you run Paper
1.13.2 or higher. If you use Paper 1.12.2 or lower, you must use `legacy` BungeeCord-style forwarding.

## Spigot

Spigot is not well-tested with Gate.
However, it is based on vanilla and as it is the base for Paper, it is relatively well-supported.

Spigot does not support Gate's modern forwarding, but does support legacy BungeeCord forwarding.

## Proxy-behind-proxy _(Gate, BungeeCord/Waterfall, Velocity, ...)_

These setups are only supported with [Connect](/connect) enabled.
You are best advised to avoid other kinds of setups, as they can cause lots of issues.
Most proxy-behind-proxy setups are either illogical in the first place or can be handled more
gracefully by better, more scalable and performant solutions like [Connect](/connect).

