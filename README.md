# dsh-test

A public sandbox for trying **DeepSeek dsh-superagent** on real GitHub activity.

## What this is

dsh-superagent is a coding agent that works on one GitHub repository. It listens
for requests in issues and pull requests, turns authorized requests into work
items, works on them in its own branch, and replies in the original conversation
— usually with a pull request.

This repository is the test bed for that loop. There is no application code: the
issues, comments and pull requests are the test cases, and any files here are
leftovers from experiments.

## Using the sandbox

1. Open an issue, or comment on an existing one, and mention the agent, for
   example `@qbudcu`.
2. The agent acknowledges the request and works on its own branch.
3. Review the result in the pull request or in the original thread.

Everything here is disposable. Test branches and files may be rewritten or
removed at any time.

## Notes

- This is a sandbox, not a supported product; nothing here is production code.
- Do not post secrets, credentials or private data.
- The repository is currently just this README — there is no build or test
  suite.

## License

No license is provided; this repository is for testing only.
