# Oppgave 2

Denne oppgaven tar utgangspunkt i et eksempel-repo. Fork repoet før du begynner: https://github.com/fredva/eksempelrepo-1

### Opprette pull request

Opprett en pull request fra branchen `feature1` til `master`. Du vil se på pull requesten at branchen har konflikter med `master`. Disse må løses før du kan merge.

### Løse konflikter med merge
Løs konfliktene ved å merge `master` inn i `feature1` lokalt på egen maskin. Push endringene når du er ferdig. Til slutt merger du pull requesten på GitHub.

### Løse konflikter med rebase
Opprett en ny pull request, denne gangen fra `feature2` til `master`. Denne branchen har også konflikter som må løses før merging.

Løs konfliktene ved å rebase `feature2` på `master`. Dette gjør du på følgende vis:

```
> git checkout feature2
> git rebase master
Løs konfliktene etterhvert som de oppstår
> git push --force
```

Legg merke til at vi må gjøre en såkalt _"force push"_ for å kunne pushe den rebasede branchen vår.

Merge pull requesten fra GitHub.

## Bonusoppgave

Installer [`hub`](https://github.com/github/hub), og bruk verktøyey for å opprette en pull request.
