##The Rails Philosophy

**Three Principles:**

- **Convention over Configuration:**
  Common aspects of a web application are already provided and preconfigured.
  Use them, rather than fight against them.

- **Don't Repeat Yourself (DRY):**
  Every piece of information should have a single, unambiguous and authoritative
  representation.

- **Agile Development:**
  Software development methodologies bases on iterative and incremental development,
  where requirements and code evolve with minimal planning through self-organizing,
  cross-functional teams.

###Convention over Configuration
- A massive number of conventions are built into Rails, the trick is learning
  all of them.
- Rails code generators follow specific naming conventions.

###DRY:
- When applied successfully, a modification to a system element does not change
  any other logically-unrelated system element, while elements that are logically
  related all change predictably and uniformly, thereby keeping them in "sync".
- This principle makes it easier to use code generators and automatic build systems.
- Code is typically created by data transformation and code generators.

###Agile Development:
- Emphasizes working software as the primary measure of progress.
- In development mode, there are no recompile, deploy, restart cycles.
- Rails has simple tools to generate ode quickly.
- Testing is built into the Rails framework.
- Extreme Programming:
  - Is an agile approach that centers around test-driver development (TDD).
  - Behavior-driven development (BDD), a second generation agile approach, extends
    TDD by writing test cases in natural language that non-programmers can read.
    BDD focuses on clear understanding of desired software behavior through
    discuss with stakeholders.

RSpec and Cucumber are BDD tools for Ruby.