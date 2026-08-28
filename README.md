# froom-endpoint

Public pointer to the current FROOM API base URL. The Raspberry Pi demo server republishes endpoint.json whenever its Cloudflare quick-tunnel hostname changes; the FROOM app reads the raw file at startup to discover the live endpoint.
