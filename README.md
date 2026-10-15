# AssessApp curriculum

The Ontario Curriculum, Grades 9–12: Science (all 17 courses) as one data file for
[AssessApp](https://github.com/Haryeti/Assesment-app). The app checks this repository
when you click **Curriculum → Check for curriculum updates**.

| File | What it is |
|---|---|
| `ontario-science.yaml` | every strand, overall and specific expectation, in the Ministry's wording, with a version |
| `latest.json` | the current version and a checksum; the app reads this first |

This repository contains only curriculum text: no code and no student data.

Expectations: © King's Printer for Ontario, reproduced for non-commercial educational use.

## Publishing an update

In the AssessApp repository, update `curriculum/ontario-science.yaml` and bump its
`version`, run `python tools/publish_curriculum.py`, then copy
`curriculum/ontario-science.yaml` and `curriculum/latest.json` here and commit.
