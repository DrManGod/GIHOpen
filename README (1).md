# GIH Open Tournament - Swiss System Bracket

A beautiful, interactive tennis tournament management system for the Swedish School of Sport and Health Sciences.

## 🎾 Features

- **20 Players** - Swiss system format with 5 rounds
- **Bilingual** - Switch between English and Swedish (tennis ball button)
- **Auto-Save** - Scores save automatically to browser storage
- **Playoffs** - Top 4 advance to semifinals and final
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Tennis Theme** - Professional tennis club aesthetic

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Create Repository**
   - Go to GitHub.com
   - Click "+" → "New repository"
   - Name: `gih-open-tournament`
   - Make it Public
   - Check "Add a README file"
   - Click "Create repository"

2. **Upload File**
   - Click "Add file" → "Upload files"
   - Upload `gih_open_tournament.html`
   - **Rename it to `index.html`** (important!)
   - Commit changes

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` → `/root`
   - Save

4. **Access Your Tournament**
   - URL: `https://YOUR-USERNAME.github.io/gih-open-tournament/`
   - Wait 1-2 minutes for deployment

### Option 2: Direct Use

Simply open `gih_open_tournament.html` in any modern web browser.

## 📖 How to Use

1. **Enter Player Names** - Edit names directly in the standings table
2. **Round 1** - Pre-filled with pairings (1 vs 2, 3 vs 4, etc.)
3. **Enter Scores** - Input 0-6 points per player
4. **Generate Next Round** - Click button after completing each round
5. **Playoffs** - After 5 rounds, top 4 advance automatically
6. **Champion** - Complete semifinals and final

## 🌍 Language Toggle

Click the tennis ball (🎾) in the top-right corner to switch between English and Swedish.

## 💾 Data Persistence & Sync

- **Google Sheets Integration** - All data syncs to a Google Sheet in real-time
- **Multi-Device Support** - Everyone sees the same tournament data
- **Auto-saves** after every change (to both Google Sheets and local browser)
- **Auto-sync** - Updates from other devices every 10 seconds
- **Sync status** indicator (top-left corner) shows save status
- **Offline fallback** - localStorage backup if connection drops
- **Reset button** at bottom to start fresh tournament

## ⚠️ Important Notes

- **Google Sheets backend** - Data syncs across all devices
- **Real-time updates** - Changes appear on all devices within ~10 seconds
- **Backup** - All data stored in your Google Sheet with timestamp history
- **View/Edit** - You can view and manually edit data in the Google Sheet
- **Network required** - Needs internet connection to sync (works offline with last cached state)

## 🏆 Tournament Structure

- **Swiss System**: 5 rounds, players paired by similar points
- **No eliminations** until playoffs
- **Top 4 advance** to semifinals
- **1st vs 4th, 2nd vs 3rd** in semifinals
- **Winners meet** in championship final

## 🎨 Design

- Classic tennis club colors (forest green, championship gold)
- Tennis ball yellow-green accents
- Professional typography
- Responsive grid layout
- Smooth animations

## 🔧 Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- localStorage for data persistence
- Responsive design (mobile-friendly)
- Modern browser required (Chrome, Firefox, Safari, Edge)

## 📝 Support

For issues or questions, contact your tournament organizer.

---

**GIH Open** - The Swedish School of Sport and Health Sciences unofficial annual Tennis tournament
