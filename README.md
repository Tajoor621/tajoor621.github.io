# NoorGull

Public index for **Tajoor Enterprises**, published at <https://tajoor621.github.io/>.

The page keeps the NoorGull name and the brass-on-ink palette of the original profile. **PhoneKey** stays the project that is ready to use: a free Android WireGuard client with no ads, no subscription, no account, and no tracking. The PhoneKey website is information and download only. A tunnel starts in the installed app, with a WireGuard profile from your own server. Xray and SSTP are not implemented.

Eleven other public projects are listed under PhoneKey. Each entry has a plain description, a link to its GitHub Pages site, and a link to its repository. Nothing is added here that is not already a public project. This page does not include a biography.

This repository does not include a license file.

## Projects

| Project | What the index says | Site | Source |
| --- | --- | --- | --- |
| PhoneKey (PhoneKey23) | Free Android WireGuard client. Ready to use. | [Site](https://tajoor621.github.io/PhoneKey23/) | [Source](https://github.com/Tajoor621/PhoneKey23) |
| Am I Scholar | Offline-first academic research and writing assistant. | [Site](https://tajoor621.github.io/Am-i-Scholar/) | [Source](https://github.com/Tajoor621/Am-i-Scholar) |
| Study Frog | Offline-first creative study workspace. | [Site](https://tajoor621.github.io/StudyFrog/) | [Source](https://github.com/Tajoor621/StudyFrog) |
| Media Manager 621 | Progressive web app for files you select. | [Site](https://tajoor621.github.io/media-manager/) | [Source](https://github.com/Tajoor621/media-manager) |
| TN-Player | Local-first Android player. Development preview. | [Site](https://tajoor621.github.io/TN-Player/) | [Source](https://github.com/Tajoor621/TN-Player) |
| My Offers (Digital-Flyer) | Neighbourhood price book. Pages hosts the introduction. | [Site](https://tajoor621.github.io/Digital-Flyer/) | [Source](https://github.com/Tajoor621/Digital-Flyer) |
| JUW-MicroSlides | Local-first microbiology lecture editor for personal study. | [Site](https://tajoor621.github.io/JUW-MicroSlides/) | [Source](https://github.com/Tajoor621/JUW-MicroSlides) |
| Khait-Kalyaan | Agriculture and rural farm business. Identity: Chota Kisan aur Mobile Gujjar. | [Site](https://tajoor621.github.io/Khait-Kalyaan/) | [Source](https://github.com/Tajoor621/Khait-Kalyaan) |
| BableTalk | On-device face-to-face conversation assistant, titled BabelTalk in the app. | [Site](https://tajoor621.github.io/BableTalk/) | [Source](https://github.com/Tajoor621/BableTalk) |
| Mera-Sukoon24 | Sukoon reading and calming tools. Self-help, not clinical care. | [Site](https://tajoor621.github.io/Mera-Sukoon24/) | [Source](https://github.com/Tajoor621/Mera-Sukoon24) |
| Autosheets | Automobile and fleet accounting. | [Site](https://tajoor621.github.io/Autosheets/) | [Source](https://github.com/Tajoor621/Autosheets) |
| My-Sheets | Daily and monthly expense tracker. The live page is titled Express Tracker Pro. | [Site](https://tajoor621.github.io/My-Sheets/) | [Source](https://github.com/Tajoor621/My-Sheets) |

The GitHub profile linked from the page is <https://github.com/Tajoor621>.

## Edit the page

All visible copy and links live in `index.html`. When a project changes:

1. Update the description so it still matches the live site. Keep project names as they are published, including Khait-Kalyaan, Mera-Sukoon24, and Chota Kisan aur Mobile Gujjar.
2. Keep both the Pages URL and the repository URL.
3. Leave PhoneKey as the featured project unless it is no longer the one ready to use.
4. Do not add a project that is not public, and do not add a personal biography.

The ordered list under “Public projects” starts at 02 because PhoneKey is 01 in the featured section. The numbers are visual. The list element itself carries the accessible numbering.

## Accessibility

- One `h1` (NoorGull), then `h2` for PhoneKey and for the project shelf, then `h3` for each later project.
- Skip link, landmarks, and a project index.
- Visible keyboard focus, including on the brass button.
- Body text, brass labels, and button text are set against the ink background at ratios above WCAG AA.
- Controls meet a 44px target height.
- `prefers-reduced-motion` turns off smooth scrolling and transitions. `prefers-contrast: more` and `forced-colors` keep borders and focus visible.
- The page still works with CSS forced into print (black on white, URLs printed beside links).

## Performance and privacy

The page is static HTML and CSS. It does not load JavaScript, analytics, cookies, or third-party fonts. Type is set with a serif and sans stack already on the device, so the original Fraunces and Outfit request to Google Fonts is gone. Icons and the social image are files in this repository.

## Preview

From this directory:

```bash
python3 -m http.server 8765
```

Open <http://127.0.0.1:8765/>. GitHub Pages serves `index.html` at the root of `tajoor621.github.io`.

## Files

| File | Role |
| --- | --- |
| `index.html` | The index |
| `favicon.svg`, `favicon.ico`, `favicon-32.png` | Browser icons |
| `apple-touch-icon.png`, `icon-192.png`, `site.webmanifest` | Home-screen icon and name |
| `og.png` | Open Graph and Twitter image |
| `robots.txt`, `sitemap.xml` | Crawling |

Social title, description, and canonical URL point at <https://tajoor621.github.io/>.
