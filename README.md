# Prompts

Review all the user stories I provide and help me clean them up so they are understandable to both technical and non-technical team members.

For EACH user story:

### 1. Improve the Description
Rewrite the existing description so that it clearly explains:
- What needs to be created/changed
- Why it is needed
- Who/which application/service will use it
- How it fits into the overall project
- Any important technical context already mentioned in the story

Do not change the actual requirement or invent new functionality.

### 2. Create Acceptance Criteria
Based strictly on the story description, create clear and testable acceptance criteria.

Use this format:

**AC1 – [Short title]**
- Given ...
- When ...
- Then ...

**AC2 – [Short title]**
- Given ...
- When ...
- Then ...

Keep the acceptance criteria specific enough that a developer can implement them and QA can validate them.

### 3. Identify Missing Information
After the acceptance criteria, add:

**Open Questions**
- What information is missing?
- What needs confirmation from the architect/SME?
- Are there dependencies on another service/story?
- Is any technical behavior unclear?

Do NOT guess the answer.

### 4. Technical Tasks
Suggest implementation/review tasks required for the story.

For example:
- Create/update component
- Configure service/API
- Add authorization/entitlement handling
- Add validation
- Add unit/integration tests
- Update documentation

Only suggest tasks that are supported by the story.

### 5. Definition of Done
Provide a short Definition of Done appropriate for the story, including:
- Implementation completed
- Tests completed
- Code review completed
- Documentation updated where required
- Acceptance criteria verified

### Important rules

- Preserve the original business intent.
- Do not invent requirements.
- Do not assume an API, service, database, or technology exists unless it is mentioned or found in the repository.
- If something is unclear, mark it as **Needs Confirmation**.
- Keep the description concise but sufficiently detailed.
- Make acceptance criteria measurable/testable.
- Use terminology from the project's existing documentation.
- If the story references another document such as R5–R9, identify that relationship.
- If multiple stories have dependencies, point them out.

### Output format

For every story, return:

## [Story ID] — [Story Title]

### Improved Description
[Clear description]

### Acceptance Criteria
- AC1 ...
- AC2 ...
- AC3 ...

### Technical Tasks
- Task 1
- Task 2
- Task 3

### Dependencies
[Related stories/components/documents]

### Open Questions / Needs Confirmation
- ...

### Definition of Done
- ...

At the end, provide:

## Overall Story Review

1. Stories that are already clear
2. Stories that need clarification
3. Stories with missing acceptance criteria
4. Stories with dependencies/conflicts
5. Highest-priority stories to discuss with the architect/SME

Do not modify the stories directly in the repository. Give me the proposed changes first so I can review them.
