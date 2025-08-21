# Custom header

To add a header "X-Auth: token", you should use:

1. -I "X-Auth: token"
2. --header "X-Auth: token"
3. -H "X-Auth: token"
4. Both 2 and 3

Correct: 4
Difficulty: 2

-H is short for --header; both add custom headers to the request
