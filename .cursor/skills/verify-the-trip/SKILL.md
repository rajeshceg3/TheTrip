# Verify TheTrip
The Trip - A Northern Odyssey: static map journey.
## Launch
Any static file server from the repo root.
## Doctor
`python3 .cursor/skills/verify-the-trip/verify.py`
## Drive
Serves the static site and renders it in headless Chromium asserting the boot marker, map container, and zero JS console errors.
## Evidence
`.cursor/skills/verify-the-trip/evidence.json`
## Cleanup
Static server terminated after the render.
## Known boundaries
Render smoke only; scene quality and e2e suites not exercised here.
