# THE MIT LICENSE — OFFICIAL ADOPTION KIT

**Versione:** 1.0 · **Stato:** materiale pronto da copiare e da sottoporre a test qualitativo.  
**Per:** maintainer MIT, sviluppatori indipendenti, progetti aziendali e contributor.  
**Principio:** nessuna registrazione, pagamento, firma, certificazione o modifica della licenza.

> **Free Code. Not Free Labor.**  
> Use the code. Respect the maintainer's time.

## 1. Che cosa significa aderire

Un maintainer **aderisce al manifesto** quando inserisce volontariamente un riferimento a questa iniziativa nel proprio repository per esprimere una posizione culturale: il software può essere usato secondo la sua licenza, mentre supporto personale, consulenza e manutenzione non sono automaticamente inclusi.

**Non significa:** ottenere una certificazione, rappresentare MIT, promettere di contribuire, imporre obblighi ai propri utenti, introdurre clausole alla licenza o endorsare personalmente Antonio Trento.

L'adesione è **reversibile** in qualsiasi momento, senza comunicazione al progetto.

## 2. Come interpretare i link in questo documento

**Fase attuale, prima della pubblicazione del sito:** gli snippet ufficiali qui sotto puntano al repository GitHub già esistente:

`https://github.com/themitlicense/themitlicense.github.io`

**Dopo il lancio:** la destinazione del link potrà diventare la **pagina pubblica canonica del manifesto** sul sito `themitlicense.github.io`, quando tale pagina esisterà e sarà verificata. L'URL concreto della pagina verrà stabilito in sede editoriale; non assumere che un percorso inventato sia già pubblicato.

**Regola:** cambiare il *link cliccato* del badge, non riscrivere la licenza MIT nel repository che aderisce.

## 3. Badge ufficiale consigliato — MIT / Free Code Not Free Labor

### Testo

`MIT · Free Code Not Free Labor`

### Markdown da copiare in un README MIT

```md
[![MIT — Free Code, Not Free Labor. Independent manifesto](https://img.shields.io/badge/MIT-Free_Code_Not_Free_Labor-FF6B35?style=flat-square)](https://github.com/themitlicense/themitlicense.github.io)
```

**Cosa comunica:** il manifesto riguarda il contesto MIT; il maintainer dichiara di condividere la necessità di rispettare il suo tempo.

**Cosa non comunica:** non certifica la licenza del repository, non indica un endorsement di MIT e non garantisce che il progetto segua tutte le raccomandazioni del manifesto. Il badge **non sostituisce** il normale `License: MIT`.

**Regola di correttezza:** se il repository **non** è MIT, non usare la variante con etichetta `MIT` come se ne fosse la licenza. Preferire il badge generale (§5) o una dichiarazione testuale.

## 4. Badge alternativo — support not included

### Testo

`Support · Not Included`

### Markdown

```md
[![Support — Not Included. Independent maintainer manifesto](https://img.shields.io/badge/Support-Not_Included-FF6B35?style=flat-square)](https://github.com/themitlicense/themitlicense.github.io)
```

**Quando preferirlo:** README professionali, progetti senza enfasi visiva sullo slogan o maintainer interessati al beneficio pratico.

**Avvertenza:** nei progetti con supporto a pagamento o promesse specifiche il messaggio deve essere qualificato. Nessun badge prevale su un eventuale contratto o su promesse fatte separatamente.

## 5. Badge generale — senza etichetta di licenza

### Testo

`Maintainers · Time Matters`

### Markdown

```md
[![Maintainers — Time Matters. Independent manifesto](https://img.shields.io/badge/Maintainers-Time_Matters-FF6B35?style=flat-square)](https://github.com/themitlicense/themitlicense.github.io)
```

**Quando preferirlo:** il maintainer desidera appoggiare il principio ma il suo progetto non usa MIT, usa più licenze o preferisce non associarlo al proprio identificativo di licenza. È una variante **di sostegno**, non una dichiarazione sulla licenza del codice.

## 6. Statement README — EN, versione breve

```md
### Open-source expectations

This project is available under the license stated in this repository. The
license does not by itself include guaranteed support, maintenance,
customization, or consulting. Please respect the maintainers' time.
Constructive bug reports, contributions, and acknowledgments are welcome.

We support the independent [Free Code. Not Free Labor. manifesto](https://github.com/themitlicense/themitlicense.github.io).
```

