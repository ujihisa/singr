## singrd

starts the singr daemon to keep connections.

    $ singrd -u {username} {address} &

## singr

plumbing commands to say/listen messages.

    $ singr listen
    ("ujihisa","hello!")
    ("ujihisa","how are you?")

    $ echo "I'm fine!" | singr say
