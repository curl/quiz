# Insecure connections

What flag allows interaction with HTTPS endpoints ignoring certificate verification?

1. `--no-check`
2. `--skip-ssl`
3. `--insecure`
4. `-k`

Correct: 3
Difficulty: 3

curl's `--insecure` (aka `-k`) allows HTTPS requests even with invalid certs
