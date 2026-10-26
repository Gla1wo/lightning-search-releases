# Lightning Search releases

Public files for Lightning Search, the sound library search for Reaper. GitHub Pages
serves this repository at <https://gla1wo.github.io/lightning-search-releases/>.

- `latest.json`: the newest version. The Lightning Search helper reads it once a day
  (it can be turned off in Settings > General) to say when an update is out. The request
  sends nothing about you or your library.
- `guide.html`: the user guide, the online copy of the one installed with the program.

Download Lightning Search from its Gumroad page.

## Releasing
See `docs/release.md` in the main repository. `latest.json` holds
`{"version": "<semver>", "url": "<download page>", "notes": "<one line>"}`, and the URL
must be an https page on gla1wo.github.io, github.com or gumroad.com.
