# Kombucha

This repository serves as the place to fetch customized Wine builds for Vinegar.

These Wine builds are patched to fix numerous issues with Roblox Studio that are
otherwise non-existent on Windows. Some of these issues are caused by Wine itself,
while others are bugs specific to a desktop environment or display server.

At the time of writing this, Kombucha comes in four different flavors:
* stable
* unstable
* proton-stable
* proton-unstable

"stable" builds of Kombucha are based on stable/development releases of Wine. These
builds are intended for use in production.

"unstable" builds of Kombucha are based on the latest commit of Wine and are updated
more frequently. They may also include experimental patches, so caution is advised
when using in production.

Builds of Kombucha labeled under "proton-stable" are based on the bleeding-edge
branch present in the Wine fork used in Proton. Compared to "stable" and "unstable",
it includes changes specifically intended to improve the user experience of running
non-native Steam games, which may also benefit Roblox Studio. These builds are also
intended for use in production.

Builds of Kombucha labeled under "proton-unstable" are updated more frequently and
may include experimental patches, similar to "unstable". Caution is advised when
using in production.

As of 2026-09-14, Vinegar defaults to using "proton-stable" builds. Users may need
to update their Wine installation to "Latest" from Vinegar's settings in order for
this change to apply.
