# Translations for MicrBloodID app
To load this repository in either backend or app repos run
`git submodules init`
and
`git submodules update --init`

If this doesn't work please try
`git submodules sync`
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
