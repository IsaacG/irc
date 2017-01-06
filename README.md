# irc
All sorts of IRC related coding

* nicktracker
 * Little experiment used to track people on IRC as they change nicks.
 * Parses my irssi IRC logs.
 * Stores nick changes and hosts associated with nicks to a SQLite DB.
 * Allows updating the DB with new logs.
 * Allows querying the DB for all the nicks associated with a given nick.
 * Uses ~/.nicktracker.rc to define $db $irclogdir and $ignorenick
 * Built on awk, bash and sqlite in about 1.5 hours.
