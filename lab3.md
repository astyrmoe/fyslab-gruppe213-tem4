# Journal fra lab 3 (25. feb)

## Oppsett

Vi started med å måle om rammen hvor vi justerer banen vår var rett. Viste seg at denne var litt skev, så vi prøvde å justere ut banen med en liten ring under. Se bilde 1, 2, 3.

-- bilde 1-3 -- **Kristian har bilder**

Vi målte inn alle punktene våre to ganger før vi sa oss fornøyd med banen vår.
Da målestokkens plassering ifht oppsettet bød på problemer, valgte vi å måle punktene fra toppen til øverst på festepunktet.

Vi satte så på plass kameraet vårt i fotostativet.

Vi teipet også på to målestokker til oppsettet for referanse.

**Vekt:**
Svart ball: 30.0 g
Ring: 13.2 g
*Usikkerhet: +/- 0.1 g*

**Dimensjoner:**
Svart ball: 189.8-187.6 cm i diameter
Ring: 5 cm i ytre diameter, ringens tykkelse er 3 mm, 4.3 cm er indre diameter, ringen er 1 cm høy (liggende) (to uavhengige observasjoner)
*Gigantisk usikkerhet*

Vi gjennomførte 10 forsøk med hver gjenstand. For å få til litt variasjon i fremgangsmåten valgte Anna og Aleksander å slippe gjennstandene halvparten av gangene hver.

**Utstyr:**
- Bane
- Kule
- Ring
- Tommerstokk
- Vater
- Vekt
- 2x målestokk
- Teip
- Kamerastativ og -mobil
- Støttering under oppsett :)

## Tracker

Vi opplevde problemer med å importere videofiler inn i Tracker. Ser ut som om det var noe med .mov filene laget av iPhone som var problemet, men gikk fint etter vi konverterte dem til mp4 videoer via `ffmpeg -i /path/video.mov /path/video.mp4`

Vi puttet så videoene inn i tracker. La til et "Mass Poin" på objektet, brukte auto-tracker og fikk ut en tabell etterpå. Vi har lagt ved alle videoene og tabellene produsert av tracker under `/målinger`.

## Databehandling

Python: `lab3.py`
Måledata i `målinger/*.csv`

**Ball:**
Gjennomsnitt: 1.2459086605596414
Standardavvik: 4.575187967652956
Standardfeil: 1.446801470118011

**Ring:**
Gjennomsnitt: 0.8090217008781936
Standardavvik: 4.929877258398597
Standardfeil: 1.558964072160602

## Usikkerhetsanalyse

- Pixel for pixel i tracker
- Frame rate

**TODO**
