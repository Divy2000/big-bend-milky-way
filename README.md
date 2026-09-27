# big-bend-milky-way

A one-page invitation to a new-moon weekend in Big Bend (Oct 9–11, 2026).

- **Before/after hero**: a photo from Cottonwood Park under the full moon, next to the sky over Big Bend at 9 pm on Oct 9. The Big Bend sky is rendered in the browser: about 4,700 real stars, the Milky Way brightness map, the planets, and atmospheric extinction.
- **Darkness chart**: hours of true dark each night (sun 18° below the horizon, moon down), computed with PyEphem.
- **All-sky planetarium**: the full Oct 9 sky with a time scrubber from 8:30 pm to 6:30 am.
- **Route map, countdown, itinerary, cost split, objections answered**, plus the Yes/No ask and a calendar invite.
- **Live update notice**: the page checks `version.json` every 30 seconds. When the version changes, open copies show a "Reload" toast. First load of a new version shows a banner saying what changed.

Personalize the link: `https://divy2000.github.io/big-bend-milky-way/?name=FirstName`

To ship an update, bump `version` (and `note`) in `version.json` to match `PAGE_VERSION` in `index.html`.

Star and Milky Way data come from d3-celestial by Olaf Frohn (BSD-3-Clause).
