# Bug Reports – Portfolio Site

## 🐞 Bug 001 – Contact form submits with blank name
- **Severity**: Medium
- **Steps**:
  1. Leave name field empty
  2. Fill in email and message
  3. Submit form
- **Expected**: Name is required
- **Actual**: Form submits without error
- **Status**: Open

---

## 🐞 Bug 002 – Navbar overlaps hero text on small screens
- **Severity**: Low
- **Steps**:
  1. Resize browser to iPhone SE width
  2. Observe navbar positioning
- **Expected**: Hero section content visible
- **Actual**: Navbar overlaps intro text
- **Status**: Fixed in v1.1

---

## 🐞 Bug 003 – Project links don't open in new tab
- **Severity**: Low
- **Steps**:
  1. Click a GitHub or Live Demo link
- **Expected**: Opens in a new tab
- **Actual**: Replaces current tab
- **Fix**: Add `target="_blank"` to `<a>` tag
- **Status**: To be fixed 
