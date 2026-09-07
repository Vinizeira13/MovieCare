# MovieCare

**A React movie-discovery project exploring catalog browsing and detail views.**

MovieCare's original interface presents popular titles from The Movie Database (TMDB) and opens a detail view when a film is selected. This repository preserves an early project snapshot and its original screenshots.

> **Repository status:** application source files are not present in the current default branch. The screenshots document the earlier interface; this checkout cannot currently run the application.

## Interface archive

### Movie catalog

<img width="900" alt="Historical MovieCare interface showing a movie catalog" src="https://user-images.githubusercontent.com/47362960/158064199-a45b266a-958d-465a-ad14-a2acfbb96f94.png">

### Movie details

<img width="900" alt="Historical MovieCare interface showing movie details" src="https://user-images.githubusercontent.com/47362960/158064211-f333a1f4-6e5a-4eef-b2d3-cd679d820dbd.png">

## Recorded stack

The committed [`package.json`](./package.json) describes a Create React App project using:

- React 17 and React Router 6 for the interface and navigation.
- Axios for HTTP requests.
- Styled Components for styling.
- Swiper for carousel interactions.
- React Testing Library for the original testing toolchain.

These are recorded dependencies, not evidence of source code or passing tests in this snapshot.

## Repository contents

| File | Purpose |
| --- | --- |
| `README.md` | Project context and historical interface captures |
| `package.json` | Original dependencies and scripts |
| `package-lock.json` | Dependency resolution snapshot |
| `teste.http` | Original API request scratch file |

The request example uses `{{tmdbApiKey}}`. Supply it through your HTTP client's private environment; never replace it with a credential in committed source.

## Running the project

The manifest retains `npm start`, `npm run build` and `npm test`, but the required `src/` and `public/` application directories are missing. Installing dependencies alone will not restore them.

To make this project runnable again, restore the application source, document its TMDB configuration, review the older dependencies and then validate catalog loading, navigation and failure states. Until then, treat MovieCare as an interface archive rather than a working starter.

## Attribution and reuse

The original project description identifies TMDB as the movie-data source. Movie artwork and third-party content remain the property of their respective owners; this project does not imply endorsement by TMDB. The original screenshot references are preserved above.

No standalone license file is included. Confirm code and asset reuse rights before redistribution.
