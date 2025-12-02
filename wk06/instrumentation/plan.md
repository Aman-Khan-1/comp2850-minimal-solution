# Instrumentation Plan - Week 6

**Purpose**: Capture objective metrics for Week 9 task-based pilots and Week 10 analysis.

---

## Events to Log

### 1. voice_navigation_used
**Trigger**: NAV / app
**Fields**:
- 'ts_iso':ISO 8601 timestamp (e.g., 2025-01-15T14:23:45Z)
- 'session_id':Anonymous 6-char hex(e.g., P1_a3f7)
- 'request_id': Unique per navigation attempt (for tracing)
- 'nav_method': icon | voice (how navigation was attempted)
- 'icon_size': Pixel size of the icon (e.g. 48px)
- 'command_text': Raw voice command
- 'destination_id':Identifier of the target screen/page
- 'http_status': 200 (success) | 400 (validation error)
- 'js_mode': 'js-on' | 'js-off'

**Why**: Measure navigation success and error rates, compare JS vs no-JS

---

### 2. 





