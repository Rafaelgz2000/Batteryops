# BatteryOps — Robotics Battery Management Prototype

## Run it
1. Download/extract this project folder.
2. Open `index.html` in a modern browser (Chrome, Edge, Safari, Firefox).
3. The app is responsive for phones, tablets, and computers.

No build step or server is required for the prototype.

## Included
- Dashboard with battery and tool-loan summaries.
- Battery inventory, Practice/Competition categories, duplicate ID protection.
- Charge estimates based on elapsed charging time and configurable full-charge duration.
- Robot insertion/removal timestamps and manually entered post-use charge estimates.
- Bad/dropped battery flagging and required inspection notes before return to service.
- Match assignments, warnings for unavailable batteries, and conflict checks for nearby matches.
- Battery activity history and suggested next-battery order.
- Tool loan records, overdue indicators, and return tracking.
- Editable robot information notes.
- CSV exports and full JSON backup/restore.
- Browser-local persistence via localStorage.

## Important prototype limitations
- Data is saved only in the browser/device where it is entered; it does not sync to teammates.
- Charge percentages are estimates, not live voltage or battery-management telemetry.
- This is a functional prototype, not a safety certification or production multi-user system.
- For deployment to a team, connect a backend such as Supabase/PostgreSQL, add authentication/roles, and host the app over HTTPS.
