# Memory migrated in-tree

This project's auto-memory was migrated in-tree by `/gitlore:install`. It now
lives in the `gitlore-memory` submodule, versioned in git alongside the code.

Do not add memory here. Launch Claude Code through the gitlore `claude` shim so
memory is redirected into the submodule. New files appearing in this directory
mean a session was started without the launcher — see the gitlore SessionStart
warning for how to activate it.
