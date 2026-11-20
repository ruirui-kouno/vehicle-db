# Japan Kei Truck Price DB (Phase 1)

Public URL: https://ruirui-kouno.github.io/vehicle-db/

English static site comparing Japanese kei truck auction prices (public aggregates),
estimated US landed costs, and US dealer asking prices for the five most-imported
kei truck models. Includes an in-browser landed-cost calculator.

Data policy: public sources only. No member-only auction system data (USS / AI-NET)
is used or republished. Figures are aggregates and estimates collected 2026-11-20,
with sources cited on the page.

Regenerate: `python3 ../build_site.py` (reads ../sample-db.csv)
Publish: `python3 ../publish_vehicle.py`
