# GClean
gmail cleaner app written in go

gclean [command] [flags] [args]

something like:
gclean list -v 1y now
verbosely emails from 1year ago til now



will probably need
- login or some way to get/pass token
- list that user can use to test and verify query results
    - different display styles
        - count
        - from/subject date
        - full? 
- query params that can include different ways to filter emails 
    - tags
    - priority?
    - inbox vs other?
    - subject includes words
    - sender
    - read/unread
- clean command that executes
    - optionally limit the amount?



[cobra for cli framework](https://github.com/spf13/cobra)