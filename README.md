# English Greetings

A few greeting snippets I use in [Espanso.org](https://espanso.org/). It's the thought that counts, not the typing ;-)

## Installation

Not yet possible [directly](https://espanso.org/docs/packages/#from-a-repository),
but this works:

```shell
# espanso uninstall greetings-english # In case you want to upgrade
espanso install greetings-english --external  \
    https://github.com/katrinleinweber/espanso-greetings-english
```

## Contributing

MRs are welcome! For major changes, please open an issue first to discuss what you would like to change.

### Development dependencies

Appending the up-to-date list of triggers and espansions requires:

- awk
- Make
- perl
- [jq](https://stedolan.github.io/jq/)
  & [yq](https://mikefarah.gitbook.io/yq/)
  via `asdf install`

## Other useful/noteworthy Espanso packages

- [effective-markdown](https://github.com/katrinleinweber/espanso-effective-markdown)
- [greetings-german](https://github.com/katrinleinweber/espanso-greetings-german)
- [Shruggie](https://hub.espanso.org/packages/shruggie/)

## List of included espansions

Trigger | Espansion
------- | ---------
`,dt` | `Dear {{clipboard}} team,\n\n\n`
`,dms` | `Dear Madam or Sir,\n\n\n`
`,kr` | `Kind regards,`
`!gw` | `and have a good week!`
`!sw` | `and have a good start into the new week!`
`!we` | `and have a nice weekend!`
`!rw` | `and have a nice rest of the week!`
`,tk` | `Thank you & kind regards,`
`!ty` | `Thank you$\|$!`
`:yw` | `You're welcome $\|$:-)`
`&tf` | `& thanks for the feedback `
`&tm` | `& thanks for merging `
`&he` | `& happy Easter!`
`&mc` | `& have a very merry Christmas!`
`&ny` | `& have a happy New Year!`
`&hh` | `& happy holidays!`
