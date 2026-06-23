# Thread

**Thread** is a modern developer workspace for managing projects, repositories,
branches, worktrees, and AI-agent workflows across machines.

We are building a new generation of developer tools for parallel work:
local-first, Git-compatible, agent-aware, and designed for granular source
control and collaboration.

> Work across machines, branches, and agents.

---

## Why Thread?

Development workflows are becoming more parallel and distributed:

- developers work across multiple machines;
- projects and worktrees keep multiplying;
- AI agents introduce new execution contexts;
- conversations, tasks, branches, and code states need to stay aligned;
- Git is still essential, but many workflows around it are becoming harder to manage.

Thread aims to make this complexity manageable.

---

## Projects

### Thread Deck

The project and repository manager.

Thread Deck helps developers manage Git projects, branches, worktrees, and local
project state across multiple machines.

It is the first product being built.

### Thread Weave

An experimental next-generation version control system.

Thread Weave explores continuous versioning, conflict-friendly workflows,
granular permissions, path-based visibility, better monorepo support, and a
native client/server model.

### Thread Forge

A future hosting and collaboration platform.

Thread Forge will provide repository hosting, permissions, code review, CI/CD,
security features, and support for Git and Thread Weave repositories.

---

## Principles

- **Local-first** — local work should stay fast, reliable, and available offline.
- **Git-compatible** — Thread starts by improving existing Git workflows.
- **Developer-first** — reduce friction and context switching.
- **Agent-aware** — model the relationship between agents, tasks, branches, and worktrees.
- **Granular by design** — support fine-grained control over refs, paths, and permissions.
- **Performance-conscious** — account for large repositories, monorepos, and filesystem limitations.

---

## Current Focus

The first milestone is **Thread Deck**: a CLI tool for managing Git projects,
branches, worktrees, and project state across machines.

Initial goals:

- register local projects;
- detect Git repositories;
- list branches, remotes, and worktrees;
- track active project state;
- prepare multi-machine synchronization;
- prepare AI-agent workflow integration.

---

## Technical Direction

Core tooling will primarily be built in **Rust**.

The future web platform may use a modern **React / TypeScript** stack such as
Next.js or TanStack Start.

Potential protocol and communication layers include **Protobuf**, **gRPC**, and
HTTP APIs where appropriate.

---

## Status

Thread is currently in the design and prototyping phase.

The project starts as a monorepo to enable fast iteration across the CLI,
project manager, sync engine, protocol definitions, and future platform.

---

## Mission

**Thread aims to become the modern versioning workspace for developers, teams,
and AI agents.**

Work faster and more safely across machines, branches, tasks, agents, and
repositories — without losing the thread.
