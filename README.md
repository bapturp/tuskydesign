# Nx

Add nx:

```sh
npx nx@latest init
```

Adding nx set up a Nx workspace. The workspace is defined with a configuration file `nx.json`.

The workspaces can be explore using the command `npx nx graph`.

Tasks

We can run a single task using: `npx nx <target> <project>`:

- `target`: one of the target defined in `nx.json` `.targetDefaults`
- `project`: on of the project defined in `package.json` `.workspaces`

We can run all tasks with a certain name `npx nx run-many -t <target>`:

- `target`: one of the target defined in `nx.json` `.targetDefaults`

```
test
```
