# 🔍 Browser Extension Security Audit - Microsoft Edge

## 🧑‍💻 Internship Task - Cybersecurity Extension Analysis

### 📅 Date: [Insert Date]

### 🔐 Objective
To audit installed browser extensions for potential security risks, improve browser performance, and learn how extensions can be used maliciously.

---

## 📄 Installed Extensions

1. **Volume Booster - Increase your sound**
   - ⚠️ Risk Level: Medium
   - 🔎 Notes: Allows control over tab audio; may request high-level access to media.
   - ✅ Action: Marked for review or removal based on necessity.

2. **Google Docs Offline**
   - ✅ Risk Level: Low
   - 🔒 Notes: Pre-installed by Google; used for offline editing of Docs.
   - ✅ Action: Kept (Safe and required by system).

---

## 🧹 Actions Taken

- Reviewed all installed extensions on Microsoft Edge via `edge://extensions`.
- Checked permissions and verified source for each extension.
- No highly suspicious extensions found.
- Volume Booster flagged for potential unnecessary permission usage.
- Restarted browser to observe performance changes.

---

## 📚 Learnings

- Malicious extensions can:
  - Steal data through over-permissioning.
  - Inject malicious scripts or redirect users.
  - Record browser activity or keystrokes.

- Always:
  - Install extensions from trusted sources (Chrome/Edge Web Store).
  - Review permissions carefully.
  - Remove unused extensions to reduce attack surface.

---

## 🖼️ Screenshots (Attach Separately)
- Screenshot 1: `edge://extensions` showing installed extensions.
- Screenshot 2: Extension "Details" page for Volume Booster.
- Screenshot 3: Permissions or source review.
