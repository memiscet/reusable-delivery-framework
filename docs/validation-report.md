# Validation record

The following checks ran successfully on 2026-10-28 using Python 3.14.7 in an isolated virtual environment.

| Check | Result |
|---|---|
| `python scripts/check_example.py` | Three fictional welcome-guide content promises passed |
| `python scripts/validate.py --project examples/community-event --complete` | Completed example's structure and handoffs passed |
| `python scripts/validate.py --project examples/software-request` | Pending software example's planning handoffs passed |
| `python -m unittest discover -s tests -v` | 31 tests passed |
| `python scripts/check_repository.py` | Local Markdown links, schema definitions, and seven skill headers passed |
| Skill-creator's quick validator on each `skills/<name>/` | All seven skills passed metadata validation |
| `python -m pip check` | No broken dependency requirements |

The tests include stale plans and reviews, incomplete AC coverage, invalid dependencies, duplicate identifiers, missing evidence, unsupported passes, inconsistent verdicts, missing artifacts, path escapes, invalid dates, repeated YAML keys, and preservation of existing work during initialization.

These results apply to the files checked locally. The GitHub workflow is configured for Python 3.11 and 3.14; hosted CI was not run as part of this local record. No AI model benchmark, production application, real event, or user study was executed. Skill metadata validation does not establish behavioral quality.

To reproduce the local checks, follow [technical setup](technical-setup.md). The repository checker provides the included skill metadata check without depending on the external skill-creator package.
