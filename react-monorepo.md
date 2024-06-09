## 1. Getting started with NX

Nx is a toolkit for monorepo development, primarily focused on Angular, React, Nest.js, etc.

**Features of NX Workspace**:

- It organizes projects within a monorepo in a structured manner.
- It provides dedicated directories for applications, libraries, and shared code, thus promoting code reuse, modularity, and maintainability.
- With a monorepo-style NX workspace, you can easily add new projects, refactor the existing ones, and manage the entire codebase as a cohesive unit.

**Creating a new project**:

`npx create-nx-workspace react-monorepo --preset=react-monorepo -pm pnpm`

## 2. Running tasks

Say, we have a react monorepo with "task-manager" project.

1. `nx show project task-manager --web`