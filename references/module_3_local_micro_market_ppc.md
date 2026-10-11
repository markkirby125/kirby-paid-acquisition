# Module 3: Local Micro-Market PPC — Small-Town Google Ads Under Low Volume

*Source: Grow My Ads, "How to Run Google Ads in a Small Town (Low Volume)" (11:45). Applies to service-area businesses and micro-markets where monthly search volume is low (rule of thumb: <50 searches/month on core terms). October 2026.*

This module overrides standard Google Ads advice (and parts of Module 1's defaults) when conversion volume can never train the algorithms.

### **3.1 The "Presence or Interest" Location Trap**

Google Ads defaults location targeting to **"Presence or interest"**. In a small town, out-of-towners searching general terms silently bleed the local budget.

**Mandatory rule:** force location targeting strictly to **"Presence"** — people physically in or regularly in the target geo. This is a settings-level default trap: it must be verified at campaign creation, never assumed.

### **3.2 Why Smart Bidding Fails in Low-Volume Geos**

Automated Smart Bidding (Target CPA, Target ROAS, Max Conversions) requires **30–50 conversions per month** to train its machine learning. In low-volume local markets that floor is unreachable, so Smart Bidding either starves delivery entirely or aggressively bids on broad, irrelevant search queries to chase conversion volume it can otherwise never find.

### **3.3 The Target Impression Share Protocol**

In small towns, set bidding to **Target Impression Share**, targeting **"Absolute Top of Page"** or **"Top of Page"**. Unlike Smart Bidding, Target Impression Share functions reliably **without** historical conversion volume — position, not conversion prediction, is the control surface.

**Essential safeguard:** always set a strict **Max CPC bid limit** to prevent automated runaway bidding. Target Impression Share without a cap will happily pay absurd CPCs for the top slot.

### **3.4 Intent Isolation: Exact & Phrase Only**

**Broad Match is forbidden** in low-volume markets. Restrict campaigns to **Exact and Phrase Match** high-intent commercial keywords (e.g., `[emergency plumber in town]`). The negative-keyword shield from Module 1 §1.3 still applies in full — low volume makes every wasted click proportionally more expensive.

### **3.5 The Matched Locations Audit**

Regularly audit the **"Matched locations"** report to confirm clicks are physically originating within the designated town boundaries. Drift here means the Presence setting (§3.1) was reverted or circumvented — treat it as a recurring monthly check, not a one-time setup.

### **3.6 Cross-Skill Routing**

- Organic local counterpart (GBP loop, location pages) → `../../kirby-local-seo/SKILL.md`.
- The $100 local-launch paid-validation step → `../../kirby-scrappy-local-launch/SKILL.md` (Phase 3, Step 7).
- Bridge landers for the winning queries → Module 1 §1.5 and Module 4.