**Cosa risolve:** spiega lo scopo senza richiedere la presenza del badge; si adatta anche a progetti che non vogliono una comunicazione provocatoria.

## 7. Statement README — EN, versione professionale neutra

```md
### Support and maintenance

Use of this software is governed by the license included with the project.
Unless separately agreed, the availability of the source code does not
include guaranteed technical support, maintenance commitments, or consulting.
Questions and well-documented bug reports are welcome, but responses and
resolution timelines are not guaranteed.

We endorse the voluntary principles of the independent [maintainer respect
manifesto](https://github.com/themitlicense/themitlicense.github.io). This
statement does not change the software license.
```

**Uso appropriato:** aziende, fondazioni, librerie ampiamente integrate, team che preferiscono un tono da progetto maturo.

**Attenzione:** «unless separately agreed» evita di fingere che nessun maintainer possa mai avere obblighi contrattuali.

## 8. Statement README — IT, versione breve

```md
### Aspettative sul supporto

Il software è disponibile secondo la licenza indicata in questo repository.
La disponibilità del codice non include di per sé assistenza garantita,
manutenzione, personalizzazioni o consulenza. Rispetta il tempo di chi
mantiene il progetto: segnalazioni precise e contributi costruttivi sono
sempre apprezzati.

Sosteniamo il manifesto indipendente [Free Code. Not Free Labor.](https://github.com/themitlicense/themitlicense.github.io).
```

## 9. Statement README — IT, versione professionale

```md
### Supporto e manutenzione

L'utilizzo del software è regolato dalla licenza presente nel repository.
Salvo accordi separati, il codice sorgente pubblicato non comprende servizi
di supporto garantito, impegni di manutenzione o consulenza. Le richieste e
le segnalazioni documentate sono benvenute, ma non sono previsti tempi di
risposta o risoluzione garantiti.

Condividiamo i principi volontari del [manifesto indipendente sul rispetto
dei maintainer](https://github.com/themitlicense/themitlicense.github.io).
Questa dichiarazione non modifica la licenza del software.
```

## 10. Link senza badge — minima frizione

**Inglese, riga breve:**

```md
We support [Free Code. Not Free Labor.](https://github.com/themitlicense/themitlicense.github.io), an independent manifesto about respecting open-source maintainers.
```

**Italiano, riga breve:**

```md
Sosteniamo [Free Code. Not Free Labor.](https://github.com/themitlicense/themitlicense.github.io), un manifesto indipendente per il rispetto di chi mantiene software open source.
```

## 11. Statement per contribuire in modo rispettoso (NON requisito di licenza)

Questa aggiunta opzionale incoraggia bug report utili e riduce ambiguità nelle aspettative:

```md
### Before opening an issue

Please search existing issues and documentation, include relevant versions,
clear reproduction steps, and the expected versus actual behavior.
Issues are requests for collaboration, not guaranteed support tickets.
Thank you for respecting the time of volunteer maintainers.
```

**Italiano:**

```md
### Prima di aprire un'issue

Consulta la documentazione e le issue esistenti; indica versioni,
passaggi per riprodurre il problema e comportamento atteso rispetto a quello
osservato. Un'issue è una richiesta di collaborazione, non un ticket di
assistenza con risposta garantita.
```

## 12. Versioni da condividere fuori dal README

**Social — proposta inglese sintetica:**

> My code is shared under the MIT License. My time isn't included. I support the independent **Free Code. Not Free Labor.** manifesto.

**Social — proposta italiana sintetica:**

> Il mio codice è distribuito con licenza MIT. Il mio tempo non è compreso nella licenza. Sostengo il manifesto indipendente **Free Code. Not Free Labor.**

**Bio/testo descrittivo:**

> Open source supporter. Clear boundaries for maintainer time. Free Code. Not Free Labor.

**Nota:** l'adesione non autorizza il progetto a ripubblicare nomi, loghi o testimonial come endorsement commerciali.

## 13. FAQ rapida per chi adotta

**Devo cambiare il file LICENSE?** No. Mai aggiungere il manifesto come clausola alla MIT.

