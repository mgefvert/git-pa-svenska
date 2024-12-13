# Git på svenska

Originalet finns på sidan https://github.com/bjorne/git-pa-svenska.
De förändringar som jag har gjort är för att skapa en mer normal,
levande och normativ ordlista, mer i linje med dagligt bruk.

## Introduktion

Det dagliga språket för de olika kommandona i `git` är
på svenska ett enda stort svengelskakalas. Jag finner mig själv ofta
sägandes _"Kan du pusha branchen?"_ eller _"Jag pullar!"_, vilket
känns pinsamt.

Detta dokument ämnar etablera en ren svensk jargong som kan användas
på arbetsplatsen för att med fördel undvika pressade situationer med
kollegor samt boskap.

## Konvention

Nedan följer tabeller över verb och substantiv relaterade till git,
deras nuvarande bruk samt förslag på hur vi tillsammans kan bättra
oss.

| Verb        | Tidigare bruk | Ny konvention    |
|-------------|---------------|------------------|
| pull        | pulla         | dra ner (1)      |
| push        | pusha         | trycka ut/upp    |
| fetch       | fetcha        | hämta            |
| branch      | brancha       | skapa en ny gren |
| commit      | commita       | checka in (2)    |
| rebase      | rebasa        | ombasera         |
| merge       | merga         | dra in (1)       |
| squash      | squasha       | mosa in/samman   |
| stash       | stasha        | gömma undan      |
| tag         | tagga         | märka upp        |
| cherry-pick | cherry-picka  | russinplocka     |
| amend       | amenda        | justera          |
| blame       | blamea        | klandra          |

| Substantiv    | Tidigare bruk | Ny konvention       |
|---------------|---------------|---------------------|
| git           | git           | git (3)             |
| repository    | repo          | kodkassun (4)       |
| branch        | branch        | gren                |
| commit        | commit        | incheckning         |
| pull request  | pull request  | ryckbegäran (5)     |
| stash         | stash         | kodgömma            |
| tag           | tagg          | märke               |
| main branch   | ?             | huvudgren, stam (6) |

1) Medan engelskan gör skillnad mellan pull och merge, så används i svenskan hellre
   olika riktadverb. Pull blir således "dra ner" (vertikal form, upp till eller ner från
   molnet) medan merge blir "dra in" (horisontell form, från jämställda grenar).

2) "Checka in" och "incheckning" är inte helt svenskt, men är ett vedertaget begrepp
   både inom programmering, hotell, och näringsliv. Det finns liten anledning att ändra
   det begreppet, även om "check-in" och "commit" inte är helt jämförbara.

3) För att undvika svärord så bör inte "jävel" användas. Git är ett programvarusystem
   och bör benämnas med sitt originalnamn.

4) En kassun är en vattentät "kista" för grundläggning av byggnadsverk i vatten. Kan 
   också användas i militära sammanhang för förvaring av vapen. Kodkassun känns som en
   relevant beteckning istället för repository.

5) Rycka rekommenderas inte längre som verb. Begreppet med ryckbegäran har dock satt sig,
   och kan fortleva. Alternativet, "indragningsbegäran" eller "dragningsförfrågan" är
   onödigt formellt.

6) Medan stam är accepterbart, så är huvudtanken i git att det finns i princip ingen
   unik stam utan allt är separata grenar. Det känns mer relevant att betrakta det som
   en huvudgren i så fall. Båda förslagen bör dock fungera bra. "master" har i stort sett
   ersatts med "main" vilket normalt översätts med "huvud-".

## Exempel

- Kan du dra in grenen jag just ombaserade och trycka ut den till github?
- Jag skapade en ny gren alldeles nyss och drog in ändringarna från min kodgömma där.
- Skicka en ryckbegäran när du är färdig med din indragning!
- Låt oss plocka russin från huvudgrenen.
- Hoppsan, jag råkade visst tvinga en uttryckning mot huvudgrenen.. :D
- Mosa samman dina incheckningar innan du drar in dem.
