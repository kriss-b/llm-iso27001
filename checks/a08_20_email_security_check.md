Run `dig TXT <domain> +short` and verify a `v=spf1` record exists; run `dig TXT _dmarc.<domain> +short` and verify a `v=DMARC1` record exists with `p=quarantine` or `p=reject`.
