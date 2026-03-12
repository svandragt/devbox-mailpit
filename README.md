[Mailpit](https://mailpit.axllent.org/) is a small, fast, low memory, zero-dependency, multi-platform email testing tool & API for developers.

It acts as an SMTP server, provides a modern web interface to view & test captured emails, and contains an API for automated integration testing ([read more](https://mailpit.axllent.org/about/)).
 
 To install a github hosted plugin, add the following to the include section of your `devbox.json` Default - master branch:
```json
    "packages": [
        "mailpit@latest"
    ],
    "include": [
        "github:svandragt/devbox-mailpit"
    ]
```
Followed by `devbox services up`. Mailpit will be enabled on http://localhost:8025/

## More information

 - https://www.jetify.com/docs/devbox/guides/plugins/index
