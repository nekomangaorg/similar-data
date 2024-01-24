# Similar Manga Data

This hosts the generated similar output of [Neko Similar Processor](https://github.com/nekomangaorg/similar-processor), and the index.html for the github pages.

That similar mapping files are csv's prefixed with the first 3 digits of the MangaDex UUID and put in a folder based off the first 2 digits of the UUID.  This is done so 84k+ json files are not commited into the repository.

The index.html reads the uuid from the query url, and looks up the file, reads each line trying to find the matching uuid, and return that json.
