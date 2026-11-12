# Neutral Dive Coach, offline build (v22, 2026-10-20)

Includes everything through v20: Terms tab (31 entries), My learnings, Quick dive, Master Scuba Diver card, and EFR first aid (Bleeding, shock, spinal injury; SAMPLE) on the SOS page, plus v21 dive-trip emergencies (CPR, near-drowning, marine stings and punctures, hypothermia, heat illness, choking), and v22 Thailand/Philippines switch on the SOS Call list.

## Update an existing install (GitHub Pages)
1. In the app you are using now: Me tab > Backup > copy to clipboard. Keep the text somewhere safe.
2. In your GitHub repo, replace index.html, sw.js, manifest.json and the icons folder with these files. Commit.
3. Wait a minute for Pages to publish, then open the site in Safari once while online. Close and reopen the home-screen app. The new service worker (cache neutral-v22-2026-10-20) replaces the old one.
4. Check the SOS page has the Thailand / Philippines switch. Your data stays, because the address did not change.

## New install
Upload the folder to a GitHub Pages repo, open the URL in Safari, Share > Add to Home Screen, then open it once online. If moving from the artifact or another address, use clipboard backup there and paste-restore here: data does not move between addresses.

## Notes
- Works fully offline after the first online open. Fonts cache on first use; system fonts are used until then.
- Ask Claude is hidden offline; export uses the clipboard.
- For the next update: replace index.html and change CACHE in sw.js.
