## 2024-07-01 - Add ARIA label to audio toggle
**Learning:** Found an icon-only button controlling audio without labels or accessible name. Icon-only buttons handling background sound are easy to miss but crucial for users with screen readers.
**Action:** Always add an `aria-label` and `title` to audio/visual control elements to ensure state changes (e.g. Play/Pause) are announced correctly.
