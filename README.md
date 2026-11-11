# My Kekkei Genkai

**The five indicators built from ICT's logic in context: the 7–9 AM range and the first presented FVG, the London expansion and the NY PM, the weekly dealing range, the quarterly shift, and the daily and weekly gaps.**

TradingView indicators, Pine Script v6. Open source under the Mozilla Public License 2.0.

In Naruto, a **kekkei genkai** (血継限界, "bloodline limit") is an ability passed down in a clan's blood. It can't be learned from a scroll, only inherited. These five are inherited the same way: each one starts from something ICT teaches and draws it on the chart as he teaches it, and each number it shows was tested first. Three of the names are true kekkei genkai (Byakugan, Sharingan, Mangekyō). Domain Expansion (Jujutsu Kaisen) and Getsuga (Bleach) are adopted into the clan.

## The five

From the morning to the quarter:

| Indicator | What it reads | One tested number | Status |
|---|---|---|---|
| [Byakugan](byakugan/) | The 07:00–09:00 ET range with live odds on its high and low, the first presented FVG, the 07:00 displacement and suspension blocks | Price came back to the 07:00 displacement's 1 by 11:00 on 92% of 1,571 displacement days | On TradingView |
| [Domain Expansion · Hollow Purple](domain-expansion/) | London: the 02:00–02:30 domain range, its qualifier and SDs. NY PM (Hollow Purple): the 13:30 range, its −0.5 ARP and SDs, the final hour and the MOC macro | Where the 13:59 close sits in the PM range: up first 12% → 89%, bottom to top octant (6,333 sessions) | On TradingView |
| [Getsuga · Tenshō & Jūjishō](getsuga-tensho/) | The week as a fib from Friday (1) to Monday (0): Shikai mids (Tenshō) or first presented FVG CEs (Jūjishō), in eighths with SDs | Level odds by 16:59: Brier 0.168 → 0.099 out of sample (1,187 weeks) | Not yet published |
| [Sharingan](sharingan/) | ICT's quarterly shift and IPDA data ranges: the 60 / 40 / 20 look back, the +20 / +40 / +60 cast forward, structure and Quarterly Theory, daily down to the 1-minute | Reach odds within 20 units: Brier 0.150 → 0.117 on M15 (2025–26) | Not yet published |
| [Mangekyō](mangekyo/) | Daily or weekly FVGs, volume imbalances and suspension blocks: the gap price is in graded in eighths, PO3 candles right of price | First touch held the far edge 49% vs 45% for the same candles without a gap (t 3.7) | Not yet published |

Each folder has:
- the script;
- a README;
- its TradingView publication text;
- `images/` (mock-ups);
- `research/` (the scripts behind the odds; no market data).

## How each number was tested

Each figure on a card passed one rule before it was shown:
- pooled p < 0.05, with errors clustered by day or week;
- the same sign in 2018–24 and in 2025–26;
- the same sign on NQ, ES and RTY.

Two exceptions: Jūjishō was tested on NQ only (402 weeks), and Sharingan's daily level odds were walk-forward tested on NQ, ES, YM and RTY, 2014–26.

Each README also lists what was tested and not found. The research scripts read 1-minute CSVs from the original workspace. Point them at your own files to re-run.

## Seireitei

In Bleach, the **Seireitei** (瀞霊廷, "Court of Pure Souls") is the walled city at the heart of the Soul Society, where the Gotei 13 sit together. When these five are combined into one script, that script will be **Seireitei**.

It is not built yet. Two limits shape it:
- **Data requests:** together the five make 25 of the 40 a script may make.
- **Drawings:** each script gets 500 lines, 500 labels and 500 boxes, so the five will share what each now has to itself.

## Related

- [twelfth-division](https://github.com/unclehk2000/twelfth-division): indicators still in the lab.
- [hydra](https://github.com/unclehk2000/hydra), [stats-kit](https://github.com/unclehk2000/stats-kit), [pinetools](https://github.com/unclehk2000/pinetools): the tools behind the tests and the checks.

## Credits

- Concepts: ICT (Michael J. Huddleston).
- Written from scratch. Where another script was studied, its README says so.

## Licence

Mozilla Public License 2.0, see [LICENSE](LICENSE). © Unclehk2000.

*Historical frequencies, not guarantees. Nothing here is financial advice.*
