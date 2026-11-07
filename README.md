<!-- ourostack:brand:start -->
<p align="center">
  <a href="https://github.com/ourostack"><img src="https://raw.githubusercontent.com/ourostack/.github/main/brand/headers/playwright-focus-proof.webp" alt="A person working on a laptop in an armchair beside two robots at their own table and laptops, with Ouro watching" width="100%"></a>
</p>
<!-- ourostack:brand:end -->

# Playwright focus proof

**Labs:** CI proof for our Playwright changes that stop the MCP extension from taking a person's tab or window. Tried in the open, not supported.

[The fork: ourostack/playwright](https://github.com/ourostack/playwright) · [Proof runs](https://github.com/ourostack/playwright-focus-proof/actions) · [`proof/`](proof/) · [More from Ouro](https://github.com/ourostack)

CI proof for the proposed Playwright changes that keep the MCP tool and its browser extension from taking the user's tab or window. The workflow builds upstream `microsoft/playwright` main and the branches in `ourostack/playwright`, runs a person-and-two-agents scenario in visible browsers on GitHub's macOS and Windows runners, and runs each pull request's extension tests, including on the code before each change.

The proof scripts are in `proof/`. Nothing here runs on a person's machine.
