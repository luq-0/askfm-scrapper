# askfm-scrapper
Proof-of-concept. Nothing is private, especially not publicly published data.

Give it a username, and it will download all questions/answers/likes/authors in a file. Convinient for Ctrl+F. Read comments for more detailed instructions.


Known issues:
- Single-threaded. I don't own a high-end PC, and I like to do something else while scrapping random strangers' data.
- Might fail to record a question or two. Very minor, however
- Might fail to properly format question/answer, resulting in text artifacts
- Letters in non-English alphabet won't be encoded properly in filenames on Windows
- Might fail to work in many other ways at any moment, but that doesn't happen. Okay, very rarely, for very edge-y cases.
