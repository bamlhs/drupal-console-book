# generate:plugin:mail
Generate a plugin mail

**Usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--services | Szolgáltatások betöltése a tárolóból.

## Examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
