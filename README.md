# The Infinite Kitchen Pod

**Low prices. Rich, quality ingredients. Eating out, made affordable.**

**The goal is to bring the cost of food down for people who like to eat out.** The Infinite Kitchen Pod is a self-cleaning robotic kitchen that cooks restaurant meals with real, quality ingredients. The meals cost less because the kitchen is automated, not because the food is worse.

**In one sentence:** an open-hardware design for a modular, self-cleaning robotic kitchen pod that stores, cooks, washes, packs and hands off up to 90 hot meals an hour from a footprint small enough for a sidewalk or a parking spot.

**Status:** early concept. The architecture, the bill of materials, the water and power math and a full set of renders are here. No prototype has been built yet, and there are real engineering problems still open ([help wanted](#status-early-concept-help-wanted)).

![The Infinite Kitchen Pod on a city street at dusk](Images/web/09-street-pod-dusk.jpg)

### [Download the investor brochure (PDF)](https://nicedreamzapp.github.io/infinite-kitchen-pod/docs/infinite-kitchen-brochure-web.pdf)

7 pages, 3.4 MB. Also available: [full quality PDF (34 MB)](docs/infinite-kitchen-brochure.pdf) · [every number in text](docs/brochure.md) · [HTML version of the earlier brochure](https://nicedreamzapp.github.io/infinite-kitchen-pod/brochure.html)

**Live site:** https://nicedreamzapp.github.io/infinite-kitchen-pod/

| | | | |
|---|---|---|---|
| [![Brochure page 1](Images/web/brochure/page-1.jpg)](docs/infinite-kitchen-brochure-web.pdf) | [![Brochure page 2](Images/web/brochure/page-2.jpg)](docs/infinite-kitchen-brochure-web.pdf) | [![Brochure page 3](Images/web/brochure/page-3.jpg)](docs/infinite-kitchen-brochure-web.pdf) | [![Brochure page 4](Images/web/brochure/page-4.jpg)](docs/infinite-kitchen-brochure-web.pdf) |
| [![Brochure page 5](Images/web/brochure/page-5.jpg)](docs/infinite-kitchen-brochure-web.pdf) | [![Brochure page 6](Images/web/brochure/page-6.jpg)](docs/infinite-kitchen-brochure-web.pdf) | [![Brochure page 7](Images/web/brochure/page-7.jpg)](docs/infinite-kitchen-brochure-web.pdf) | |

## What the pod is

A 12 ft by 10 ft pod, 9.5 ft tall (about 120 square feet), all electric on 480V 3-phase with no gas line, that runs a full kitchen on its own:

- **Cold storage and dosing.** A refrigerated zone holds ingredient cartridges that a person restocks once a day. Load-cell dispensers portion dry and diced ingredients to about half a gram; pumps dose sauces and oils.
- **Cooking.** A 6-axis collaborative arm on a linear track works two 5 kW induction woks and a ventless multi-cook oven. Wok sear, steam, bake, pasta and cold bowls.
- **Self-cleaning.** After every meal the wok and tools get a 3-stage wash: a hot water blast, an ultrasonic sanitizer dip and a 180°F rinse. Off-peak, a full clean-in-place cycle sprays the cell down with rotating spray balls into a sloped stainless basin.
- **Packing and handoff.** Meals are heat-sealed, labeled and delivered to heated and chilled pickup lockers, a delivery vehicle bay, or a rooftop drone pad.
- **Self-contained.** A UL 710B ventless hood and UL 300 fire suppression mean no ductwork, so the pod can go where a restaurant can't.

![A robot arm tossing a stir fry in a high-heat wok](Images/web/12-high-heat-wok.jpg)

## The menu: steakhouse dinners at about half the price

Rich, quality ingredients, flame broiled to order. Every plate comes with garlic herb butter, mashed potatoes and seasonal asparagus.

| Dish | Infinite Kitchen | Traditional steakhouse |
|---|---|---|
| Ribeye | **$28** | $55 |
| Filet mignon | **$32** | $65 |
| Lobster tail | **$34** | $70 |
| Salmon | **$24** | $48 |
| Surf and turf | **$38** | $85 |
| Catch of the day | **$26** | $52 |

Steakhouse prices are illustrative comparisons from the brochure, not quotes from a specific restaurant.

| | |
|---|---|
| ![A robot arm placing a ribeye on an electric infrared charbroiler](Images/web/13-flame-grill-ribeye.jpg) | ![Steak, lobster and salmon](Images/web/14-steak-lobster-salmon.jpg) |
| **980°F infrared charbroiler, all electric, no gas hose** | **Ribeye, filet, salmon and lobster tail** |

## What it can cook

<img src="Images/web/17-what-we-can-cook.jpg" width="420" alt="What We Can Cook: flame charbroiled American, Asian wok, seafood and global bowls" align="right">

- **Flame charbroiled American:** ribeye, burgers, chicken
- **Asian wok:** pad thai, orange chicken, fried rice
- **Seafood:** lobster tail, salmon, shrimp
- **Global bowls:** gyro, burrito and Mediterranean bowls

One pod switches between a charbroiler, two woks and a multi-cook oven, so a single menu can cover a steakhouse, a wok bar and a bowl shop.

<br clear="right">

## Cheaper meals, same good food

A big share of what you pay for when you eat out is the kitchen around the food: rent, buildout and staff. The pod shrinks all three and keeps spending on ingredients.

| | |
|---|---|
| **$12** | average meal price in the operating model (estimate) |
| **28%** | of every ticket goes to food and packaging, so ingredients stay a priority |
| **About $0.53** | of labor per meal: one fleet tech covers five pods (estimate) |
| **90 meals an hour** | peak, about 1,200 a day |
| **±0.5 g** | portion accuracy, the same recipe every time |

And for whoever owns one:

| | |
|---|---|
| **$185,000** | target turnkey price (early estimate) |
| **4.5 months** | simple payback in the brochure model |
| **$41,500** | estimated net operating profit per month at 750 meals a day |
| **$72,450** | estimated direct hardware BOM |

These numbers come from the revised brochure and are early estimates. The audit document uses more conservative figures, and reconciling the two is one of the [open issues](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/8).

## Customized to your needs

One chassis, four configurations, same robot, your brand.

![Configuration sheet: glass curbside, solid stainless mall, compact kiosk and gutted kitchen retrofit](Images/web/16-customization-configs.jpg)

1. **Glass curbside:** high visibility, QR ordering, sidewalk deployment
2. **Solid secure:** malls and nighttime; metal covers the windows, no glass
3. **Compact kiosk:** 1.8 m x 2.4 m for campuses and transit hubs
4. **Gutted retrofit:** modules drop into a failed kitchen shell, 48 hour install, no construction

## Two ways to get one

The [brochure](docs/infinite-kitchen-brochure-web.pdf) lays out two plans (early estimates):

- **Plan 1, turnkey purchase:** $185,000 per pod upfront, a $1,200 a month cloud platform fee, 4.5 month simple payback.
- **Plan 2, robot as a service:** $15,000 for site setup and commissioning, then $8,500 a month covering hardware, software, telemetry, maintenance and replacement parts.

Either way the operator's costs stay low, so the menu prices can too.

## Gallery

| | |
|---|---|
| ![Street pod at dusk](Images/web/09-street-pod-dusk.jpg) | ![Glass-walled street pod](Images/web/01-pod-overview.jpg) |
| **Street pod at dusk** | **Glass walls** |
| ![High-heat robotic wok](Images/web/12-high-heat-wok.jpg) | ![Ingredient dispensing and cooking line](Images/web/04-robot-arm-woks.jpg) |
| **High-heat wok** | **Ingredient dispensing** |
| ![Gutted kitchen, before and after](Images/web/10-retrofit-before-after.jpg) | ![The pod inside a gutted kitchen](Images/web/11-pod-in-gutted-kitchen.jpg) |
| **Retrofit, before and after** | **Pod in a gutted kitchen** |
| ![Full system cutaway](Images/web/08-cutaway-all-parts.jpg) | ![Clean-in-place wash station](Images/web/05-wash-station.jpg) |
| **Full system cutaway** | **Wash station** |
| ![Heated and chilled pickup lockers](Images/web/03-pickup-lockers.jpg) | ![Drone and vehicle delivery](Images/web/06-drone-car-delivery.jpg) |
| **Pickup lockers** | **Drone and car delivery** |
| ![Ribeye on the infrared charbroiler](Images/web/13-flame-grill-ribeye.jpg) | ![Glass curbside pod](Images/web/18-glass-cube-pod.jpg) |
| **Flame grill** | **Glass curbside configuration** |

Web-sized images are in [`Images/web/`](Images/web/). The full resolution files in [`Images/`](Images/) are the earlier concept renders the brochure uses.

## How it compares

Other companies are automating kitchens, but with closed designs, and most automate one station inside a kitchen someone already built. As far as we can find, nobody has published an open, end-to-end design like this one.

| Company | What it does | Price |
|---|---|---|
| Miso Robotics (Flippy) | Robotic fry station inside an existing kitchen | About $3,000 per month, rented ([source](https://www.fox2detroit.com/news/white-castle-hiring-robots-to-give-the-right-tools-for-serving-more-hot-and-tasty-food)) |
| Botinkit (ChefBot) | Wok cooking robot inside an existing kitchen | $43,000, or a monthly plan ([source](https://www.robotlab.com/store/botinkit/)) |
| Hyper Food Robotics | Containerized robotic restaurant | Not published |
| Nala Robotics (Pizzaiola) | Robotic pizza and multi-cuisine kitchen | Lease from about $7,000 per month, reported 2022 ([source](https://fortune.com/2022/10/18/tech-forward-everyday-ai-robots-pizza/)) |
| Moley Robotics | Dual-arm robotic kitchen for luxury homes | About $335,000, reported at launch ([source](https://thespoon.tech/moleys-robotic-kitchen-goes-on-sale/)) |

The pod is the whole kitchen, it is owned instead of rented, and it is open. All three keep menu prices low while the ingredients stay good. Details: [docs/competition.md](docs/competition.md).

## Deploy as a pod, or drop it into an existing kitchen

| | |
|---|---|
| ![Before and after: a gutted commercial kitchen turned robotic](Images/web/10-retrofit-before-after.jpg) | ![The pod installed inside a gutted kitchen](Images/web/11-pod-in-gutted-kitchen.jpg) |

- **Into a second-generation kitchen.** A gutted restaurant space that still has its hood, fire suppression, grease trap and plumbing saves an estimated **$67,000 to $238,000** in buildout. The cooking cell drops in and reuses all of it.
- **As a self-contained pod.** Its own ventless hood and clean-in-place system let it sit on a sidewalk or in a parking lot, with no ductwork, no walls and no restaurant lease.

Either way, the money not spent on buildout and rent is money that does not have to be charged for the meal. Details: [docs/retrofit-existing-kitchen.md](docs/retrofit-existing-kitchen.md).

## Docs

| File | What it is |
|---|---|
| [docs/infinite-kitchen-brochure-web.pdf](docs/infinite-kitchen-brochure-web.pdf) | The 7-page investor brochure, web size (3.4 MB) |
| [docs/infinite-kitchen-brochure.pdf](docs/infinite-kitchen-brochure.pdf) | The same brochure at full quality (34 MB) |
| [docs/brochure.md](docs/brochure.md) | Every number and claim from the brochure in text: menu prices, configurations, plans, cuisines |
| [brochure.html](brochure.html) | HTML version of the earlier 6-page brochure (print to PDF from the browser) |
| [docs/revised-cad-bom.pdf](docs/revised-cad-bom.pdf) | Revised CAD layout, BOM, P&L and sanitation protocol (2 pages) |
| [docs/technical-audit.md](docs/technical-audit.md) | Engineering and financial audit: water heating, arm timing, BOM, P&L, hood and fire, materials, allergens |
| [docs/cip-spec.md](docs/cip-spec.md) | Clean-in-place sanitation hardware and regulatory blueprint |
| [docs/cip-hardware-sanitation-system.html](docs/cip-hardware-sanitation-system.html) | Interactive 3D view of the clean-in-place hardware ([open it live](https://nicedreamzapp.github.io/infinite-kitchen-pod/docs/cip-hardware-sanitation-system.html)) |
| [docs/competition.md](docs/competition.md) | How the pod compares to commercial kitchen robots, with sourced prices |
| [docs/retrofit-existing-kitchen.md](docs/retrofit-existing-kitchen.md) | Pod vs. dropping into an existing second-generation kitchen |

## Status: early concept, help wanted

This is a concept with real open problems. Each one below is a [help wanted issue](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues?q=is%3Aissue+label%3A%22help+wanted%22). If you know the field, jump in.

1. **[Hot water buffer sizing](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/1).** Each full CIP run needs about 142 gallons of 180°F water and the design carries a 75 gallon tank.
2. **[Single-arm, dual-wok throughput](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/2).** The 38 second per meal cycle works on paper and needs a prototype to prove it.
3. **[BOM and price](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/3).** The BOM and the $185k price are early estimates from list prices, not quotes.
4. **[Hood and fire suppression](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/4).** Integration details for the UL 710B ventless hood and UL 300 suppression.
5. **[Material choices](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/5).** Induction wok metal, peristaltic tubing vs. diaphragm pumps, and the arm's washdown rating.
6. **[Allergen carryover](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/6).** The wash protocol needs real carryover testing.
7. **[Certification path](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/7).** NSF 4/7, UL 197/471/508A, R15.06 / ISO 10218.
8. **[Reconcile the numbers](https://github.com/nicedreamzapp/infinite-kitchen-pod/issues/8).** Footprint, amperage and finance figures differ across the docs.

## License

- **Hardware design** (layouts, CAD, BOM and hardware specifications): [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0)
- **Documentation and images** (this README, the site, the brochure, `docs/` and `Images/`): [Creative Commons Attribution-ShareAlike 4.0](LICENSE-DOCS) (CC BY-SA 4.0)

Copyright Matt Macosko.
