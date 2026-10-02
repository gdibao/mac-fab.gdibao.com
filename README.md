# Chituo AI macOS Build Runner

This public repository contains only the macOS release workflow for Chituo AI.
The product source remains in the private `gdibao/fab.gdibao.com` repository.

The workflow is manual-only. It checks out an immutable private tag with a
read-only deploy key, verifies the requested commit, builds Intel and Apple Silicon
packages, and uploads only DMG/ZIP artifacts. Product source is never committed
to this repository.
