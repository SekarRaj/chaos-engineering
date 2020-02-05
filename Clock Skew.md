# Clock Skew

Why do we have to check for clock skew in Chaos engineering.

* In most unique identifiers generation, current time is used in some form. Different clock time in nodes responsible for the ID generation may introduce collition identifier.

* Couchbase conflict resolution(time-stamp based) uses the timestamp associated with the document to determine which document is the most recent. 

