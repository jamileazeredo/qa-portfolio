# Hi, I'm Jamile Azeredo 👋

Junior Quality Assurance professional based in Zurich, Switzerland 🇨🇭
## About Me

I'm Jamile Azeredo, a Quality Assurance professional based in Zurich, Switzerland, currently
transitioning into technology after nearly 10 years of experience in business management and
legal administration in Brazil.

I chose to move into QA after recognizing technology as an area with strong long-term growth
potential — and one where I could apply skills I had already built: structured thinking, attention
to detail, and the ability to work well within teams and cross-functional projects.

For more than 9 years, I built and ran my own beauty business in Brazil, managing daily operations,
client relationships, and a growing team across two locations. Earlier in my career, I spent over
2 years working within judicial institutions in Rio de Janeiro, handling legal documentation and
case files for the public. Both experiences — one entrepreneurial, one institutional — gave me a
solid foundation in documentation, process management, and identifying inconsistencies before they
become bigger problems, all of which translate directly into how I approach software testing today.

What draws me specifically to QA is the combination of analytical thinking and collaboration:
testing isn't a solitary task, it requires understanding requirements, communicating clearly with
developers and stakeholders, and constantly refining a process based on feedback — something I
already valued and practiced long before writing my first test case.

I'm currently completing a hands-on QA training program with TripleTen, where I've applied manual
testing, API testing, mobile testing, and structured bug reporting across real-world project
simulations. This portfolio documents that journey — not just the projects themselves, but the
process and thinking behind them.

---

## My Learning Journey

*A timeline of my progress through the TripleTen QA Bootcamp — each project built on the skills and feedback from the one before it.*

### Sprint 1 — [Urban Routes: Regression Testing](https://github.com/jamileazeredo/urban-routes-testing)
My first hands-on testing project, focused on manual and regression testing of a route-planning web application. I identified functional inconsistencies and documented over 6 bugs in Jira, learning the fundamentals of clear, structured bug reporting. This was where I first learned that a good bug title should answer "what, where, and when" — a principle that shaped every project that followed.

### Sprint 2 — [Test Documentation](https://github.com/jamileazeredo/test-documentation)
This project introduced formal test design techniques: requirements analysis, equivalence class partitioning, and boundary value analysis. I learned that a boundary isn't just the edge of a valid range, but also the values immediately outside it — a distinction that directly improved the depth of my test coverage in later API testing.

### Sprint 3 — [Manual Testing & Bug Reporting](https://github.com/jamileazeredo/manual-testing-bug-reporting)
Focused on layout, form, and functional testing, this project reinforced the bug-reporting discipline from Sprint 1. Receiving the same feedback on title clarity a second time taught me that consistency requires deliberate repetition — not just understanding a principle once, but applying it every time.

### Sprint 4 — [API Testing with Postman](https://github.com/jamileazeredo/api-testing-postman)
My first project testing beyond the user interface: validating REST API endpoints using Postman across 59 test cases, covering positive, negative, and boundary scenarios. Feedback on this project taught me to validate results strictly against written specifications, rather than relying on what the system appeared to do.

### Sprint 5 — [Mobile Application Testing](https://github.com/jamileazeredo/mobile-application-testing)
The most complete project of the bootcamp: manual testing of an Android application across 51 checklist items and 7 sections, including a dedicated section for ambiguous requirements. This project consolidated everything from the previous sprints — structured bug reporting, precise test coverage, and critical thinking about edge cases — resulting in the strongest evaluation of the program.

---

## Reviewer Feedback

*Throughout the TripleTen QA Bootcamp, every project was reviewed by a QA mentor. I'm sharing that feedback here — not just the praise, but also the corrections — because learning to receive and apply feedback is a core part of being a good QA professional.*

### Sprint 1 — Bug Reporting Fundamentals

![Sprint 1 Feedback](PASTE_SPRINT_1_IMAGE_LINK_HERE)

**English translation:**
> "Hello Jamile, congratulations on your work — your project has been approved! [...] Remember that a bug title should give a clear idea of the problem found. [...] You found more than 6 bugs, which is an excellent achievement. Each of your bug reports includes all required fields: ID, title, reproduction steps, expected result, and actual result. Your report titles clearly describe the problem, answering 'What is happening? Where? When?'"

---

### Sprint 2 — Test Case Design & Equivalence Classes

![Sprint 2 Feedback](PASTE_SPRINT_2_IMAGE_LINK_HERE)

**English translation:**
> "Thank you for submitting your Sprint 2 project! At this stage, you started applying equivalence classes and creating your own test cases [...] You structured your classes well and showed a solid theoretical understanding [...] The class 'text with fewer than 2 characters' was missing, which would validate the class of values below the field's accepted limit [...] Great work here! There are still a few opportunities to improve, but your progress is clear."

---

### Sprint 3 — Layout, Forms & Functional Testing

![Sprint 3 Feedback](PASTE_SPRINT_3_IMAGE_LINK_HERE)

