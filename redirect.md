# Redirect

If the URL `https://example.com/a` redirects to `https://example.com/b`, and
we issue the command line `curl -LO https://example.com/a`. Which local file
name will the content be saved in?

1. a
2. b
3. none
4. example.com/a

Correct: 1
Difficulty: 1

The local name is decided by the file name part of the initial URL.
