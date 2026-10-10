# NYC Property Intelligence

A static, mobile-friendly NYC property research and preliminary underwriting workspace.

## Current capabilities
- Search NYC PLUTO records by address or 10-digit BBL.
- Display lot/building area, floors, built FAR, zoning fields, units, and year built when available.
- Query NYC Rolling Sales public data and show a basic comparable-sale screen with sale price, reported gross square feet, and price per square foot.
- Calculate a transparent residual-land-value screen from user-entered assumptions.
- Label public-data limitations and avoid treating missing fields as verified negatives.

## Data sources
- NYC PLUTO / MapPLUTO dataset ID: `64uk-42ks`
- NYC Rolling Sales dataset ID: `usep-8jbt`
- NYC Open Data Socrata API: `https://data.cityofnewyork.us/resource/`

## Important limitations
This is a first-pass research tool, not an appraisal, title report, zoning opinion, legal-occupancy determination, architect's test fit, or lender quote. Sale records require manual review for arm's-length status, property type, condition, legal area, and comparability. Verify source schemas and all material facts before investment decisions. The app does not fabricate missing records; API/schema failures are shown as errors.

## Deployment
GitHub Actions workflow deploys the repository to GitHub Pages. If Pages has not been enabled for this repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source. After the workflow succeeds, the expected site URL is:

`https://alexianelson.github.io/nyc-property-intelligence/`
