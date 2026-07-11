# Security Policy

This is the organization-wide default policy; it applies to every CatchFleet
repository, including the Listener release builds.

Please **do not open a public issue** for security problems. Use GitHub's
private vulnerability reporting on the
[catchfleet repository](https://github.com/catchfleet/catchfleet/security/advisories/new).

In scope: the game at [playcatchfleet.com](https://playcatchfleet.com)
(accounts, helper keys, the device-link flow, the observation apply
pipeline) and the Listener release builds. Note that "I can fake my own
sightings with a custom client" is a known limitation of the Alfa;
server-side anti-spoofing is on the roadmap. Novel integrity bypasses
(auth, key handling, cross-user effects) are very welcome reports.
