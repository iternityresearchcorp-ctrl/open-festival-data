# Open festival data · Life Kundali

City-accurate Hindu, Sikh and Jain festival dates for 156 cities, October 2026 to October 2027,
plus Sangrand, Puranmashi and Masya (the Gurughar calendar) with sunrise and sunset.

Overseas, a festival often falls on a different day than in India, because the Moon's tithi
changes at the same instant everywhere but the day it is "current at sunrise" (or at moonrise,
or in the evening) depends on where you are. In 2026, Karva Chauth is Wednesday 28 October in
Toronto, New York and London, but Thursday 29 October in India. These files give each city its own date.

## Files

- `index.json`: the catalogue (cities, file names, version, licence).
- `<country>-<city>.json`: one file per city: `festivals` (date, India's date, tradition, names in
  English, Hindi and Gurmukhi, the observance rule and the times) and `gurughar` (Sangrand, Puranmashi,
  Masya and Gurpurabs).
- `festivals-2026-27.csv`: every city and festival in one table.

## How the dates are worked out

Swiss Ephemeris positions, Lahiri ayanamsa, each city's own sunrise, sunset and moonrise, and the
classical observance rules (udaya, pradosh, nishita, aparahna and so on) named in each record. Every
date is also on the website with its reasoning: https://lifekundali.com/festivals/ and https://lifekundali.com/gurughar/.
Temples and gurdwaras keep their own calendars; where they differ, theirs is the one to keep.

## Licence

Data: Creative Commons Attribution 4.0 (CC BY 4.0). Use it in apps, sites, calendars and research,
commercial or not. **Credit:** "Festival dates: Life Kundali (lifekundali.com)", with a link where
the medium allows.

Version 2026.10.04. Updated yearly. Questions: order@lifekundali.com
