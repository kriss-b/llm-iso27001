Run `openssl s_client -connect <domain>:443 </dev/null 2>/dev/null | openssl x509 -noout -dates`; check passes if the certificate has not expired and is not expiring within 60 days.
