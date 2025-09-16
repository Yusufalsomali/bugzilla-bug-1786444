# Bugzilla Report: 1786444

**Title:** TypeError: tab is undefined — getSourceTabs crash when debugging WebExtension  
**Product/Component:** DevTools → Debugger  
**Version:** Firefox 103  
**Status at capture:** UNCONFIRMED  
**Type:** Defect  
**Priority/Severity:** P2 / S3

## Source
- Mozilla Bugzilla: https://bugzilla.mozilla.org/show_bug.cgi?id=1786444

## Files in this repo
- `bug-1786444.pdf` (print-to-PDF capture of the full report)  
  _or_ `bug-1786444.html` (HTML export)  
  _or_ `bug-1786444.xml` (raw XML export)

## Notes
Reporter observed a crash in DevTools Debugger after reloading a WebExtension via `about:debugging` and switching to its tab. Error in stack trace: **TypeError: tab is undefined**.
