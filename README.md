# mta-sts

Serves the MTA-STS policy for corpora.inc mail (RFC 8461) at https://mta-sts.corpora.inc/.well-known/mta-sts.txt. Change `mode` to `enforce` only after TLS reports are clean, and bump the id in the `_mta-sts.corpora.inc` TXT record on every policy change.
