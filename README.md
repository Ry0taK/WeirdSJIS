# Weird SJIS
This repository reproduces the issue described in [this issue](https://github.com/ut-issl/c2a-core/pull/119).

# Usage
1. Fork this repository.
2. Clone the forked repository.
3. Open repro.c in the editor that supports Shift-JIS.
4. Add a character (e.g. `a`) to the end of file.
5. Commit/Push changes.
6. Open a pull request against this repository.
7. Wait for CI to be finished.
8. Open `Files changed` tab in the pull request.
9. You'll see the internal server error page.

