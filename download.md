# Download

Download the file from `https://example.com/file` to a local file name as the
file part of the URL.

1. `curl -I https://example.com/file`
2. `curl -O https://example.com/file`
3. `curl -o https://example.com/file`
4. `curl -T https://example.com/file`

Correct: 2
Difficulty: 1

`-O` has the long name version `--remote-name`. It saves the file using the file
part from the URL provided on the command line.
