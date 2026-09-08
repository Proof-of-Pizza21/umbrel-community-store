# Landing Archive Community Store

## Identità permanente

Per questo repository usare esclusivamente:

- Git author/committer name e account GitHub: `Proof-of-Pizza21`.
- Git author/committer email: `259956083+Proof-of-Pizza21@users.noreply.github.com`.

Questa istruzione sostituisce qualsiasi identità diversa ereditata dalla directory
superiore o dalla configurazione globale. Prima di commit, tag e pubblicazioni
verificare la configurazione Git locale e l'identità effettiva di autore e
committer. Prima di pubblicare verificare anche l'account GitHub autenticato.
Non modificare chiavi di firma senza verificarne l'appartenenza all'account.

## Privacy

Il nome e il cognome reali dell'utente non devono comparire in file, percorsi
versionati, metadati, commit, tag, release o artefatti. L'unica identità pubblica
consentita è quella indicata sopra. Prima di ogni push controllare file nascosti,
contenuto selezionato e tutta la cronologia da pubblicare.

Non includere URL personali di collaudo, archivi di siti, credenziali, log,
percorsi locali o dati del dispositivo. La directory dati del pacchetto contiene
soltanto `.gitkeep`; i dati creati durante l'uso restano sul dispositivo Umbrel.

## Pacchetto

L'identificatore dello store è `proof-of-pizza21`; quello dell'app è
`proof-of-pizza21-landing-archive`. Mantenerli stabili dopo la prima installazione.
La prima anteprima è per `linux/amd64`, destinata al collaudo su umbrelOS 1.7.4.
Usare soltanto immagini pubblicate e provate con digest verificato. Non dichiarare
eseguiti test sul dispositivo se non sono stati realmente completati.

Conservare `LICENSE-PLAYWRIGHT` insieme al profilo seccomp derivato da Playwright.
Il file `seccomp-profile.json` è generato da Umbrel dal template durante
l'installazione; non deve essere versionato.
