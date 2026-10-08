# APEX 2.0 — F1 Historical Records Explorer

An independent, heavily AI-assisted Formula 1 historical statistics project.

## What it does
APEX explores a custom statistic: the shortest eligible **total race-winning time** for each historical circuit layout. It distinguishes circuit configurations, checks lap counts, and explains why selected records qualify.

This is **not an official Formula 1 or FIA records database**. Results reflect the project's own criteria, and historical classifications may contain errors.

## AI disclosure
The project owner conceived the idea, defined the selection benchmarks and review rules, and directed the work. ChatGPT was used extensively for historical research, data processing, coding, and website design. Not every historical entry has been independently verified by the project owner; corrections and constructive scrutiny are encouraged.

## Dataset status
The current compiled data covers 1,165 race entries across 198 provisional circuit-layout groups. It identifies 160 records accepted under the custom criteria, while 38 groups have unresolved caveats or questions. Some accepted results use a documented fallback rule rather than direct pre-race documentary proof.

## Record methodology
1. Compare only races that share the same circuit layout.
2. Use the highest eligible lap count for a layout; exclude shorter races subject to documented exceptions.
3. Of the qualifying races, select the shortest total winning time.
4. Preserve the supporting sources, decision reasoning, and confidence/evidence level.

## Website
The project is a standalone HTML application and can run offline by opening `index.html`. Once GitHub Pages is activated, the same file can be viewed online.

## Report a correction
Please open an Issue specifying the circuit, year, current record, proposed correction, and source links.

Not affiliated with Formula 1, FIA, or any F1 team.
