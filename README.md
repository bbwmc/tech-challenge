# tech-challenge

Use an NPM package like [json-server](https://www.npmjs.com/package/json-server) to get db.json running as a mock rest API.

Assume that these 5 reviews have just landed in the database. Non of them are live yet. Using Node or PHP, write a script that goes through each review and scans it for the bad words in the words array.

If a review matches a bad word, it should not go live and a message should be sent to a Slack channel (e.g. #bad-reviews). Feel free to use a standard Slack package like [slack-node-sdk](https://www.npmjs.com/package/slack-node) or [maknz/slack](https://packagist.org/packages/maknz/slack).

If a review passes the test, the `live` field should be updated to `true`.

Reviews with IDs 1 and 4 should pass the test and go live. The others should fail.

Good luck!
