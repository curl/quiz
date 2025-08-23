# HTTP method override

Which flag can be used to override the HTTP method used by curl?

1. `--request <method>`
2. `--method <method>`
3. `-X, --request <method>`
4. `--override <method>`

Correct: 3
Difficulty: 2

curl supports overriding HTTP methods via `-X, --request <method>`, e.g., `-X PUT`, `-X DELETE`; default is based on presence of data or headers
