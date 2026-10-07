# neosloc

`sloccount` counted lines of code and priced them with COCOMO. With LLMs writing code,
lines are cheap. **neosloc** measures what still costs something:

- **Integrability** in ten dimensions, as ladders of checkable requirements, judged per
  surface (service, CLI, library, desktop app, frontend).
- **Make or buy**: tokens, agent hours and human days to rebuild a project with agents,
  against minutes to adopt it as it is.
- **neoCOCOMO**: what a codebase is worth when agents can re-type it.
- **LLM evaluators** that try real integration tasks and audit the scores.

```bash
pip install neosloc
neosloc path/to/repo
```

[Documentation](https://neosloc.github.io/neosloc/) ·
[Repository](https://github.com/neosloc/neosloc) ·
[PyPI](https://pypi.org/project/neosloc/)
