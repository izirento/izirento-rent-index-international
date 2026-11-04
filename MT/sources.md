# Malta: sources

Every row of `MT_rent_landlord_rules.csv` cites a primary source. Facts were read on 2026-11-04. Values are our own wording of the source; check the primary source before relying on a value.

| Topic | Field | Publisher | Source | Cross-check |
| --- | --- | --- | --- | --- |
| tenancy_law | Main law | Laws of Malta (Ministry for Justice) | [link](https://legislation.mt/eli/cap/604/eng/pdf) |  |
| registration | Registration of leases | Laws of Malta (Ministry for Justice) | [link](https://legislation.mt/eli/cap/604/eng/pdf) |  |
| lease_term | Minimum duration of long leases | Laws of Malta (Ministry for Justice) | [link](https://legislation.mt/eli/cap/604/eng/pdf) |  |
| rent_increase | Frequency and cap | Laws of Malta (Ministry for Justice) | [link](https://legislation.mt/eli/cap/604/eng/pdf) |  |
| deposit | Maximum security deposit | - | not available |  |
| rent_level_change | Rent price change, 2025 annual average (HICP actual rentals for housing) | Eurostat | [link](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=MT&time=2025) | [link](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=MT&time=2025-12) |
| rent_level_change | Rent price change, December 2025 year on year (HICP actual rentals for housing) | Eurostat | [link](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=MT&time=2025-12) | [link](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=MT&time=2025) |

## Fields left empty

- Maximum security deposit: No cap found in the Act text read; the Act allows the lessor to request a security amount (art. 6(1)(f)). Left blank.

Licence: CC BY 4.0 for the compilation, see `../LICENSE.md`. This is information, not legal advice.