**English translation:**
> "Thank you for sharing your project on layout testing, form testing, and functional testing [...] Remember that a clear idea of the problem found shouldn't require opening the report to understand what's happening [...] The title should answer 'What is happening? Where? When?' [...] overall you did excellent work!"

---

### Sprint 4 — API Testing with Postman (Urban Grocers)

![Sprint 4 Feedback](PASTE_SPRINT_4_IMAGE_LINK_HERE)

**English translation:**
> "What an impressive submission! 17 test cases for the first endpoint and 42 for the second — coverage well beyond the minimum expected. [...] Cases 6 and 14 of Endpoint 2 were incorrectly marked as Passed — according to the specification, 0 items should not allow the order to proceed [...] this was one of the most complete and well-documented submissions I've received for Sprint 4!"

---

### Sprint 5 — Mobile Application Testing (Android)

![Sprint 5 Feedback](PASTE_SPRINT_5_IMAGE_LINK_HERE)

**English translation:**
> "What an impressive submission! 51 checklist items covering 7 complete sections of the application, 7 bugs found and documented, a 'gray area' tab for ambiguous items, and very well-structured bug reports in Jira. This is the level of a real QA professional! [...] this was one of the most complete and professional submissions I've received for Sprint 5."

---

## My QA Workflow

*This is how I approach a testing project, from first contact with requirements to final delivery.*

1. **Study the official documentation** — I start by reviewing the requirements and any related checklists (layout, functional specs, etc.) provided by the project manager or client. This is always my starting point — understanding what the application is supposed to do, according to the official source, before I ever interact with the product itself.

2. **Analyze business rules** — I identify the logic behind each requirement — valid ranges, mandatory fields, dependencies between screens or endpoints — since this is where most edge cases and boundary values come from.

3. **Plan the testing strategy** — I decide which techniques apply (equivalence partitioning, boundary value analysis, exploratory testing) and prioritize what to test first based on risk and business impact.

4. **Create the necessary documentation** — I write test plans, test cases, and checklists structured clearly enough that another QA could pick them up and execute them without needing me to explain anything.

5. **Execute the tests and identify gray areas** — As I execute the planned test cases, I pay close attention to what isn't explicitly documented. This hands-on process is exactly what gives me clarity on how the product actually behaves — it's often only during execution that gray areas become visible: scenarios the requirements didn't anticipate, but that could still cause errors for the user. I also stay alert to the fact that fixing one bug can sometimes introduce or expose another, so I treat this awareness as ongoing throughout testing, not a one-time check.

6. **Report bugs in a structured way** — Every bug report includes a clear title (what, where, when), reproduction steps, expected result, and actual result — so anyone can understand and reproduce.

7. **Cross-check test coverage** — Using my own notes on requirements and checklists, I cross-check my work against them — often with AI as a support tool — to confirm that no planned test was left out before considering the project complete.

8. **Apply feedback to improve my process** — I treat reviewer feedback as part of the testing process itself, not just a grade. Each round of feedback has directly shaped how I approach the next project — as documented in the Reviewer Feedback section above.

### How I use AI as a support tool

Over the course of this bootcamp, I developed my own standardized templates — for Jira bug reports and for test case spreadsheets — to make sure every project I deliver follows the same level of detail and is easy to read and review, no matter which sprint it came from.

I use AI as part of that system: while I'm the one reading requirements, executing tests, and identifying inconsistencies in the product, AI helps me follow my own template consistently and speed up documentation — making my output more complete, more agile, and more consistent across every project.

This is how I approach tools in general: I build the process, define the standard, and use whatever makes that process faster and more reliable — without losing ownership of the analysis behind it.

---

## Featured Projects

| Project | Description |
|---|---|
| 🧪 [Urban Routes – Regression Testing](https://github.com/jamileazeredo/urban-routes-testing) | Manual and regression testing of a route-planning web application, including bug reporting and test documentation. |
| 📋 [Test Documentation](https://github.com/jamileazeredo/test-documentation) | Requirements analysis, equivalence class partitioning, and boundary value analysis applied to test case design. |
| 🐞 [Manual Testing & Bug Reporting](https://github.com/jamileazeredo/manual-testing-bug-reporting) | Layout, form, and functional testing with structured bug reports documented in Jira. |
| 🔌 [API Testing with Postman](https://github.com/jamileazeredo/api-testing-postman) | 59 REST API test cases covering positive, negative, and boundary scenarios across two endpoints. |
| 📱 [Mobile Application Testing](https://github.com/jamileazeredo/mobile-application-testing) | Manual testing of an Android application across 51 checklist items, including edge case analysis. |

---

## Contact

📍 Wetzikon, Zurich, Switzerland
💼 [LinkedIn](https://www.linkedin.com/in/jamile-azeredo)
💻 [GitHub](https://github.com/jamileazeredo)
📧 azeredojamile.ch@gmail.com
