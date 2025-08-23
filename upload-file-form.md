# Upload file via form POST

Which form of curl request uploads "file.txt" as form-data key "file"?

1. `-F, --form file=@file.txt`
2. `--form-string file=file.txt`
3. `-d, --data file=@file.txt`
4. `-T, --upload-file file.txt`

Correct: 1
Difficulty: 4

Use `-F, --form name=@filename` to send multipart/form-data with files
