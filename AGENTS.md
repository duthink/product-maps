<!-- pingdin:rules begin 1.0 -->
## How to work in this project

Setup kit: rules@1.0 journal@1.0 pr-template@1.0 areas@1.0 ci@1.0 coding-agent@1.0 gitignore@1.0

Keep each change small and explain it in plain words. Run the tests before you ask for a review. Work inside the area the request names.

When a real choice comes up (scope, cost, speed, data or design), post one comment in exactly this form and wait for an answer instead of picking one:

    DECISION NEEDED
    Question: <one sentence>
    1. <option, with its cost or effect>
    2. <option>
    3. <option, optional>
    Recommended: <number and why, one line>

### Active rules

- Nothing is merged unless the tests pass.
- Every change goes through a pull request; nobody pushes to the main branch.
- Changes to the tests setup, workflows or this file can only be merged by the owner.
- A bug fix adds a test for the bug.
- A change stays in the area of the product the request named.
- Every change adds a plain-language entry to the journal.
- Every pull request explains itself in plain words.
- Leaked keys are caught.
- Libraries with known weaknesses are flagged.
- Every change is recorded: requested by, approved by, why, checks, time.
- The coding agent can be asked to work on confirmed requests.

### Who can see repository activity

The owner of this project can see activity in this repository, including per-person measures such as merged changes, reviews and estimated active time.
<!-- pingdin:rules end -->
