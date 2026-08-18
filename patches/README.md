# NS Browser patches

Put Chromium-compatible `git format-patch` output here.

Example:

    patches/ns-browser.patch

The GitHub Action runs `git apply --check` before applying the patch so an
upstream Chromium update fails cleanly instead of producing a silently broken
build.

Features such as ad blocking, custom filtering, DoH UI/configuration, package
branding, and translation integration should be implemented as versioned
Chromium patches rather than editing the downloaded source blindly.
