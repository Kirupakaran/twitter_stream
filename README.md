# twitter_stream
A twitter stream which easily allows the user to gather tweets relating to a specific event or hashtag. Supports functionality to write to a csv or upload directly to a Postgres database.

Just pass a command line option.

-q specifies the query. 'cubs' will filter out all tweets other than tweets related to either bear cubs or the Chicago cubs. 'cubs, portland' will filter out all tweets other than the two given terms.

Access Twitters' developer API here: https://dev.twitter.com/
You'll need application and developer keys.
