# How RELOC8 Works

## The Core Problem with Existing Tools

General AI assistants will give you an answer about where to live, but it depends heavily on how you phrase the question, it is not grounded in real local data, and there is no consistent scoring framework. You get a different answer every time.

Search engines give you fragmented results. You end up cross-referencing 10 tabs yourself.

Property portals (Rightmove, Zoopla) focus on price and availability. They do not factor in total cost of living, safety, transport, or whether the area fits your lifestyle.

RELOC8 brings all of this together in one place with a standardised scoring approach.

---

## The Scoring Algorithm

When you submit your preferences, the algorithm evaluates each candidate neighbourhood across six dimensions:

| Dimension | What it measures |
|---|---|
| Affordability | Rent-to-income ratio, monthly leftover after essentials |
| Safety | Local crime data, trend direction |
| Transport | Commute time to work, public transport coverage, walkability |
| Schools | Ofsted ratings, proximity, catchment areas (if children flagged) |
| Lifestyle and Amenities | Gyms, restaurants, green space, entertainment |
| Community | Proximity to religious institutions, cultural community presence |

Each dimension is scored 0 to 10. The final match score is a weighted average based on the priorities you set at the start. If you set transport as a 9/10 priority and safety as a 5/10, the algorithm weights accordingly.

---

## Financial Projections

Beyond the match score, RELOC8 calculates:

- Monthly rent estimate for your household type in that area
- Estimated utilities, transport costs, food, and entertainment based on local data
- Rent-to-income ratio with a health flag (green below 30%, amber 30-40%, red above 40%)
- Monthly leftover estimate after all projected costs

This gives you a realistic picture of what your finances look like in each neighbourhood, not just what the rent is.

---

## Why the Scores Are Transparent

We made a deliberate choice to show the breakdown behind every score. If RELOC8 recommends one area over another for a young professional on a given salary, you can see exactly why. You can disagree with the weighting and adjust your priorities to rerun the analysis.

---

## Data Sources

RELOC8 pulls from verified, regularly updated datasets:

- ONS (Office for National Statistics) cost of living data
- Police.uk crime statistics
- National Rail and local transport APIs
- Ofsted school inspection data
- OpenStreetMap amenity data
- Rightmove and Zoopla rental price indices
