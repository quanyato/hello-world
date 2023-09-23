# Engineering Tech Spec

<aside>
💡 **Notion Tip:** Use this template to organize a project kickoff and build out the necessary context. Share this page with other team members by clicking the `Share` button on the top right of this page. Learn more about [sharing & permissions here](https://www.notion.so/help/sharing-and-permissions).

</aside>

**Table of contents**

# Problem statement

What problem are you trying to solve? If there is a [PRD](https://www.notion.so/templates/product-requirement-document-prd), this can be a sync’ed block from the PRD. Link to any other documents that are relevant for background or context.

## Goals

What should be true after this project is implemented?

## Non-goals

What is explicitly not in scope and why?

# Proposed solution

What changes are required to solve this problem and achieve the project goals?

**What are the high level architectural changes?**

Diagrams can be very helpful here.

**What are the high level data model changes?**

These should include any database schema changes, or any changes to structured fields, e.g. an existing JSON column.

**What are the main changes to the UI?**

## Risks

What risks might be introduced by this set of changes? Consider running a [pre-mortem](https://www.notion.so/templates/pre-mortem-template) to raise risks. Be sure to capture mitigating these risks in the Implementation and Rollout Plans.

**Are there any backwards-incompatible changes?**

**Does this project have special implications for security and data privacy?**

**Could this change significantly increase load on any of our backend systems?**

**Does this project have any dependencies?**

# Alternative solutions

What alternatives did you consider? Describe the evaluation criteria for how you chose the proposed solution. 

# Implementation and rollout plan

Fill this section out based on what is relevant for the size and scope of this project. This section can also be TBD as the project is started, but you should gradually fill this in as the project progresses towards launch. 

**Does this project require a migration?**

If an extensive migration is necessary, write a separate tech spec for it, and link it here. Describe how to rollback in the event of an unsuccessful migration.

**Is this project in an experiment or feature flagged?**

Describe how to support an incremental release if needed.

## Success Criteria

**How will you validate the solution is working correctly?**

Describe what automated and/or manual testing you will do. Does this project need load or stress testing? This can also be a separate Testing Plan doc that is shared with QA, and linked here.

**What monitoring and alerting will you do to ensure this project doesn’t decrease performance and reliability?**

E.g. Increased requests, latency, and error rates.

### Ready for Review?

- [ ]  Change doc status to `Proposed (Open for comments)`
- [ ]  Add your reviewers to the table below, and click button to request
- [ ]  Share doc in Slack

Reviewers should leave feedback as comments on the tech spec itself, and use the title of their review row to summarize their feedback.

- Review status legend
    - *Review Requested:* The author (or someone else) requested a review from this reviewer.
    - *Changes requested:* The review summary should clearly state what changes are requested. The author should address the reviewer's comments and follow up with the reviewer.
    - *Approved:* Good to go! The reviewer thinks this tech spec should be accepted, and/or trusts the author to make changes based on their feedback.

[Reviewers](Engineering%20Tech%20Spec%207139863815084963ae30f3d508ad35c9/Reviewers%2073f919e0aeac4719989f0d3b5fc2ecb1.csv)
