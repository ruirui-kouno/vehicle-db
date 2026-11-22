# Japan Kei Truck Price DB (Phase 1)

Public URL: https://ruirui-kouno.github.io/vehicle-db/

English static site comparing Japanese kei truck auction prices (public aggregates),
estimated US landed costs, and US dealer asking prices for the five most-imported
kei truck models. Includes an in-browser landed-cost calculator.

Also carries a "High-Value Desk" section: order-based sourcing of high-value JDM
performance cars (GT-R R34/R33, Silvia S15, Lancer Evolution IV–VII, Supra JZA80),
prioritising models/specifications never officially sold in the US, with published
auction averages vs US sold medians, the order/deposit/condition-standard terms,
and a B2B-only note for JDM-only parts. All figures are public aggregates and
assumption-based estimates, labelled as such on the page.

Also carries `eligibility-2027.html` (hand-written, not generated): a month-by-month
2027 US 25-year-rule eligibility calendar for the last 2002 builds (R34, S15, Supra,
RX-7, Evo VII, WRX STI GDB, NSX, JZX110, kei trucks), with a mailto alert-signup
(subject "2027 Eligibility Alert") so registrations can be counted in Gmail.
Linked from the top of index.html and listed in sitemap.xml. Regenerate index.html
with build_site.py, then publish both files with publish_vehicle.py.

Data policy: public sources only. No member-only auction system data (USS / AI-NET)
is used or republished. Figures are aggregates and estimates collected 2026-11-20,
with sources cited on the page.

Regenerate: `python3 ../build_site.py` (reads ../sample-db.csv)
Publish: `python3 ../publish_vehicle.py`
