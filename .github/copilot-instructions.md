# Copilot coding agent instructions

## General goals
- Make sure that all the files in the Pull Request form a coherent whole.
- When you are unsure, ask clarifying questions.

## Pull requests & reviews
- Do not summarize the changes.
- Leave **comments in French**.
- Use a **gentle, positive tone** in all review feedback.
- Favor actionable suggestions, and explain the “why” briefly.

## Python quality guidelines
- **Type all Python functions**: add type hints for parameters and
  return types.  If the return type is `None`, it must *not* not be
  declared.
- **Documentation**: every function must have **at least one line of documentation** (docstring).
  - If a function has no docstring, suggest a very short one (one sentence) that states its purpose.
- **Factorization / DRY**:
  - Keep code well factorized and avoid repetition.
  - Extract helpers for repeated logic.
  - Prefer clear, reusable functions over copy/paste blocks.

## Style & maintainability
- Keep naming consistent and descriptive.
- Prefer pure functions when possible.
- Add or adjust tests when behavior changes.
- Update documentation when introducing new behavior.
