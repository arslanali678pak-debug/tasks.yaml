# tekton-tasks

Two Tekton `Task` definitions in `tasks.yaml`:

- **npm** — runs npm commands (`install`, `run build`, ...) on a Node.js project.
- **jasmine** — runs the Jasmine test suite with `npx jasmine`.

Apply with:

```bash
kubectl apply -f tasks.yaml
```
