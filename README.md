# Translations for MicrBloodID app
To load this repository in either backend or app repos run
`git submodule init`
and
`git submodule update --init`

If this doesn't work please try
`git submodule sync`
and repeat the update command

# Translation format
The translation format is
```{
translation:
  {
   key: "translation for key",
  }
}
```

in files named "2 letter language code".json,
for example *en.json* for English, or *pl.json* for Polish

# Translation formatting
If adding new translations please make a new section for each domain of translation, separated by newlines. A new domain might be a database table, a frontend screen, or something like that. This will help keep the translations more readable.
