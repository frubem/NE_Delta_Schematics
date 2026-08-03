# Modified ROMs

## 60Hz mod

`EP780A_60hz.BIN` is the same as the original DELTA EP780A, except that it has the CRTC initialization routine modified to generate a 60Hz picture

## //e enhanced ROMs

`EP780A_IIe_enhanced_60Hz.BIN` and `EP780B_IIe_enhanced.BIN` are Apple //e Enhanced ROMs, modified to include the CRTC initialization code.

Note that:
- The VIDEO ROM with additional character has not (yet?) been ported to the DELTA
- The selftest fails during RAM check. It possibly needs patching. Note that it also fails with the original Delta ROMs so the designers probably did not care to fix this either.

