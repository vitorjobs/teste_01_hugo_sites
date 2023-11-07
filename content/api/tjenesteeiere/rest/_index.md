---
title: REST
description: Som tjenesteeier får du tilgang til en ekstra del av Altinns REST-api. Selv om du er tjenesteeier vil du også kunne ha behov for den åpne delen av REST APIet. 
weight: 300
aliases:
- /guides/integrasjon/tjenesteeiere/api/
---
{{% panel %}}
#### Modernisering av Altinn
Altinn skal moderniseres for å sikre brukervennlige, sikre og kostnadseffektive tjenester til innbyggere og næringsliv.

*Det betyr at mange av dagens API i Altinn 2 innen juni 2025 vil erstattes av nye tjenester.
Før du tar i bruk dagens Altinn 2 API bør du undersøke hvilke konsekvenser moderniseringsløpet har for deg.*

Les mer om dette på samarbeidsportalen under [Modernisering av Altinn](https://samarbeid.digdir.no/eformidling/modernisering-av-altinn/1799)
{{% /panel %}}

For å få en API-nøkkel med tilgang til "serviceowner"-ressursene, følg stegene på [Kom i gang med REST API](/docs/api/rest-api/kom-i-gang/), og velg autentisering med Maskinporten eller virksomhetssertifikat. Organisasjonsnummeret i tokenet eller sertifikatet må matche det som er oppført på etaten som tjenesteeier i Altinns databaser. For å trigge autentisering med virksomhetssertifikat, legger man på parameteren `?ForceEIAuthentication` i URI-en.

APIet for tjenesteeiere har en egen teknisk dokumentasjonsside med testklient: <br> **[Teknisk API-dokumentasjon for tjenesteeiere](https://www.altinn.no/api/serviceowner/help)**



{{% children description="true" %}}
