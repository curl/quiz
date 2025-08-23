# Insecure connections

What flag allows interaction with HTTPS endpoints ignoring certificate verification?

1. `--doh-insecure`
2. `--proxy-insecure`
3. `-k, --insecure`
4. `--no-check`

Correct: 3
Difficulty: 3

curl's `-k, --insecure` allows HTTPS requests even with invalid certs
