# Key Findings

## Why This Project Was Interesting

The 2014-2016 West Africa Ebola outbreak is important to explore through data
because it was historically severe and unevenly distributed across countries.
The notebook uses a cleaned WHO/HDX-derived dataset to look at where reported
cases and deaths were concentrated, how the outbreak appeared over time, and
what source-backed public health context can and cannot explain.

## What The Data Shows

The cleaned project dataset shows a highly concentrated outbreak burden. Sierra
Leone, Liberia, and Guinea account for nearly all reported cases and deaths in
the notebook's main country dataset. Together, they represent about 99.85% of
reported cases and about 99.87% of reported deaths in that cleaned dataset.

The three countries do not show the same pattern. Sierra Leone has the highest
reported case total in the notebook's country-burden table, with 14,122 reported
cases. Liberia has the highest reported death total, with 4,806 reported deaths.
Guinea has fewer reported cases and deaths than Sierra Leone and Liberia, but it
still makes up most of the remaining burden among the three hardest-hit
countries.

The smaller outbreaks in the cleaned dataset are much lower in scale. Nigeria,
Mali, the United States of America, Senegal, Italy, Spain, and the United
Kingdom appear as imported or limited outbreaks in the notebook's comparisons.
The overall project dataset covers 10 main country labels and more than 28,600
reported cases, using cumulative confirmed, probable, and suspected case and
death indicators.

The notebook also shows why country differences need careful reading. Case
totals, death totals, reporting coverage, and descriptive CFR values do not all
tell the same story. For example, Mali has the highest descriptive CFR in the
cleaned dataset, but that percentage is based on only 8 reported cases, so it is
not comparable to ratios from the larger outbreaks in Liberia, Sierra Leone, and
Guinea.

## What Can Be Learned From The Outbreak

The notebook suggests cautious lessons about outbreak response capacity. WHO
sources frame Ebola control as a package of activities rather than a single
intervention. The themes discussed in the notebook include coordinated emergency
response, surveillance, contact tracing, case management, laboratory support,
safe burial practices, and community engagement.

Nigeria is used as a documented contrast case, not as a direct comparison for
Guinea, Liberia, or Sierra Leone. CDC and academic sources cited in the notebook
describe Nigeria's response as involving rapid coordination, intensive contact
tracing, isolation and case management, laboratory confirmation, and
communication activities. This supports a careful lesson: response systems
appear stronger when they can coordinate quickly, trace and monitor contacts,
manage suspected or confirmed cases, confirm cases through laboratory support,
and communicate clearly with communities.

The notebook also emphasizes continued monitoring after apparent containment.
The WHO end-phase milestone is used as context because known transmission chains
had stopped while flare-up risk remained. That supports the idea that outbreak
analysis should pay attention not only to the rise of reported cases, but also
to the period after visible transmission appears to have slowed or stopped.

These are lessons suggested by the evidence reviewed in the notebook. They are
not proof that one intervention caused a specific change in the outbreak curves.

## Important Things To Keep In Mind

The dataset has a specific scope. It uses selected cumulative confirmed,
probable, and suspected case and death indicators from the WHO/HDX-derived
project data. These are descriptive project totals, not confirmed-only counts or
exact WHO headline totals.

Reporting differs by country, so the time-series charts should be read with
care. More reporting rows do not mean a country had a more severe outbreak, and
derived changes in cumulative cases are not the same as true daily incidence.

CFR values are descriptive ratios: reported deaths divided by reported cases.
They are useful only when the denominator is visible, especially for countries
with very small reported outbreaks.

`Liberia 2` and `Guinea 2` remain excluded from the primary country-level
dataset. The notebook explains that merging those continuation labels directly
into Liberia and Guinea would create duplicate country-date rows, and their
literal source meaning remains unresolved.

The intervention evidence also has gaps. The notebook uses official milestones
and Nigeria response evidence as context, but it does not claim that specific
regional interventions explain changes in the three hardest-hit countries'
curves. Some timing evidence, including treatment-center and safe-burial dates,
remains under-sourced for that kind of claim.

## Final Reflection

This project is a careful exploration of an important public-health event. Its
value comes from showing what the cleaned dataset can describe, where the
evidence is stronger, and where interpretation needs restraint.

Transparent data analysis matters here because the outbreak patterns are
meaningful, but the limitations are meaningful too. The notebook is most useful
when its descriptive findings and public-health context are read together, with
clear evidence boundaries.
