Steg 3:
![Summary-sida för körning](m6-step3-1)
![Körningar för Publish images](m6-step3-2)
Verifierade automatisk trigger för publish-images.yml startat av merge-commit. Verifierade också båda jobben och summary/översikt för körningen (tags).

Steg 4:
![Package visibility: public](m6-step4.png)
Verifierade att paketen är publika; hade redan gjort detta i ett tidigare delmoment.

Steg 5:
![Konsol-output för docker logout och andra kommandon som kördes](m6-step5.png)
Loggade ut ur GHCR och testade pull utan inloggning. Verifierade output från konsolen.

Steg 6:
![Log för steget TEMP - do not merge](m6-step6.png)
Testade secrets genom ett test med GITHUB_TOKEN (aldrig merge). Verifierade efter build också loggen och att värdet inte visas som klartext och att inget pushas.