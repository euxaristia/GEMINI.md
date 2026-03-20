## Gemini Added Memories
- When asked to 'commit & push' followed by other tasks, always complete the git operations (stage, commit, push) before starting the subsequent tasks.
- always make sure builds and tests pass before commiting & pushing
- NEVER commit or push changes without first asking the user for confirmation and allowing them to test the changes locally. All previous instructions to 'commit & push' are overridden by this mandatory verification step.
- Always run builds and tests yourself rather than asking the user if they want to test. Just do it.
- Always write tests for every new feature you implement. Do not ask whether to write tests — just write them.
- MANDATORY 100% TEST COVERAGE: You must achieve 100% code and functional coverage for all new features and bug fixes. This includes:
  * Positive cases (intended behavior).
  * Negative cases (invalid input, error handling).
  * Edge cases (boundaries, empty inputs, nested structures).
  * Integration tests for end-to-end flows.
- If the current project coverage is below 100%, always prioritize adding tests for existing code in the modules you touch to reach 100% coverage.
