# wpsalt

tiny curl wrapper to generate salt for wp-config.php from api.wordpress.org

Runs `curl -s https://api.wordpress.org/secret-key/1.1/salt/`

The main reason why I keep this in a shell script and not an alias for example
is so that I can use its output directly in vim via `:r !wpsalt` when editing
a `wp-config.php` file.

## Installation

If you don’t know how to make a shell script executable and put it some place
useful, you probably don’t need this :)

