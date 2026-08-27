# Team Timezone Map

Interactive support team schedule visualization across time zones.

## Features

- Visual 24-hour timeline with UTC reference
- Three team views: Support team, Technical support team, and Support operations team
- Editable work windows for each team member
- Separate browser-persisted schedules for each team view
- Local time display based on each member's UTC offset
- Yellow country labels for countries that observe daylight saving time
- Tooltips explaining the daylight saving time indicator

## Team Views

### Support team

1. Mitali (India, UTC+4.5)
2. Ranjana (India, UTC+4.5)
3. Luca (Ireland, UTC+1)
4. Aleksandar (Serbia, UTC+2)
5. Milena (Serbia, UTC+2)
6. Renata (Portugal, UTC+1)
7. Juan (Argentina, UTC-4)
8. Hannes (Brazil, UTC-4)
9. Fede (Argentina, UTC-4)
10. Cesar (Costa Rica, UTC-6)
11. João (Brazil, UTC-4)
12. Marco (Costa Rica, UTC-6)
13. Marci (Costa Rica, UTC-6)
14. Everton (Brazil, UTC-4)

### Technical support team

Mitali, Ranjana, Aleksandar, Renata, Juan, Hannes, João, Marco, and Everton.

### Support operations team

Luca, Fede, Cesar, and Marci.

## Working Hours

Each team member's schedule displays a 7-hour-and-40-minute work window, with lunch marked in orange.

The current local schedules include:

- Luca: 04:00-11:40 (Ireland, UTC+1)
- Fede: 08:10-16:50 (Argentina, UTC-4)
- Cesar: 07:00-15:40 (Costa Rica, UTC-6)
- Marci: 09:00-16:40 (Costa Rica, UTC-6)

## Daylight Saving Time

The following countries in the roster observe daylight saving time:

- Ireland
- Serbia
- Portugal

These countries are highlighted in yellow in the interface, with a tooltip explaining the indicator. India, Argentina, Brazil, and Costa Rica do not currently observe daylight saving time.

## How to Use

1. Open `index.html` in a browser.
2. Select a team view using the tabs.
3. Click a team member's name to edit their work window.
4. Changes are saved automatically in the browser for the selected team view.
5. Green cells represent working hours; orange cells represent lunch.

## Technical Notes

- The project is a standalone HTML file with inline CSS and JavaScript.
- No build step or external dependencies are required.
- Schedule data is stored in browser `localStorage`.
- The table uses UTC columns and displays each member's corresponding local time.

---

Developed by Renata Farago.
