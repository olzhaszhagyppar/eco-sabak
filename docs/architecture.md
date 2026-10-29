# Architecture

Eco-sabak is a Moodle-based site hosted on an Ubuntu VPS. Nginx serves Moodle through PHP-FPM, with MariaDB storing course and account records. Moodle's uploaded files are stored in a separate private data directory.

The custom homepage and lesson HTML is managed through Moodle's editor, so it is stored in the Moodle database. Files in this repository are reference copies of the customizations, not a deployable Moodle distribution.

Never commit `config.php`, private `moodledata`, database exports, or user information.
