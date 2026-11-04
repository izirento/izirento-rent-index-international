# International rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations for countries outside the UK: deposits, rent increases, termination notice, lease terms, registration and energy certificates, with a primary-source link for every value. The UK edition is a separate repository: [izirento-uk-rent-index](https://github.com/izirento/izirento-uk-rent-index).

- Version: 1.0 (first release, further countries are added as they are verified)
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related on izirento.com: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index)
- Localised home pages: [Germany · Deutsch](https://izirento.com/de-de), [Poland · Polski](https://izirento.com/pl-pl), [United Arab Emirates (Dubai) · English](https://izirento.com/en-ae), [United Arab Emirates (Dubai) · العربية](https://izirento.com/ar-ae), [Kazakhstan · Русский](https://izirento.com/ru-kz), [Kazakhstan · Қазақша](https://izirento.com/kk-kz)
- Licence: CC BY 4.0 for the compilation (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). The underlying laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Countries in this release

| Country | Region | Rows | Folder |
| --- | --- | --- | --- |
| Germany | EU | 11 | [`DE/`](DE/) |
| France | EU | 11 | [`FR/`](FR/) |
| Spain | EU | 8 | [`ES/`](ES/) |
| Italy | EU | 8 | [`IT/`](IT/) |
| Netherlands | EU | 9 | [`NL/`](NL/) |
| Poland | EU | 8 | [`PL/`](PL/) |
| United Arab Emirates (Dubai) | Middle East | 6 | [`AE/`](AE/) |
| Kazakhstan | CIS | 8 | [`KZ/`](KZ/) |
| Ireland | EU | 7 | [`IE/`](IE/) |
| Finland | EU | 7 | [`FI/`](FI/) |
| Saudi Arabia | Middle East | 7 | [`SA/`](SA/) |
| Czechia | EU | 9 | [`CZ/`](CZ/) |
| Sweden | EU | 6 | [`SE/`](SE/) |
| Georgia | CIS | 7 | [`GE/`](GE/) |
| Uzbekistan | CIS | 5 | [`UZ/`](UZ/) |
| Luxembourg | EU | 8 | [`LU/`](LU/) |
| Denmark | EU | 6 | [`DK/`](DK/) |
| Estonia | EU | 7 | [`EE/`](EE/) |
| Latvia | EU | 7 | [`LV/`](LV/) |
| Malta | EU | 7 | [`MT/`](MT/) |
| Slovakia | EU | 8 | [`SK/`](SK/) |
| Bahrain | Middle East | 8 | [`BH/`](BH/) |
| Oman | Middle East | 8 | [`OM/`](OM/) |
| Azerbaijan | CIS | 6 | [`AZ/`](AZ/) |
| Armenia | CIS | 9 | [`AM/`](AM/) |
| Slovenia | EU | 9 | [`SI/`](SI/) |
| Portugal | EU | 11 | [`PT/`](PT/) |

Dubai is the only UAE emirate covered, because rent law is set emirate by emirate.

## Countries skipped

| Country | Reason |
| --- | --- |
| Qatar | The official legal portal (almeezan.qa) blocks automated access, so the text of Law No. 4 of 2008 could not be read from a primary source. Only secondary commentary was available. |
| Israel | The Knesset and gov.il pages carrying the Rental and Loan Law amendments could not be read (access refused to automated requests), so no value could be confirmed from a primary source. |
| Austria | The official legal portal (RIS) answers automated requests with a security check, so the Tenancy Act (MRG) could not be read from a primary source. |
| Kuwait | No official consolidated text of Decree-Law No. 35 of 1978 (amended by Laws 15/2020 and 95/2024) could be read; only law-firm and commercial legal-database copies were found, so no value was confirmed from a primary source. |
| Jordan | No official consolidated text of the Landlords and Tenants Law No. 11 of 1994 including its later amendments could be read from the legislation bureau or Ministry of Justice; the copy found is a Bar Association file that does not show the latest amendments. |
| Kyrgyzstan | The official legal database (cbd.minjust.gov.kg) requires a captcha and returned no text to automated access, so the Civil Code and Housing Code could not be read from a primary source. |
| Tajikistan | The official legal portal (adlia.tj) did not respond to requests, so no primary-source text could be read. |
| Turkmenistan | The Housing Code on the government portal covers allocation and lease of the state housing fund only; the rules for private residential rentals (Civil Code) could not be located in a readable official text. |
| Moldova | The official legal register (legis.md) refuses automated access; the e-lex.md portal states that it is a demo version that may contain errors, so no value was confirmed from a reliable primary text. |
| Ukraine | The official Verkhovna Rada portal (zakon.rada.gov.ua) does not respond to requests from the non-Ukrainian network used for this work, and Ukrainian IP addresses are not used, so the Civil Code could not be read from a primary source. |
| Croatia | Only the amending act of 2018 (NN 68/2018) could be read from the official gazette; a consolidated text of the Act on Lease of Flats was not available from a primary source, and its protected-rent provisions apply to a special category of tenancies. |
| Lithuania | The official legal register (e-seimas.lrs.lt) shows a bot-verification page to automated requests, so the Civil Code lease chapter could not be read. |
| Greece | The tax authority (AADE) and public revenue pages could not be read in full, and no official consolidated text of the residential lease rules (Civil Code and Law 4242/2014) was available in readable form. |
| Bulgaria | The legal database reached (lex.bg) is not an official source and denied access; the State Gazette text of the Obligations and Contracts Act was not read. |
| Romania | The official legislation portal (legislatie.just.ro) returned no text to automated requests. |
| Hungary | The official legal database (njt.hu) returned no text to automated requests, and the Civil Code lease chapters were not read. |
| Cyprus | The Rent Control Law text on the official-law site (cylaw.org) could not be read in a usable form (the version obtained did not contain readable lease provisions). |

## Countries not yet covered

- **Other EU member states:** Belgium (rent law is regional). Rent price change for all EU states is in `eu27_rent_price_change_eurostat.csv`; legal rules are added as they are verified.
- **Middle East:** Other UAE emirates.

## Files

| File | Content |
| --- | --- |
| `<CC>/<CC>_rent_landlord_rules.csv` | One row per fact for a country, with source URL, optional cross-check URL and check date |
| `<CC>/sources.md` | Every field with publisher and links, plus fields left empty |
| `all_countries_rent_landlord_rules.csv` | All country files in one table |
| `eu27_rent_price_change_eurostat.csv` | Rent price change for the 27 EU member states from Eurostat (HICP actual rentals for housing) |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |

## Field dictionary (country CSV)

| Field | Meaning |
| --- | --- |
| `country_code, country` | ISO-style code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, lease_term, registration, energy_certificate, rent_level_change and similar |
| `field` | Specific item |
| `value` | The rule or figure in our own wording; empty when no verified figure exists |
| `source_publisher` | Body that published the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | A second source read for the same fact, where one was found |
| `checked_on` | Date the source was read |
| `note` | Caveats, such as translation status or what was not reviewed |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Rent price change for EU countries is the Eurostat HICP index of rents actually paid. It shows how rents moved, not what they cost. The API responses used were last updated by Eurostat on 6 February 2026, so the latest period is December 2025.
4. Where a statute is translated, the original-language text prevails. Rules that depend on a region or municipality (for example designated tight-market areas in Germany, stressed zones in Spain) are described at national level only.

## Citation

Gorok, L. (2026). *International rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://izirento.com

## Attribution

Eurostat data is reused under the Eurostat copyright notice with the source acknowledged. Legal and government sources are listed per country in `sources.md` and in `LICENSE.md`.
