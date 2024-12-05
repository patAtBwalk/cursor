# AI Instructions

# VS 2022 Git Commit Instructions
To Edit:
1. Open VS 2022
2. Navigate: Tools > Options > Github > Copilot
3. Copy instructions below
4. Paste into "Commit message custom instructions"

```
Choose the type based on changes from this list:
docs: Documentation-only changes
feat: Introduces a new feature to the codebase
fix: Patches a bug in the codebase
perf: Improves performance
refactor: Code changes that neither fix a bug nor add a feature
revert: Reverts a previous commit
style: Changes that do not affect the meaning of the code (white-space, formatting, etc.)
test: Adds missing tests or corrects existing tests

The first line should start with a hash symbol followed by a work item id and then contain the type and simple summary of changes, with no more than 50 characters.
The second line should be empty.
Start the full summary on the third line.

Example:
#1234 feat: Add user authentication feature

Implement user authentication using JWT tokens:
- Create login and registration endpoints
- Add password hashing and validation
- Integrate JWT token generation and verification
```
