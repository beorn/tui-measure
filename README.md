# ⚠️ DEPRECATED

**This package has been deprecated.** Its functionality has been merged into [inkx](https://github.com/beorn/inkx).

## Migration

If you were using `@beorn/tui-measure`, migrate to `inkx`:

```typescript
// Before (tui-measure)
import { wrapText, truncateText, constrainText, displayLength } from "@beorn/tui-measure"

// After (inkx)
import { wrapText, truncateText, constrainText, displayWidth } from "inkx"
// Note: displayLength is now displayWidth
```

For constraint components (`ConstraintRoot`, `FlexRow`, `ScrollableList`), these are now part of application code rather than a shared library. See the [km-tui layout module](https://github.com/beorn/km/tree/main/apps/km-tui/src/layout) for an example implementation.

## Original Description

Terminal UI text measurement utilities - ANSI-aware text wrapping, truncation, and constraint-based layout components for React terminal applications.

---

*This repository is archived and no longer maintained.*
