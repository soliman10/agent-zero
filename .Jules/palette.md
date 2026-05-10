## 2024-05-10 - Accessibility Check
**Learning:** Found an interaction improvement: the "View Notifications" toggle in `webui/components/notifications/notification-icons.html` is missing `role="button"` and `tabindex="0"`, and needs a keyboard interaction handler (e.g. `@keydown.enter` / `@keydown.space`) for accessibility.
**Action:** Enhance the notification toggle `div` with accessibility attributes and keyboard support so screen readers and keyboard users can activate it.
