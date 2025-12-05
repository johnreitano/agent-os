Implement all tasks assigned to you and ONLY those task(s) that have been assigned to you.

## Implementation process:

1. Analyze the provided spec.md, requirements.md, and visuals (if any)
2. Analyze patterns in the codebase according to its built-in workflow
3. IF your task involves user-facing UI, and IF any of the views and UI elements that you will be modifying already exist, and IF you have access to a browser testing tool (such as the Playwright MCP server), THEN, using this browser testing tool, use all of these pre-existing views and/or UI elements as if you are a user to capture their visual appearance BEFORE your change.
  - Take before-change screenshots of these views and UI elements you will be modifying and store those in `agent-os/specs/[this-spec]/verification/screenshots/before-change/`. Do not store these before-change screenshots anywhere else in the codebase other than this location.
4. Implement the assigned task group according to requirements and standards
5. Update `agent-os/specs/[this-spec]/tasks.md` to update the tasks you've implemented to mark that as done by updating their checkbox to checked state: `- [x]`

## Guide your implementation using:
- **The existing patterns** that you've found and analyzed in the codebase.
- **Specific notes provided in requirements.md, spec.md AND/OR tasks.md**
- **Visuals provided (if any)** which would be located in `agent-os/specs/[this-spec]/planning/visuals/`
- **User Standards & Preferences** which are defined below.

## Self-verify and test your work by:
- Running ONLY the tests you've written (if any) and ensuring those tests pass.
- Making sure that there are no linting/formatting errors.
- IF your task involves user-facing UI, and IF you have access to a browser testing tool (such as the Playwright MCP server), THEN using this browser testing tool, use the feature you've implemented as if you are a user to ensure a user can use the feature in the intended way.
  - Take after-change screenshots of the views and UI elements you've modified and store those in `agent-os/specs/[this-spec]/verification/screenshots/after-change/`.  Do not store these after-change screenshots anywhere else in the codebase other than this location.
  - Analyze the after-change screenshot(s) you've taken to check them against your current requirements. Also, check the after-change screenshot(s) against any corresponding before-change screenshots if they exist.
