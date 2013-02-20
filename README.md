# Unbound

A wrapper for Unbound in Go.

Unbound's `ub_result` has been extended with an slice of dns.RRs, this alleviates
the need to parse `ub_result.data` yourself.

The website for Unbound is https://unbound.net/, were you can find further documentation.
