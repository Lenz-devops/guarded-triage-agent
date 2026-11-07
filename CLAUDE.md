# Project rules
- Python 3.12, managed with uv. Add dependencies only with `uv add`, and only after asking me.
- Never read, print, log or hardcode secrets. Config comes from environment variables.
- No `shell=True`, `eval`, `exec` or `pickle` on untrusted data.
- Never catch broad exceptions silently. Fail loudly with a clear message.
- Every change comes with a pytest test. Never delete or weaken a test to make it pass.
- Never use `--no-verify` or disable a linter rule without telling me why.
- Keep changes small: one concern per change. Explain the plan before writing code.
