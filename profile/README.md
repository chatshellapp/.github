# ChatShell

Give any AI model, cloud or local, web search, file access, and a shell on your desktop, with nothing extra to set up.

Plan a trip, compare purchases, prepare a shopping list, or organize your files. Connect a cloud AI provider or a local model, and choose when tool actions need your approval.

**[Download ChatShell](https://github.com/chatshellapp/chatshell-desktop/releases/latest)** · [Documentation](https://chatshell.app/docs?utm_source=github&utm_medium=org-profile&utm_campaign=profile-readme)

Free and open source under Apache 2.0, for macOS, Windows, and Linux. Latest release: v0.8.3 (October 2026).

## Start here

**[chatshell-desktop](https://github.com/chatshellapp/chatshell-desktop)** is the app: screenshots, install steps, and how to contribute.

[chatshell-agent](https://github.com/chatshellapp/chatshell-agent) is the shared Rust agent core behind the desktop app and the iPhone app now in development.

## For teams evaluating ChatShell

- **Maintainer:** built and maintained by Sean Wong at Seedvector LLC. It is a single-maintainer project today.
- **Cost:** no paid tier, no per-seat pricing, no account required.
- **Data:** no telemetry by default. API keys are encrypted with AES-256-GCM, and the master key is kept in the OS keychain. Updates are signature-verified.
- **Defaults to know:** tools run without asking (Yolo mode) unless you switch a conversation to Ask mode.
- **Not yet:** the Windows installer is not code-signed, and there are no admin or MDM controls. The macOS build is signed and notarized.
- **Security:** see the [security policy](https://github.com/chatshellapp/chatshell-desktop/security/policy). Reports go through private vulnerability reporting, the first response comes within a week, and fixes ship for the latest version only.

<!-- Profile owner: Sean. Review triggers: each minor release, iPhone app launch, Windows signing, a second maintainer, any pricing change. Last reviewed: 2026-10-30. -->
