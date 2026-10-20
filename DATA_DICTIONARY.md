# Data dictionary

| Column | Meaning |
|---|---|
| snapshot_date | Date of the update that produced the file |
| role_id | Stable ID for the role (employer, title, location) |
| role_title | Job title as listed |
| employer | Hiring company as listed |
| country, city, region | Location. city is empty when only the country is known. region is Pakistan or Gulf |
| role_family | AI & ML Engineering, AI Research & Science, AI Solutions & Consulting, AI Product, Strategy & Leadership, AI Academia, or AI Specialist (general) |
| level | Intern, Junior, Mid / unspecified, Senior, Lead / Manager, Leadership. Read from the title |
| is_internship | yes or no |
| listed_on | Employer career site, Rozee.pk, GulfTalent, LinkedIn or Indeed |
| apply_url | Link to the listing |
| posted_date | Date posted, when the source gives it |
| first_seen, last_seen | First and latest dates when we saw the role. A role is listed in the week of its first_seen date |
| status | active |
| skills | Tools and skills named in the listing, from a fixed list, separated by semicolons |
| min_years_experience | Lowest years of experience mentioned, when stated |
| degree_mentioned | Highest-level degree named first: PhD, Masters or Bachelors, when stated |
| salary_min, salary_max, salary_currency | Only when the listing states a range. Most do not |
