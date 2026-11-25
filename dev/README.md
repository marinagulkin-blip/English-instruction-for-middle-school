# WordQuest environments

| Environment | GitHub Pages entry | Browser storage prefix |
| --- | --- | --- |
| Practice | `index.html` | `wordquest-v1` |
| Development | `dev/index.html` | `wordquest-dev-v1` |

Use `dev/index.html` for development and publish changes there first. Keep the classroom/practice entry at the root on the last accepted version. When releasing an approved change, apply it to the root entry without copying the development marker or the development-only header. If artwork changes during development, add it under `dev/` or use a new filename so the live practice artwork stays on its tested version.

The two entries are served by the same GitHub Pages project. Points, settings, profiles and open rounds are stored separately in the browser. A first-open profile link for practice belongs on the root URL.
