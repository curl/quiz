# HTTP response code only

To retrieve only the response code, you would use:

1. --response-code
2. -w "%{http_code}"
3. --silent --write-out "%{http_code}"
4. Both 2 and 3

Correct: 4
Difficulty: 5

--write-out formats output; used with -s to hide others; %{http_code} gives just the status code
