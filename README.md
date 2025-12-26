# ClickBind Releases

Customize your mouse's extra buttons on macOS.

## Download

👉 [Download Latest Version](https://github.com/clickbind-app/clickbind-releases/releases/latest)

## Auto Update

ClickBind supports automatic updates.
Menu → Check for Updates

## Links

- [Website](https://clickbind.app)

## FAQ

### Mouse Compatibility Notice

Some gaming mice do not expose extra button events to macOS.

- **Check product compatibility**: If the product description mentions "Mac OS for normal using" or "Windows for programmable buttons," the mouse likely only sends basic click/scroll events to macOS, and ClickBind cannot detect additional buttons.
- **How to verify**: Enable "Detect Button" mode in ClickBind and press your mouse button. If nothing is detected, the mouse doesn't send that button event to macOS.
- **Tip**: Look for mice that explicitly support "macOS programmable buttons" or have official macOS driver support for full compatibility.

### Why ClickBind Is Not Available on the Mac App Store

ClickBind provides system-wide mouse input control on macOS. Because this functionality is not compatible with Mac App Store sandboxing and permission restrictions, ClickBind is distributed directly using Apple Developer ID signing and notarization to ensure full functionality.

This ensures ClickBind is safe and follows Apple's guidelines. ClickBind uses only Apple's official public APIs.

### Permission Usage

ClickBind requires macOS Accessibility and Automation permissions for the following purposes:

**Accessibility**

- Detecting mouse button inputs
- Remapping mouse buttons based on user configuration

**Automation**

- Executing system commands (Mission Control, Show Desktop, etc.)
- Running AppleScript files (.scpt)

Automation permission is only required when using these features. You will be prompted by macOS the first time you use them.

These permissions are used strictly for input handling and automation purposes only. ClickBind does not log keystrokes, store input data, or transmit any data externally.

#### What happens if I deny a permission?

ClickBind will still run normally. Only the features that require the denied permission will be disabled.

#### How do I grant or revoke permissions?

Go to System Settings → Privacy & Security → Accessibility (or Automation) to manage permissions for ClickBind.

### Privacy & Data Collection

ClickBind does not collect:

- User accounts
- Personal information
- Keystroke data
- Usage or behavioral data

For license verification, ClickBind sends:

- Device identifier (hashed hardware UUID, not personally identifiable)
- License key
- Last verified timestamp
- Server signature (cryptographic signature for local tamper detection)

This data is used only to validate the license. No input data or user activity is stored or sent to external servers.

ClickBind operates entirely locally on your Mac, except for license verification.

### Lost License Key

If you lost your license key, please contact us at beomjunk.dev@gmail.com with the email address you used during purchase. We'll verify your purchase and resend the license key.

### Refund Policy

We offer a full refund within 14 days of purchase, no questions asked. Please contact us at beomjunk.dev@gmail.com with the email address you used during purchase.

### System Requirements

macOS 14.0 (Sonoma) or later

### How to Uninstall

1. Quit ClickBind
2. Move ClickBind.app to Trash
3. Optionally, revoke permissions in System Settings → Privacy & Security
