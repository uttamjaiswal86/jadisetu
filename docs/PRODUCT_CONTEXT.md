# JadiSetu — Product Context

This document records durable product context for future planning and implementation. It captures the founder-provided ecosystem note; competitor descriptions below are research hypotheses supplied for investigation, not verified current facts.

## Product identity

- **Working name:** JadiSetu (जड़ीसेतु)
- **Meaning:** a bridge across the medicinal-herb value chain, from cultivation to quality-controlled supply and buyers.
- **Geographic intent:** rooted in the initial Dumka/Jharkhand origin, while designed for adoption across India and possible international sourcing or trade. Do not bake Dumka or one state into the product's technical boundaries, identifiers, or brand architecture.
- **Positioning:** a digital operating platform for the medicinal and Ayurvedic crop value chain, built around a common data backbone and connected workflows. It is not just a crop-management app or another plant-listing marketplace.
- **Product principle:** win by connecting a traceable crop lifecycle and solving real participant problems. Avoid adding features only because they sound useful.

## Lifecycle vision

The long-term chain may span:

`Farmer/FPO → Land → Soil → Crop recommendation → Cultivation/training → Monitoring/risk → Insurance partner → Yield/harvest → Quality/testing → Grading/processing → Packaging/traceability → Inventory/trading → Buyer/manufacturer/exporter → Logistics/payment`

Phase 1 proves the narrower managed lifecycle already defined in [PHASE1_DISCOVERY.md](PHASE1_DISCOVERY.md): farmer, land, soil, rules-based crop recommendation, cultivation plan, crop batch, training/monitoring, harvest, quality, packaging, buyer requirements, and basic procurement records. Later modules must be staged and justified; this long-term vision is not authorization to expand the Phase 1 build.

## Ecosystem participants to consider over time

| Participant | Potential needs |
|---|---|
| Farmer | Land and soil records, crop choice, planting material, training, field support, monitoring, insurance status, harvest, quality, buyers, payments and history. |
| FPO / farmer group | Member management, aggregated acreage and plans, input/harvest aggregation, quality, buyer demand, procurement, payments and traceability. |
| Agronomist / field coordinator | Assigned portfolio, visits, soil and crop context, observations, treatment follow-up, yield ranges and alerts. |
| Laboratory / testing agency | Sample requests, chain of custody, test methods/results, certificates and crop-specific grades. |
| Trader / processor | Available quantity, grade, location at suitable granularity, supplier, processing records, inventory and traceability. |
| Manufacturer / Ayurvedic company | Demand planning, required quantity/quality/date, supplier network, procurement, traceability and supply reliability. |
| Exporter | Quality evidence, batch traceability, packaging, inventory and export documentation. |
| Insurance provider | Authorized access to farmer/land/crop and relevant history through controlled integrations, if agreements and regulations permit. The insurer remains the risk carrier and decision maker. |
| Logistics provider | Pickup, destination, package/quantity, delivery status and any required handling conditions. |
| Government / institutional program | Potential schemes, training, certifications or market information, only through confirmed data-sharing arrangements and available interfaces. |

Design participant-specific access on shared domain records. A common platform does not mean every participant sees all data or every participant must use the same interface.

## Ecosystem and competitor context to investigate

The founder-provided note identified these names as examples of ecosystem capabilities or market segments to study:

- **e-CHARAK / NMPB ecosystem:** medicinal-plant discovery, information, market discovery and stakeholder resources.
- **Herbical:** private B2B herbal-sector connections and discovery.
- **GeeCom:** farmer/FPO/tribal participation and buyer connectivity.
- **Aushadhi Mandi:** regional medicinal-plant trading and discovery.
- **HEPAI:** industry networking, training, value-chain and market-development activity.
- **Indian Herbs Online, Konkuwan Herbs,** and relevant government medicinal-plant systems: additional research leads.

These are leads, not verified descriptions of current product capabilities, integrations, or commercial status. Before making strategic claims, research current public information and, where possible, speak with participants. Maintain a matrix that labels each capability **confirmed**, **probable**, or **unknown**, includes evidence and date checked, and distinguishes an organization's activity from a software feature.

| Capability to compare | JadiSetu Phase 1 | Potential later scope |
|---|---|---|
| Farmer/FPO onboarding | Farmer records; FPO association support in data model | Full FPO/member operations and community/collector networks |
| Land and soil | Land records, optional GPS, soil-test history | Broader GIS and historical land intelligence |
| Crop choice | Expert-configured transparent rules | Validated predictive models, only after data and approval |
| Cultivation and health | Plans, training, observations, treatment history | Expanded advisory, weather/risk support, optional image analysis |
| Yield and insurance | Manual yield ranges; insurance status record | Validated forecasts and licensed-provider integrations |
| Quality and traceability | Harvest lots, quality records, grading and package traceability | Lab integrations, processing transformations and richer chain of custody |
| Marketplace and procurement | Managed buyer requirements and basic order workflow | Regional listings, offers, contracts and procurement network if validated |
| Inventory, logistics, finance | Not Phase 1 | Integrations or modules based on partner need and business case |
| Manufacturer/exporter demand | Basic buyer records and requirements | Demand planning, contract cultivation and supply forecasting |
| Analytics / AI/ML | Operational metrics and data foundation | Forecasting or decision support after validation and consent/governance |

Do not claim that a named competitor lacks a feature without current evidence. The comparison is for product discovery, not a feature-copy checklist.

## Competitive and integration principles

1. For each proposed module, identify the participant problem and investigate whether an existing government, commercial, institutional, or partner service already addresses it.
2. Decide whether to build, integrate, exchange data, refer, partner, or defer. Do not assume external APIs or data-sharing rights exist.
3. Preserve the useful role of specialist systems: for example, a laboratory owns its test result, an insurer owns underwriting/claims decisions, and a manufacturer's ERP may remain its inventory authority.
4. Differentiate through a connected, traceable workflow and dependable quality-controlled supply only if farmer, FPO, trader, processor, and manufacturer research validates that need and advantage.
5. Treat historical farmer, land, soil, crop, cultivation, weather (if lawfully sourced), health, treatment, yield, quality, price, buyer and outcome data as sensitive strategic data. Collect and use it only with suitable purpose, access control, consent/contractual basis, retention and governance.

## Long-term questions the platform may answer

- **Farmer:** What is suitable to grow on this land, given known conditions?
- **Agronomist:** What cultivation and follow-up does this crop need?
- **Insurer:** What authorized evidence is available to assess risk under its own process?
- **Buyer:** What material may be available, when, in what quantity and with what verified quality?
- **Manufacturer:** Can supply meet a required quantity, specification and date?

These are future decision-support questions. Phase 1 should collect reliable operational records and must not imply precise predictions or guarantees.

## Phased direction

1. **Phase 1 — Managed crop lifecycle:** farm/land/soil through cultivation, monitoring, harvest, quality, traceability and managed buyer workflow.
2. **Phase 2 — Connected operations:** evaluate FPO functionality, inventory, logistics, licensed insurance integrations, payments and historical analytics.
3. **Phase 3 — Supply network:** evaluate manufacturer demand, contract cultivation, advanced procurement and supply planning.
4. **Phase 4 — Intelligence:** evaluate suitability/yield/quality/risk/demand/price models and image support after sufficient validated data, governance and field evidence exist.

Each phase requires user research and a business case. Future capabilities are options, not commitments.
