# Broom

Free disk visualiser and cleaner. One small download, no installer, no accounts, no telemetry. Everything Broom removes goes to your system Bin, never permanent deletion.

The one part that is not local is **Ask Broom**, the optional assistant on the Home screen. Turn it on and your question plus a summary of the scan (folder and file names, paths and sizes, never the contents of any file) is sent to Broom's service to be answered. Everything else, including every scan and every removal, happens entirely on your machine.

**Try it in your browser first:** https://broom.ste-hosea.workers.dev

## Downloads

Grab the latest release from the [Releases page](https://github.com/RexStev/broom-releases/releases).

- **macOS**: `Broom-mac.zip`. Unzip, drag Broom to Applications, double-click. First run only: macOS says it cannot verify the app (builds are not yet Apple-notarized). Choose Done, then open System Settings, Privacy & Security, scroll down and press Open Anyway. macOS never asks again.
- **Linux**: `broom-<version>-linux-<arch>.tar.gz`. One binary: `tar -xzf` and run `./broom`, then open http://localhost:4177.
- **Windows**: `broom-<version>-windows-amd64.zip`. Early build. Unzip and run `broom.exe`, then open http://localhost:4177.
- **macOS terminal build**: `broom-<version>-darwin-<arch>.tar.gz`. Advanced: the bare engine binary, not an app.

Verify any download against `SHA256SUMS.txt` in the same release.

## What it does

Space map, junk cleaner with 100+ per-OS rules, node_modules finder, duplicate hunter, empty-folder sweep, large-and-old files with safety verdicts, startup manager, adware scan, privacy check, app uninstaller with leftovers, scan diffing, guardian mode and APFS clone-merge. Cleaning is two-phase (analyze first, always to the Bin) with protected system paths refused server-side.

This repository hosts release binaries only.
