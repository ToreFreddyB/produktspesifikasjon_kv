### Datamodell

**Kilde:** [SOSI UML XMI-fil](inputs/fastmerker-hoydefastmerker/model.xmi)

<a href="fastmerker-uml_feature_catalogue.png" title="Klikk for stor visning"><img src="fastmerker-uml_feature_catalogue.png" alt="Datamodell fastmerker_uml" style="max-width: 100%; height: auto;" /></a>

#### Fastmerke

varig merket punkt, markert med bolt eller annet merke der plane koordinater og/eller høyde er bestemt, eller er planlagt bestemt i et geodetisk system<br /><br />Merknad: Fastmerker tjener hovedsakelig som grunnlag ved kartlegging og oppmåling. Tidligere kunne fastmerker innbefatte borehull, merke i fjell, el.<br /><br /><br />-- Definition --<br />permanently marked point, marked with a bolt or other mark in which the plane coordinates and/or height are determined, or are planned to be determined in a geodesic system

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på<br /><br />-- Definition --<br />location where the object exists</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>punktNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets unike identitetskode angitt kartverkets punktnummersystem</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkeNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnet på fastmerket ved registrering. Dette er ikke nødvendigvis det offisielle stedsnavnet for området<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.2).<br /><br />-- Definition --<br />the name of the survey control station upon registration. This is not necessarily the official place name for the area  Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.2).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>punkttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av fastmerkets punkttype<br /><br />Merknad:  I norm for fastmerkeregister og fastmerkenummer har punkttype kodene P, Q og R avhengig av selve nummeret. I denne standarden benyttes punkttype P for polygonpunkt uavhengig av selve nummeret.<br /><br />-- Definition --<br />description of the point type of the survey control station   Note: In the norm for survey control station register and survey control station number, point type has the codes P, Q and R depending on the number itself. In this standard, the point type P is used for the polygon point regardless of the number.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>PunktType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/fastmerker/punkttype">https://register.geonorge.no/sosi-kodelister/fastmerker/punkttype</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkeEtableringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for etablering av fastmerke<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.6).<br /><br />-- Definition --<br />date of establishment of survey control station   Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.6).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkestatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>fastmerkets status<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister.<br /><br />-- Definition --<br />status of the survey control station   Note: For more information, see the standard survey control station numbering and survey control station register.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fastmerkestatus</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkestatus.verifiseringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når dataene er fastslått å være i samsvar med virkeligheten<br /><br />Merknad: Verifiseringsdato er identisk med ..DATO i tidligere versjoner av SOSI<br /><br />-- Definition --<br />date when it is established that the data conform to reality    Note: Verification date is identical to ..DATE in previous versions of SOSI</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkestatus.typeStatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av  fastmerkets status<br /><br />-- Definition --<br />designation of the survey control station's status</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeStatus</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/fastmerker/typestatus">https://register.geonorge.no/sosi-kodelister/fastmerker/typestatus</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkeUnderlag</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>type underlag som fastmerke står i<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.13)<br /><br />-- Definition --<br />type of foundation where the survey control station is located    Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.13)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>FastmerkeUnderlag</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkeunderlag">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkeunderlag</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkeSentrumRef</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av punktet for sentrumsreferansen, dvs hva på fastmerket nord- og øst-koordinaten refererer seg til<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.16)<br /><br />-- Definition --<br />description of the point of the centre reference, i.e. to what on the survey control station do the north and east coordinates refer   Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.16)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>FastmerkeSentrumRef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkesentrumref">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkesentrumref</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fastmerkeHøydeRef</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hva høyden refererer seg til<br />f.eks. topp av fastmerke</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>FastmerkeHøydeRef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkehoyderef">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkehoyderef</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boltHøgde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høyden på bolten som markerer punktet. Målt fra bakken til boltens høyeste punkt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kommune</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av hvilke kommune punktet ligger innenfor<br /><br />Merknad:  Statistisk sentralbyrå har en offisiell liste over kommunenummer hvor de to første siffer er fylkesnummer og de to siste kommunenummer innen fylket.<br /><br />-- Definition --<br />statement of which municipality the point lies within   Note: Statistics Norway has an official list of municipality numbers, in which the two the first digits indicate the county number and the two last municipality numbers within the county.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kommunenummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>punktBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>fastmerkets beliggenhet i forhold til omgivelsene<br /><br />Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.36).<br /><br />-- Definition --<br />location of the survey control station in relation to the surroundings   Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.36).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>sone</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Naturlig sone til punktets kartprojeksjonskoordinater i euref89</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>naturligAkse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Naturlig sone til punktets kartprojeksjonskoordinater i NGO1948</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nordKoordinat</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets nordlig kartprojeksjonskoordinat i EUREF89 og naturlig sone angitt i variabelen _ sone_</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>østKoordinat</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets østlige kartprojeksjonskoordinat i EUREF89 og naturlig sone angitt i variabelen _ sone_</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nordKoordinatEuref89Sone33</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets nordlig kartprojeksjonskoordinat i EUREF89 og sone 33</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>østKoordinatEuref89Sone33</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets østlige kartprojeksjonskoordinat i EUREF89 og sone 33</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nordKoordinatNGO1948</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets nordlig kartprojeksjonskoordinat i NGO1948 og naturlig sone angitt i variabelen _ naturligAkse_</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>østKoordinatNGO1948</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktets østlige kartprojeksjonskoordinat i NGO1948 og naturlig sone angitt i variabelen _ naturligAkse_</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeNN1954</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høyde angitt i den vertikale referansen NN1954</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeEllipsoidisk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Ellipsoidisk høyde i EUREFf89</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeNormalNN2000</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høyde angitt i den vertikale referansen NN2000</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beregningsDatoNGO1948</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato da punktets gjeldende koordinater i NGO1948 ble beregnet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beregningsDatoEuref89</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato da punktets gjeldende koordinater i EUREF89 ble beregnet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beregningsDatoNN1954</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for beregning av fastmerke<br /><br />Merknad:<br />For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.17).<br /><br />-- Definition --<br />date of calculation of survey control station   Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.17).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beregningsDatoNN2000</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato da punktets gjeldende høyde i NN2000 ble beregnet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydereferansemodell</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Modellen som er brukt ved beregning av høydeverdien i variabelen_høydeNormalNN2000</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeGammelNN2000_2018</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Gjeldende høydeverdi i variabelen_høydeNormalNN2000 før siste datumsoppdatering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Fellesegenskaper

