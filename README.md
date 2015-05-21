# Moodle authentication plugin for Odoo
This plugin let your users to login to Moodle using their login and passwords from Odoo.
Basic personal info (like names and e-mail addresses) is also imported.

## Configuration
Place the "odoo" directory inside the "auth" directory of your Moodle instalation. Login as admin.
Moodle should automatically detect the new plugin.
Go to Site "Administration" / "Plugins" / "Authentication" / "Odoo login and password integration" to provide
plugin with information about your Moodle instalation. You should probably also blok users from editing fields that
are automatically imported from Odoo. You are all set.
