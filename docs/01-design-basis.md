# 01 · Establish the design basis

Before modelling, create a small basis record. A drawing that looks correct can still have mixed
units, an assumed datum or an outdated reference surface.

| Record | Evidence to retain | Stop and resolve when |
|---|---|---|
| Horizontal units and coordinate reference | Survey metadata or agreed project basis | Units or reference are unknown |
| Vertical units and datum | Survey control and benchmark schedule | Elevations come from mixed datums |
| Software and file versions | Application release and issue identifiers | A dependency cannot be traced |
| Existing and proposed surface purpose | Named source and boundary | Surface names alone are the only evidence |
| Design criteria | Approved project requirements | A generic internet value is being treated as an approval |
| Quantity method | Surface comparison or section areas, with basis | Quantities from unlike methods are mixed |

The synthetic DEMO-001 exercise uses metres and an arbitrary local datum. It is not a surveyed site.
Its station areas are supplied teaching values; there is no underlying CAD model.

Suggested naming convention for the exercise: `DEMO-001_EG_R01` for existing ground and
`DEMO-001_FG_R01` for proposed ground. The names are examples, not an industry mandate.
Record source, date and intended use separately from a convenient object name.
