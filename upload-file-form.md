# Upload file via form POST

Which form of curl request uploads "file.txt" as form-data key "file"?

1. `-F file=@file.txt`
2. `--form file=file.txt`
3. `-d file=@file.txt`
4. `-X POST --upload file.txt`

Correct: 1
Difficulty: 4

Use `-F name=@filename` to send multipart/form-data with files
