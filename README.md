# LoL Esports Schedule

A simple, responsive website displaying upcoming League of Legends esports matches for LCK, LPL, LCS, and LEC leagues.

## Features

- Display upcoming matches for all 4 major leagues (LCK, LPL, LCS, LEC)
- Filter matches by league
- Team win/loss records
- Match format (Bo1, Bo3, Bo5)
- Auto-refresh every 5 minutes
- Match details modal
- Responsive design
- Dark theme with esports aesthetic

## How to Run

### Option 1: Direct File Open
Simply open `index.html` in your web browser:
1. Double-click `index.html`, or
2. Right-click `index.html` → Open with → Your browser

### Option 2: Local Server (Recommended)
Using Python 3:
```bash
python -m http.server 8000
```

Then open: http://localhost:8000

Using Node.js:
```bash
npx serve
```

Then open: http://localhost:3000

### Option 3: Deploy to GitHub Pages
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select `main` branch
4. Your site will be available at `https://yourusername.github.io/lolschedule/`

## Technical Details

- **Tech Stack**: Plain HTML, CSS, JavaScript (no build tools required)
- **API**: Lolesports API (https://esports-api.lolesports.com)
- **Auto-refresh**: Every 5 minutes
- **Data displayed**: Upcoming matches (state: "unstarted")

## League Configuration

| League | ID | Color |
|--------|-----|-------|
| LCK    | 98767991310872058 | Gold |
| LPL    | 98767991314006698 | Blue |
| LCS    | 98767991299243165 | Red |
| LEC    | 98767991302996019 | Purple |

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## License

MIT License - Free to use and modify.
