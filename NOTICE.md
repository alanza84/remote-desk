# Notice

This repository is **Remote Desk**, a branded and pre-configured fork of
[RustDesk](https://github.com/rustdesk/rustdesk) for a private rendezvous/relay
and API server. It is not affiliated with, endorsed by, or supported by
RustDesk or Purslane Tech Pte. Ltd.

## License

The original RustDesk client is licensed under the GNU Affero General Public
License, version 3. This fork is distributed under the same license. The full
text is in `LICENCE`. Copyright notices in the original source files are
preserved.

"Powered by RustDesk" attribution in the UI is also preserved: RustDesk already
excludes that string from the app-name substitution.

## What changed

Customer-facing branding (app name, window/tray/taskbar labels, Android and iOS
display names, and bundle/application identifiers so this app can be installed
alongside official RustDesk) and compile-time server settings in
`libs/hbb_common/src/config.rs`. The remote-control protocol and security model
are unchanged.

If you want the official RustDesk client, get it from
https://github.com/rustdesk/rustdesk.
