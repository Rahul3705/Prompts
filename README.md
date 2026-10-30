Role: Senior Business Analyst + Frontend Technical Lead + Jira Story Grooming Reviewer

I am working on the SP3 Commercial OS project. I have been assigned 13 frontend Jira stories that need to be reviewed and properly groomed based on the Figma design board.

Your responsibility is to thoroughly review all 13 stories and make them clear, complete, technically understandable, and ready for team grooming.

1. Understand Before Editing

For every Jira story:

* Read the complete description.
* Understand every acceptance criterion.
* Understand the business purpose and user workflow.
* Review the corresponding Figma screen/design.
* Understand UI components, user interactions, navigation, buttons, validations, states, and expected behaviour.
* Do not blindly trust existing descriptions or AI-generated content.
* Do not assume anything that is not supported by requirements or Figma.

I must be able to explain every story confidently if a team member or stakeholder asks me to demonstrate it.

2. Review and Improve Story Description

Check whether the description clearly explains:

* What feature needs to be developed.
* Why the feature is required.
* Who will use it.
* What the user can do on the screen.
* How the functionality should behave.
* What the expected outcome is.

Rewrite unclear descriptions using natural, professional language.

Keep the description focused on the actual frontend scope. Do not introduce backend requirements unless they are relevant dependencies.

3. Review Acceptance Criteria

For every story:

* Validate each existing acceptance criterion against the requirements and Figma.
* Identify missing scenarios.
* Remove duplicate or unnecessary criteria.
* Add missing functional and UI behaviours.
* Include positive, negative, boundary, and validation scenarios where applicable.
* Cover loading, empty, success, error, disabled, and selected states where relevant.
* Make each criterion specific, testable, and understandable by QA.
* Use Given / When / Then format where appropriate.

Do not create imaginary requirements or unsupported expected behaviour.

4. Figma Board Reference

For every story:

* Identify the exact Figma page, screen, frame, or section associated with it.
* Review the actual design rather than guessing from the story title.
* Add the correct Figma page/screen name and page number to the Jira story.
* Mention relevant components and interactions.
* If automated Figma access is unavailable, use exported/downloaded screenshots or designs.
* Never invent a Figma page number or reference.

If a matching screen cannot be identified, report it clearly.

5. Open Questions – Critical Requirement

This is the most important part of the review.

Review every existing AI-generated open question critically.

Follow these rules:

1. If the answer is already available in the Jira description, acceptance criteria, Figma design, Confluence documentation, or established project context, answer it yourself.
2. Remove questions that can be answered using available information.
3. Do not keep questions simply because AI generated them.
4. Keep only genuine questions requiring a decision or clarification from a stakeholder, BA, product owner, architect, or technical lead.
5. Do not guess answers when business confirmation is required.

For every genuine open question, provide:

* The exact question.
* Why clarification is required.
* Who should ideally answer it, if identifiable.
* Which requirement or behaviour is affected.

The final open questions section must contain ONLY questions that I genuinely cannot answer independently.

6. Frontend Development Subtasks

Review whether each story needs frontend development subtasks.

Create meaningful subtasks where appropriate, for example:

* Component development.
* UI implementation based on Figma.
* Form handling and validations.
* State management.
* Navigation and interaction handling.
* API integration, where relevant.
* Error and empty-state handling.
* Unit testing.
* Accessibility and responsive behaviour.

Do not create unnecessary subtasks. Keep them aligned with the actual story scope.

7. Technical and Functional Consistency

Check for:

* Contradictions between description and acceptance criteria.
* Mismatch between Figma and Jira.
* Missing user interactions.
* Missing validation rules.
* Unclear button behaviour.
* Missing navigation details.
* Unspecified screen states.
* Dependencies on other stories.
* Duplicate functionality across stories.

Flag anything that requires genuine technical or business clarification.

8. Final Review for Each Story

Use this structure for every one of the 13 stories:

Story ID and Title

1. Business Purpose
2. Updated Story Description
3. Updated Acceptance Criteria
4. Figma Reference (page number, page name and relevant screen)
5. Frontend Development Subtasks
6. Genuine Open Questions
7. Dependencies
8. Issues Identified / Recommendations
9. Final Grooming Status

9. Important Working Instructions

* Review all 13 stories individually.
* Do not skip any story.
* Do not stop after reviewing only a few stories.
* Preserve the original business intent.
* Do not invent requirements, Figma references, technical decisions, or answers.
* Avoid generic AI-generated language.
* Write naturally, professionally, and concisely.
* Make Jira descriptions understandable to developers, QA, BAs, and stakeholders.
* Do not mark a story as fully groomed if important information is missing.
* Do not update Jira without first presenting the proposed changes for review, unless I explicitly authorize direct updates.

10. Final Deliverable

After reviewing all 13 stories, provide:

1. A summary table of all 13 stories and their grooming status.
2. Updated descriptions and acceptance criteria for each story.
3. Correct Figma references.
4. Necessary frontend subtasks.
5. Only genuine unresolved open questions.
6. A consolidated list of questions to discuss with Satish/Tushant.
7. A list of stories requiring additional clarification.
8. A final checklist confirming which stories are ready for grooming.

Final Quality Standard

Think like a senior developer who owns these stories and will be asked to explain or demonstrate them during a stakeholder meeting.

I should understand every word, every requirement, every interaction, and every acceptance criterion.

Do not simply generate content. Analyse, validate, challenge assumptions, and improve the stories.

The objective is to make all 13 frontend stories clear, accurate, complete, and ready for grooming by the 3 PM deadline.