#### Fellesegenskaper (abstrakt)

abstrakt objekttype som bærer sentrale egenskaper som er anbefalt for bruk i produktspesifikasjoner.<br /><br />Merknad: Disse egenskapene skal derfor ikke modelleres inn i fagområdemodeller.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tidspunkt for siste endring på objektet<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Posisjonskvalitet</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodekode">https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodekode</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for å måle høyden</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MålemetodeHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodeh%C3%B8ydekode">https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodeh%C3%B8ydekode</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetNGO1948</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Posisjonens nøyaktighet i NGO1948. Stipulert etter målestyrken</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetEUREF89</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Posisjonens nøyaktighet i EUREF89. Angitt som to ganger RMS av de beregnede standardavvik til punktets koordinater</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetHøydeNN1954</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydens nøyaktighet i NN1954. Stipulert etter målestyrken</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetHøydeNN2000</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydens nøyaktighet i NN2000</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «CodeList» PunktType

**Definisjon:** beskrivelse av fastmerkets punkttype

Merknad:  I norm for fastmerkeregister og fastmerkenummer har punkttype kodene P, Q og R avhengig av selve nummeret. I denne standarden benyttes punkttype P for polygonpunkt uavhengig av selve nummeret.

-- Definition - -
description of the point type of the survey control station    Note: In the norm for survey control station register and survey control station number, point type has the codes P, Q and R depending on the actual number. In this standard, the point type P is used for the traverse point regardless of the number.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/fastmerker/punkttype">https://register.geonorge.no/sosi-kodelister/fastmerker/punkttype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» TypeStatus

**Definisjon:** fastmerkets status

Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister.

-- Definition - -
status of the survey control station    Note: For more information, see the standard survey control station numbering and survey control station register.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/fastmerker/typestatus">https://register.geonorge.no/sosi-kodelister/fastmerker/typestatus</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» FastmerkeUnderlag

**Definisjon:** type underlag som fastmerke står i

Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.13)

-- Definition - -
type of foundation for the survey control station    Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.13)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkeunderlag">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkeunderlag</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» FastmerkeSentrumRef

**Definisjon:** beskrivelse av punktet for sentrumsreferansen, dvs hva på fastmerket nord- og øst-koordinaten refererer seg til

Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.16)

-- Definition - -
description of the point for the centre reference, i.e. to what on the survey control station do the north and east coordinates refer    Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.16)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkesentrumref">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkesentrumref</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» FastmerkeHøydeRef

**Definisjon:** beskrivelse av punktet for høydereferenser, dvs hva høyden refererer seg til

Merknad: For nærmere informasjon, se standarden fastmerkenummerering og fastmerkeregister, opplysninger knyttet til et fastmerke (5.1.1.26).

-- Definition - -
description of point for height references, i.e. what the height refers to    Note: For more information, see the standard survey control station numbering and survey control station register, information in connection with a survey control station (5.1.1.26).

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkehoyderef">https://register.geonorge.no/sosi-kodelister/fastmerker/fastmerkehoyderef</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Kommunenummer

**Definisjon:** nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste samt et utvalg av utgåtte numre

Merknad: Det presiseres at kommune alltid skal ha 4 sifre, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 sifre.

Merknad 2: Modelleringsverktøyet Enterprise Architect håndterer ikke samiske tegn eller tankestrek. Det betyr at det vil forekomme avvik mellom definisjonene i denne lista i SOSI modellregister og definisjonene i offisielt standarddokument.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon

-- Definition - -
method on which registration of position is based

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodekode">https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodekode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» MålemetodeHøyde

**Definisjon:** metode for å måle objekttypens høydeverdi

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodeh%C3%B8ydekode">https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetodeh%C3%B8ydekode</a></td>
    </tr>
  </tbody>
</table>
