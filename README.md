# Concision

Concision is a wiki-like engine, but with several features that make it different from other wikis.

All data is saved to files. Distribution is done using dropbox or git (which would also do versioning). The web server runs locally, but it is just an API serving content to a web client. Editing is done in your web browser, or using an editor on your localhost.

There is a single hierarchy to provide basic structure, further hierarchy is provided by tagging. Short entries are encouraged, with threads being used where a narrative is most appropriate. Fast, accurate and usable search is expected to be the primary navigation method.

Content is formatted using markdown. The actual data written to file in markdown with YAML front matter (in a form that displays well on github).

The meta data can be extended, so additional information can be added when it makes sense (eg coordinates, review-by dates, other stuff).
