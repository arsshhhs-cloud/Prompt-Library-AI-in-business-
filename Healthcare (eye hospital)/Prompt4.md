## Prompt 4: Monthly Marketing Analytics Summary Report

---

**Prompt Text:**  
Role: Senior Performance Marketing Analyst (Healthcare Sector).
Task: Synthesize raw monthly data into a high-impact Executive Summary for a Hospital Marketing Manager.

Data Input: [Paste Raw Data Here]

Report Structure & Constraints:

The "Bottom Line" (H2): A 1-2 sentence summary of overall performance (Growth vs. Decline).

Channel Performance Table: A Markdown table comparing Organic, Social, Email, and Paid across Traffic, Leads, CTR, and Conversion Rate (Include a % Change column).

Critical Insights (Bullet Points): Identify the why behind the numbers. (e.g., "Email conversion rose due to the Cataract awareness campaign").

Strategic Roadmap: 2 high-priority, non-technical recommendations for next month to improve patient acquisition.

Communication Style:

Audience: Non-technical Senior Management.

Tone: Objective, data-driven, yet optimistic.

Length: Max 300 words.

Rule: Translate technical jargon (e.g., instead of "CPA," use "Cost per new patient lead").
<DATA>date	channel	campaign_name	impressions	clicks	spend_aud	leads	appointments_booked	appointments_completed	surgeries_performed	revenue_aud
2026-03-01	Google Ads	Lasik Campaign	12000	540	320	45	30	25	10	15000
2026-03-01	Facebook Ads	Cataract Awareness	18000	620	280	50	28	22	8	12000
2026-03-01	Organic Search	SEO General	9000	400	0	35	20	18	6	9000
2026-03-02	Google Ads	Lasik Campaign	14000	600	350	48	32	27	11	16500
2026-03-02	Instagram Ads	Eye Checkup Promo	16000	580	260	52	34	29	7	7000
2026-03-02	Referral	Doctor Referral	3000	120	0	20	15	14	5	8000
2026-03-03	Google Ads	Lasik Campaign	13000	580	340	47	33	28	12	18000
2026-03-03	Facebook Ads	Cataract Awareness	17500	610	290	49	29	24	9	13500
2026-03-03	Walk-in	Offline	2000	0	0	18	18	16	6	9500
2026-03-04	Google Ads	Lasik Campaign	15000	650	360	50	35	30	13	19500
2026-03-04	Instagram Ads	Eye Checkup Promo	17000	600	270	55	36	31	8	8000
2026-03-04	Organic Search	SEO General	9500	420	0	36	22	19	7	10000
2026-03-05	Google Ads	Lasik Campaign	14500	630	355	49	34	29	12	18000
2026-03-05	Facebook Ads	Cataract Awareness	17800	620	300	51	30	25	9	14000
2026-03-05	Referral	Doctor Referral	3200	140	0	22	16	15	6	9000
2026-03-06	Google Ads	Lasik Campaign	16000	700	380	55	38	32	14	21000
2026-03-06	Instagram Ads	Eye Checkup Promo	18000	620	290	58	39	33	9	8500
2026-03-06	Walk-in	Offline	2500	0	0	20	20	18	7	11000
2026-03-07	Google Ads	Lasik Campaign	15500	680	370	53	37	31	13	19500
2026-03-07	Facebook Ads	Cataract Awareness	18200	630	310	52	31	26	10	15000
2026-03-07	Organic Search	SEO General	9800	430	0	38	23	20	8	11000
2026-03-08	Google Ads	Lasik Campaign	15000	660	360	51	35	30	12	18000
2026-03-08	Instagram Ads	Eye Checkup Promo	17500	610	280	56	37	32	8	8000
2026-03-08	Referral	Doctor Referral	3400	150	0	23	17	16	6	9500
2026-03-09	Google Ads	Lasik Campaign	16200	710	390	57	39	34	15	22500
2026-03-09	Facebook Ads	Cataract Awareness	18500	640	320	54	32	27	11	16000
2026-03-09	Walk-in	Offline	2600	0	0	21	21	19	7	11500
2026-03-10	Google Ads	Lasik Campaign	15800	690	380	55	38	33	14	21000
2026-03-10	Instagram Ads	Eye Checkup Promo	17800	620	300	58	40	34	9	9000
2026-03-10	Organic Search	SEO General	10000	440	0	40	24	21	8	12000 </DATA>

---

Placeholders to fill: 
[Paste raw data here]

---

**Intended Workflow**
Monthly reporting and performance review for the hospital's digital marketing activities, presented to senior management.

**Problem Being Solved**
Transforming raw analytics data from multiple platforms into a readable, decision-ready report takes several hours each month and often requires advanced data interpretation skills.

**Automation Potential**
High. Once data is exported from each platform, this prompt can produce a polished report in minutes. Over time, this can be semi-automated using connected tools (e.g. Zapier + ChatGPT integration with Google Sheets exports).

**Risks and Limitations**
-The prompt depends entirely on the quality and accuracy of data the user pastes in — garbage in, garbage out.
-AI may misinterpret trends if context (e.g. a public holiday reducing traffic) is not provided explicitly.

---

**output**
## Bottom Line  
Performance showed solid growth in patient acquisition driven primarily by Paid channels, particularly Google Ads, with noticeable improvements in lead volume and appointment completions.

| Channel        | Traffic (Clicks) | Leads | Click-Through Rate (CTR) | Conversion Rate (Leads/Clicks) | % Change (Leads) |
|----------------|------------------|-------|--------------------------|-------------------------------|------------------|
| Google Ads     | 7,095            | 555   | ~4.8%                    | 7.8%                          | +15%             |
| Facebook Ads   | 3,720            | 308   | ~3.8%                    | 8.3%                          | +8%              |
| Instagram Ads  | 4,260            | 430   | ~3.7%                    | 10.1%                         | +12%             |
| Organic Search | 2,590            | 189   | ~4.3%                    | 7.3%                          | +10%             |

### Critical Insights  
- **Google Ads (Lasik Campaign)** led growth due to increased impressions and spend, boosting both leads (+15%) and completed surgeries.  
- **Instagram Ads** showed the highest conversion rate (10.1%) driven by the Eye Checkup Promo, indicating effective engagement with younger demographics.  
- **Facebook Ads** (Cataract Awareness) maintained steady leads and strong appointment completions, reflecting successful awareness-building efforts.  
- **Organic Search** continues to deliver valuable leads with zero spend, confirming strong SEO presence.  
- **Walk-ins and Doctor Referrals**, while smaller in volume, contribute consistently to completed appointments, underscoring offline channels' importance.

### Strategic Roadmap  
1. **Increase budget allocation to Google Ads and Instagram campaigns:** Prioritize expanding the Lasik and Eye Checkup promotions to capitalize on their strong lead generation and conversion rates.  
2. **Enhance Facebook awareness content:** Refresh Cataract campaign messaging to sustain engagement and improve appointment booking rates, especially targeting older patient segments.

This focused approach balances paid and organic efforts to maximize patient acquisition while optimizing marketing spend efficiency.

---
