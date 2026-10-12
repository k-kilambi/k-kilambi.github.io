# Portfolio change log

## Repository copy

- Kept both `k-kilambi.github.io.OLD` and `k-kilambi.github.io`, as requested.
- Copied the site's files, three branches, and six-commit history into the new repository.
- Verified that the branch file trees match the originals. Recreated commits have new IDs; original IDs, signatures, and PR records remain in `.OLD`.
- The previously merged LinkedIn button change is included in the new repository's `main`.
- Recreated the open Fermat experience update as PR #1 in the new repository, with a link back to the original PR #2 in `.OLD`.
- GitHub Pages serves the live site from the new repository's `main` branch at `https://k-kilambi.github.io/`.

## Experience update and publication delay

- The user merged the recreated experience PR into the new repository's `main` branch.
- The Work Experience page now includes Product Go-to-Market at Fermat, June 2026–Present.
- MBA Candidate starts in 2025, and Launch Factory ends in 2025.
- Immediately after the merge, a website refresh did not show the update. The user subsequently confirmed that it appeared without any further changes.
- This was consistent with a short GitHub Pages rebuild or serving delay; no deployment fix was needed.

## Homepage links — proposed in this PR

**Goal:** Make the homepage actions more consistent and use the recognizable LinkedIn logo instead of a text button.

- Style “A little about me” as a button matching “Explore my work,” while keeping its About-page destination.
- Replace the “View LinkedIn” text button with a clickable LinkedIn logo.
- Preserve the LinkedIn profile URL, new-tab behavior, and safe external-link attributes.
- Give the icon link an accessible name, a tooltip, a keyboard focus indicator, and a generous click target.
- Exclude this change log from the public Jekyll output.
- These homepage changes remain subject to manual PR review and merge on GitHub.
