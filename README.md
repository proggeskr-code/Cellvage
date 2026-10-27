# Cellvage

Scan and verify Cellvage battery passports.

- `index.html`: the Cellvage phone app (scan a passport QR, verify its signature on the phone, keep it in My batteries)
- `passport.html`: the stand-alone passport page
- `prototype.html`: the selling-flow prototype screens (sample data)

A passport lives entirely inside its QR link (after the `#`), so it is never sent to the server; the phone checks the rig's ECDSA P-256 signature itself.
