# Playwright focus proof

CI proof for the proposed Playwright changes that keep the MCP tool and its browser extension from taking the user's tab or window. The workflow builds upstream `microsoft/playwright` main and the branches in `ourostack/playwright`, runs a person-and-two-agents scenario in visible browsers on GitHub's macOS and Windows runners, and runs each pull request's extension tests, including on the code before each change.

The proof scripts are in `proof/`. Nothing here runs on a person's machine.
