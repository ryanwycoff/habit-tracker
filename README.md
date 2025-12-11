# Personal Habit Tracker

A private, password-protected habit tracking web application optimized for iPhone use. Track your daily schedule, workouts, meals, supplements, and personal care routines.

## Features

✅ **All TODO Requirements Completed:**

1. ✓ Password protection for privacy
2. ✓ Private configuration file (habits and schedule separate from main code)
3. ✓ Removed import button from bottom panel
4. ✓ Removed "Up Next" UI component (only Overdue section remains)
5. ✓ Calendar highlighting: **Blue** for selected day, **Grey** for current day
6. ✓ Removed categories and notes from daily schedule view
7. ✓ Separate tracking for duplicate habits (same habit can appear multiple times in schedule with independent tracking)
8. ✓ Red highlighting for overdue items
9. ✓ Completed items hidden by default with "Show Completed" toggle button
10. ✓ Schedule items sorted chronologically
11. ✓ Comprehensive exercise habits with reps and sets details
12. ✓ Pilonidal cyst care habits (hair removal cream schedule)
13. ✓ Body hair trimming habits with optimal 16mm guard lengths
14. ✓ Weekly laundry habit
15. ✓ Weekly financial review habit
16. ✓ Weekly face shaving habit
17. ✓ Complete optimized schedule for all 7 days
18. ✓ iPhone portrait optimization (all UI components fit perfectly)
19. ✓ Local storage with live updates
20. ✓ TODO.md and SCHEDULE.md removed from git tracking

## Setup Instructions

### 1. Configure Your Password

Edit `config-private.js` and change the password:

```javascript
password: "changeme123",  // Change this to your desired password
```

### 2. Customize Your Schedule (Optional)

The `config-private.js` file contains:
- **Habits**: Complete list of all activities with details
- **Schedule**: Weekly schedule for Monday-Sunday

You can customize these through the web interface or by editing the config file directly.

### 3. Deploy to iPhone

#### Option A: Local File (Simplest)
1. Open `habit-tracker.html` directly in Safari on your iPhone
2. Add to Home Screen for app-like experience

#### Option B: GitHub Pages (Recommended)
1. Push the repository to a **private** GitHub repo
2. Enable GitHub Pages in repo settings
3. Access via the provided GitHub Pages URL
4. Add to Home Screen on your iPhone

#### Option C: Self-Hosted Server
1. Upload all files to your web server
2. Ensure `config-private.js` is accessible
3. Access via your domain

### 4. Add to iPhone Home Screen

1. Open the tracker in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"
4. Name it "Habit Tracker"
5. It will now work like a native app!

## Usage

### Daily Tracking
- **Overdue Section**: Shows habits that are past their scheduled time
- **Calendar**:
  - Grey border = today's date
  - Blue border = selected date
  - Green dots = completed habits
  - Red dots = overdue/missed habits
- **Daily Schedule**:
  - View all scheduled habits for the selected day
  - Tap checkboxes to mark complete
  - Red background = overdue items
  - Completed items hidden by default (toggle to show)

### Managing Your Schedule
1. Tap "Manage" button at bottom
2. Select day of week
3. Add, edit, or remove schedule items
4. Choose from predefined habits
5. Tap "Done" to save changes

### Data Management
- **Export**: Download backup of all completion data
- **View Data**: See all tracked data in JSON format
- **Clear All**: Reset all completion tracking (habits and schedule remain)

## Data Storage

- **LocalStorage**: All completion tracking stored in browser's localStorage
- **Privacy**: Data never leaves your device
- **Backup**: Use Export feature regularly to backup your data
- **Sync**: For iPhone, data syncs via iCloud if Safari is configured to sync

## File Structure

```
habit-tracker/
├── habit-tracker.html     # Main application (public)
├── config-private.js      # Your private habits & schedule (DO NOT COMMIT)
├── .gitignore            # Prevents private files from being committed
├── README.md             # This file
├── TODO.md               # Personal notes (not tracked in git)
└── SCHEDULE.md           # Personal schedule details (not tracked in git)
```

## Security Notes

1. **Password Protection**: Basic password authentication - not suitable for highly sensitive data
2. **Config File**: Never commit `config-private.js` to a public repository
3. **GitHub Pages**: Use a **private** repository if deploying via GitHub Pages
4. **HTTPS**: Always use HTTPS in production to protect password transmission

## Customization

### Changing Password
Edit `config-private.js`:
```javascript
password: "your-new-password",
```

### Adding New Habits
Edit `config-private.js` in the `habits` array:
```javascript
{
  id: 'my_habit',
  name: 'My New Habit',
  category: 'Fitness',
  details: 'Optional details shown under habit name'
}
```

### Modifying Schedule
Edit `config-private.js` in the `schedule` object:
```javascript
'Monday': [
  { time: '6:00 AM', habitId: 'my_habit' },
  // ... more items
]
```

## Browser Compatibility

- ✅ Safari (iOS) - Optimized
- ✅ Chrome (Mobile)
- ✅ Firefox (Mobile)
- ✅ Desktop browsers (works but optimized for mobile)

## Troubleshooting

### Password Not Working
- Check for typos in `config-private.js`
- Ensure you saved the file after editing
- Hard refresh the page (Cmd+Shift+R or clear cache)

### Data Lost
- Check if browser data was cleared
- Restore from Export backup if available
- Enable iCloud sync for Safari to prevent data loss

### Schedule Not Showing
- Verify `config-private.js` is in the same directory as `habit-tracker.html`
- Check browser console for JavaScript errors
- Ensure the file is properly formatted (valid JavaScript)

## Tips for Best Results

1. **Daily Routine**: Check overdue items throughout the day
2. **Weekly Export**: Export your data every Sunday as backup
3. **Schedule Refinement**: Adjust times based on actual completion patterns
4. **iPhone Setup**: Enable "Add to Home Screen" for quick access
5. **Notifications**: Use iPhone's built-in alarms for time-sensitive habits

## Local Storage vs iPhone Storage

The app currently uses browser localStorage which is persistent but can be cleared if:
- Browser data is manually cleared
- iPhone storage is critically low
- Safari is reset

**Mitigation strategies:**
1. Regular exports (recommended weekly)
2. iCloud Safari sync (automatic if enabled)
3. Multiple device access keeps data alive

For true local iPhone file storage, the app would need to be converted to a native app or Progressive Web App with file system access, which is beyond the scope of this web-based implementation but the localStorage approach is reliable for daily use with proper backups.

## License

Personal use only. Not intended for redistribution.

## Updates

To update the app:
1. Download new `habit-tracker.html`
2. Keep your existing `config-private.js`
3. Your data and configuration will be preserved

---

**Version**: 2.0
**Last Updated**: December 2025
**Optimized for**: iPhone (Portrait Mode)
