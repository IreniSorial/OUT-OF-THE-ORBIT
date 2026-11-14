# OUT OF THE ORBIT — Planetary Analog Explorer

**NASA Space Apps Challenge 2026**  
A browser-based educational research prototype for exploring Earth analog environments and comparing them with selected planetary locations across the Solar System.

## Project overview

OUT OF THE ORBIT helps users explore how real environments on Earth can inform the study of other worlds. It presents descriptive profiles of Earth field sites and planetary targets, then provides a structured comparison workspace that explains similarities, differences, scientific relevance, and limitations.

The project is an educational exploration tool. It does not claim that an Earth location is an exact replica of a planetary environment, and it is not intended for mission planning or operational decisions.

## Main features

- **Earth sites:** Browse and search the Earth analog site profiles, including their location, landforms, geology, environmental context, water context, scientific relevance, limitations, and cited sources.
- **Planetary targets:** Explore profiles for the Moon, Mars, and additional Solar System destinations.
- **Deep comparison:** Select one Earth site and one planetary target and compare them across six dimensions:
  1. Terrain & landforms
  2. Geology & minerals
  3. Temperature & climate
  4. Water & ice
  5. Erosion & processes
  6. Operations & instruments
- **Evidence and limitations:** Each comparison explains the available descriptive evidence and highlights important mismatches or uncertainties.
- **Percentage-based similarity display:** The interface is designed to show a percentage only when both locations have comparable, source-backed measurements for the same feature, expressed in compatible units and supported by documented uncertainty and citations. The current profile data is primarily descriptive and does not provide paired quantitative measurements across the six dimensions. For that reason, the current version displays **“Not calculable”** / **“N/A · insufficient comparable data”** rather than inventing percentages.
- **Visuals:** Uses built-in conceptual illustrations and can retrieve location images from NASA's Image and Video Library or Wikimedia Commons when internet access is available. Illustrations are not real photographs.
- **Display settings:** Includes a light-mode option in the settings panel.

## How to use

1. Extract the ZIP archive.
2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox, or Safari).
3. Use **Earth sites** to search and open an Earth location profile.
4. Use **Other worlds** to browse planetary target profiles.
5. Open **Compare**, choose an Earth site and a planetary target, then select **Run deep comparison**.
6. Expand each comparison dimension to read the evidence, context, and limitations.
7. Use **Settings** to switch the display to light mode if preferred.

No installation or build step is required. An internet connection is recommended for remotely retrieved images; the site includes local conceptual illustrations as visual fallbacks.

## Scientific approach and interpretation

The comparison is organized around six dimensions relevant to planetary analog research. The profiles summarize documented characteristics and explain where an Earth environment may be useful for studying a planetary feature or field procedure.

A visual or process-level resemblance is not proof of identical composition, origin, age, climate, gravity, atmospheric pressure, radiation exposure, water history, or operational conditions. Each profile therefore includes limitations and avoids treating an Earth analog as a complete planetary equivalent.

### Similarity percentages

A percentage is meaningful only when the compared locations have measurements for the same variable, in compatible units, with adequate provenance and uncertainty information. Descriptive labels such as “strong,” “partial,” or “weak” cannot be converted into percentages without an explicit and justified scoring method.

In this version, the available records do not provide sufficient paired quantitative measurements to calculate defensible scores for the six comparison dimensions. Missing or non-comparable measurements are therefore left unscored. No overall percentage is calculated when no dimension has a valid paired score.

## Data and references

- The site contains profile-level scientific descriptions and source links in its built-in data records. Open an individual profile to view its cited references.
- The image lookup integrations use the **NASA Image and Video Library API** (`images-api.nasa.gov`) and the **Wikimedia Commons API** (`commons.wikimedia.org`) when available.
- NASA and Wikimedia images remain subject to the rights, credit, and usage information supplied by their respective source records. Check the original source page before reusing an image outside this project.
- The project does not bundle a separate numerical measurement dataset for calculating cross-environment similarity percentages.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Fetch API for optional remote image retrieval
- NASA Image and Video Library API
- Wikimedia Commons API

## Project files

```text
OUT_OF_THE_ORBIT_Percentage_Comparison.zip
└── index.html
```

This README describes the current project package. The ZIP contains the website as `index.html`.

## Important limitations

- The website is a scientific and educational prototype, not a validated planetary simulation.
- Profile descriptions and cited sources should be checked against the original publications before being used as research-grade measurements.
- Remote image retrieval depends on internet connectivity and third-party API availability.
- Similarity percentages remain unavailable until validated, paired quantitative measurements and a transparent scoring protocol are added.

---

**OUT OF THE ORBIT — Explore Earth. Understand other worlds.**
