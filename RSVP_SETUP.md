# Tutorial RSVP setup

The English Google Form is **published** with responder access set to **Anyone with the link**. The website links to the public form and retains an email fallback.

## Google Forms settings

- Use English for the form title, description, questions, choices, validation messages, and confirmation message.
- Publish the form with responder access set to **Anyone with the link**. Do not restrict respondents to an organization or require Google sign-in.
- Turn **Limit to 1 response** off, because it requires Google sign-in.
- Set **Collect email addresses** to **Do not collect**. Do not collect verified Google account email addresses. Instead, add the required **Email** short-answer question below with **Text → Email address** response validation.
- Keep **View results summary** off. Respondents must not be able to view other responses.
- One shared form and a linked private Google Sheets response table for all attendees.
- Keep responses private to authorized tutorial organizers. Do not publish response summaries or a participant list.
- Collect no files, health information or payment details.
- Preserve the email RSVP alternative for anyone who cannot access Google Forms. Share the direct public responder link as well as the tutorial website link. Do not describe mainland China access as verified without testing from a mainland network.

## Form content

**Title:** RSVP — Personal LLM Health Agent Tutorial

**Description:**

October 12, 2026, afternoon, Shanghai. This one-minute form helps the organizers estimate attendance and send tutorial setup information. RSVP does not replace paid UbiComp/ISWC registration and does not reserve a seat. Please select official conference registration covering the workshop/tutorial days.

Responses are for tutorial organization and participant communication. We will not publish the participant list. Do not include health data, passwords, or API keys. For questions, contact zj2445@cumc.columbia.edu.

1. **Name** — required, short text.
2. **Email** — required, short answer with **Text → Email address** validation. Description: "Used for tutorial logistics and setup instructions only." Validation message: "Please enter a valid email address."
3. **Institution** — optional, short text.
4. **Attendance plans** — required, single choice:
   - Planning to attend in person
   - Interested, not yet certain
5. **Python experience** — optional, single choice:
   - New to Python
   - Can run and edit notebooks
   - Comfortable writing Python
6. **Agent development experience (optional)** — optional, single choice. Select the highest level that describes your experience building LLM agents. No prior agent development experience is required for this tutorial.
   - No prior agent development experience
   - Followed a tutorial or modified an agent example
   - Built my own tool-using agent prototype
   - Deployed or evaluated agents in a research or applied project
7. **Registration acknowledgment** — required checkbox:
   - I understand that this RSVP is not conference registration and does not reserve a seat.

**Completion message:**

Thank you. Your RSVP has been recorded. We will use your email for tutorial updates and setup information. Please complete the required conference registration separately. Questions: zj2445@cumc.columbia.edu.

## Published form link

The `rsvp-form-button` link in `docs/index.html` opens the [public responder form](https://docs.google.com/forms/d/e/1FAIpQLSdWzprHOY6Myk8anZ5wM9EUDd5w-I5V7CFPpEUa3vYFiamk_Q/viewform?usp=header). It does not link to the editor or response results. The form does not require a Google account.

## Launch checks

- Open the public responder URL in a signed-out browser session. Verify that the form loads and can be completed without a Google account.
- Confirm that Name, Email, Attendance plans, and Registration acknowledgment are required, and that Institution and Python experience are optional.
- Check that the Email question rejects an invalid email format and that all authored content is in English.
- Launch validation checks should not submit a response, so the response list remains empty. Response persistence remains unverified until an authorized submission is checked in the organizer account. If a test response is submitted later, use authorized test data rather than a real person's details, and confirm before permanently deleting it or its corresponding row in a linked response sheet.
- Confirm that respondents cannot view the response summary or participant list.
- Check the website at desktop and mobile widths. Verify the form link, the email alternative, and the separate official paid-registration link.
- Keep the statement that RSVP does not replace paid UbiComp/ISWC registration or reserve a seat in both the form and website.
- Verify mainland access separately before claiming it works there. Keep the email alternative visible regardless.