**Devo condividere modifiche o donare?** No. Il manifesto incoraggia, ma non obbliga.

**Devo citare Antonio Trento?** No. Il collegamento al manifesto deve essere chiaro, ma non richiediamo un link promozionale al sito personale del fondatore.

**Serve l'autorizzazione dell'organizzazione?** Non da parte nostra. Nel tuo repository rispetta le normali regole decisionali del progetto e dell'organizzazione che lo governa.

**È una certificazione della correttezza del progetto?** No.

**Posso sostituire il testo del badge?** Sì, se non fai sembrare il manifesto una fonte ufficiale della MIT o un nuovo insieme di restrizioni legali.

**Posso usare un badge anche se non sono maintainer?** Puoi condividere il messaggio; evita però di modificare repository o profili di terzi senza consenso.

**Un contratto di supporto diventa nullo se aggiungo il badge?** No. Il badge non annulla accordi esistenti.

## 14. Contrasto: badge manifesto vs badge licenza

| Indicazione | Esempio | A cosa serve |
|---|---|---|
| Badge licenza | `License: MIT` | Identifica la licenza effettiva del software |
| Badge manifesto | `MIT · Free Code Not Free Labor` | Esprime supporto a una posizione volontaria |
| Testo LICENSE | MIT ufficiale con avvisi richiesti | Definisce diritti e condizioni legali |
| Testo README | Aspettative sul supporto | Comunica informazioni pratiche e culturali |

Se un badge esprime «MIT» ma il repository usa un'altra licenza, il visitatore potrebbe essere tratto in inganno. Usare la variante generale.

## 15. Regole ufficiali per il brand di adozione

1. No «official», «certified», «approved by MIT».
2. No loghi MIT, GitHub o OSI spacciati come partner.
3. No modifica del testo di licenza per aggiungere obblighi «etici».
4. No caricamento del badge come prova di adesione di terzi senza approvazione.
5. No meccanismi che costringano gli utenti downstream ad aderire.
6. No URL abbreviati opachi, redirect verso prodotti a pagamento o raccolta email obbligatoria.
7. No badge usati come pegno per ottenere aiuto o priorità.
8. No campagne massive per far inserire il badge a maintainer inconsapevoli.

## 16. Strategia A/B — testare prima di decretare il badge definitivo

**Ipotesi A:** lo slogan «MIT · Free Code Not Free Labor» comunica meglio l'identità del movimento.  
**Ipotesi B:** «Support · Not Included» convince più maintainer perché esprime il vantaggio pratico.  
**Ipotesi C:** i team istituzionali preferiscono lo statement neutro.

Mostrare le tre possibilità a un piccolo campione di maintainer, in ordine alternato. Chiedere: «Che cosa significa?», «La MIT cambia?», «Lo metteresti davvero nel README?».

**KPI del test:** adozioni effettivamente osservate entro 7–14 giorni; comprensione corretta; timore di confusione legale; richiesta di variante neutra. Con campioni ridotti, non proclamare una superiorità statistica.

## 17. Manutenzione editoriale del kit

- Quando il sito sarà pubblicato, indicare un **solo URL canonico del manifesto** per il badge consigliato.
- Tenere un solo badge primario nella comunicazione, mantenendo alternative utili.
- Non cambiare destinazione e tono dei badge già condivisi per promuovere il fondatore.
- Se cambia il nome del manifesto, mantenere continuità nei collegamenti senza appropriazione dell'identità MIT.
- Se si introduce una licenza esplicita per testi/badge originali, pubblicarla chiaramente **prima** di incoraggiare adattamenti di terzi.
- Se si vuole mostrare pubblicamente un adopter, chiedere consenso per nome/logo/testimonianza; la sola presenza di badge pubblico non equivale ad autorizzazione a un endorsement.

## 18. Riferimenti

- Shields.io, badge statici: https://shields.io/docs/static-badges
- Testo MIT ufficiale: https://opensource.org/license/mit
- Documento interno di origine: `foundation.md`, sezioni 5–8.

**Il badge non deve vendere il manifesto. Deve dare al maintainer un modo elegante per dire: «Questo codice puoi usarlo; il mio tempo no».**
