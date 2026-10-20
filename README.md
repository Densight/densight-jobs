# Densight AI Hiring Data

Open data on AI jobs, updated several times a week, in Pakistan and the Gulf (UAE, Saudi Arabia, Qatar, Kuwait, Bahrain, Oman).
Published by [Densight Labs](https://densightlabs.com). Licence: CC BY 4.0. Please credit "Densight Labs".

## What is here
- `data/latest.csv` and `data/latest.json`: the AI roles first seen this week (Sunday to Saturday), up to the latest update. Roles first seen before this week's Sunday are not listed
- `data/weeks/week-of-YYYY-MM-DD.csv`: the roles first seen in each completed week (Sunday to Saturday), named by the Sunday the week starts. Each file holds only that week's roles
- `data/weekly_counts.csv`: open roles, new roles and internships by country and role family at each update. `active_roles` counts every open role, not only this week's. `new_this_week` covers the trailing seven days
- `data/monthly_index.csv`: the monthly Densight AI Hiring Index and monthly new roles by country. Months marked provisional start from roles open at launch and are not used as the base. The index is 100 in the first complete month (new roles that month)
- `data/weekly_movers.csv` and `data/monthly_movers.csv`: new roles by country, role type and skill against the previous week or month. `comparable` is yes only when the earlier period lies fully inside live tracking
- `DATA_DICTIONARY.md`: what each column means

## What counts as an AI role
A role is included when its title is clearly about AI or machine learning (AI, ML, NLP, LLM, generative AI,
computer vision, MLOps and similar), in one of the seven markets, on site or hybrid. Remote roles are excluded.
Data analyst, business analyst, BI, AI trainer and data annotation roles are excluded.
Titles like "Data Scientist" are included only when the job text confirms machine learning work.

## Notes
- Tracking began on 17 Oct 2026. Roles open at launch carry their posting date as `first_seen`, so they fall outside the weekly lists.
  Week on week and month on month changes are marked `comparable` in the movers files once enough tracking exists.
- Each role appears once, even when it is listed on several sites. `apply_url` is the best link we found.
- Roles disappear from the snapshot when they are no longer seen for 21 days.
- Internships are included and marked in `is_internship`. Headline counts should usually exclude them.
- Data comes from employer career sites, Rozee.pk, GulfTalent, LinkedIn and Indeed. Coverage is wide but not complete.
