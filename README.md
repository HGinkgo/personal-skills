# Personal Skills (`pskills`)

Reusable Codex skills maintained by HGinkgo.

## Included skill

- [`general-workflow`](./general-workflow/) - A practical operating guide for scoped work, evidence-based decisions, risk confirmation, and reversible execution.

## Install in Codex

Copy the skill folder into your local Codex skills directory:

```powershell
Copy-Item -Recurse .\general-workflow "$env:USERPROFILE\.codex\skills\general-workflow"
```

Or clone the repository and copy it directly:

```powershell
git clone https://github.com/HGinkgo/personal-skills.git
Copy-Item -Recurse .\personal-skills\general-workflow "$env:USERPROFILE\.codex\skills\general-workflow"
```

After installation, start a new Codex task. The skill can be selected automatically when the request involves planning, scoped implementation, or risky external actions. You can also invoke it explicitly with `$general-workflow`.

## Repository name

The repository is named **personal-skills**. Its short English name is **pskills**.

## License

MIT. See [LICENSE](./LICENSE).
