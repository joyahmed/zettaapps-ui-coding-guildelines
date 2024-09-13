# ZettaApps UI & Coding Guidelines

## Maximize Reusability
- Strive to create **reusable components** wherever possible. Components should be **generic, modular**, and easy to integrate across different parts of the app. This enhances **consistency** and reduces code duplication.

## Modular Code Structure
- Break your code into logical, small, and manageable pieces. Each **component, hook**, or **utility function** should have a single responsibility. This makes testing and debugging easier while improving **readability**.

## Isolate State Logic and Side Effects
- Move **state management** (e.g., local states, context) and other side effects (e.g., working with **local storage**, timers, etc.) out of components when they make the component bulky or complex. Use **custom hooks** to manage this logic, ensuring that components remain **focused** on rendering the UI.

## Keep Components Small and Focused
- Aim for each component to serve a **single purpose**. If a component grows too large, it may be handling too much responsibility. Break it down into smaller **subcomponents** or hooks to maintain simplicity.

## Follow Existing Layout Patterns
- For layouts, structures, and styling, **reuse patterns** and components from existing Zetta projects. Maintain consistency with **proven solutions**, and avoid experimenting with new layouts or styles unless explicitly required. Stick to familiar styling guidelines.

## Propose Improvements Separately
- If you discover a way to improve an existing feature or component, do not directly implement it in an ongoing project. Instead, create a separate project to showcase the improvement. If it proves more efficient and reliable, it will be considered for adoption across projects.

## Maintain Development Speed and Stability
- Avoid changes that complicate the codebase or slow down development. Prioritize **stable**, time-tested solutions over complex or unproven methods that might lead to breaking changes. Always **test** new logic thoroughly before integrating it.

## Use State Efficiently
- Manage **component state** efficiently. Avoid unnecessary rerenders by using **React's `useState`, `useReducer`, and `useMemo` hooks**. Handle global state with **context** or state management libraries only when absolutely necessary.

## Refactor Repeated Logic
- If you notice repeated logic across components (e.g., handling state, managing side effects), refactor it into **custom hooks** or **utility functions**. This ensures better maintainability and keeps the codebase DRY (Don't Repeat Yourself).

## Prioritize Efficient Development
- **Focus on speed and efficiency** when coding. Break tasks into **small, manageable chunks**, and avoid over-engineering solutions. Ensure that each task is completed in a reasonable amount of time by setting **clear deadlines** and **communicating progress regularly**.

## Limit Research Time
- When faced with a new feature or issue, allocate a **strict time limit** for research (e.g., 30 minutes). If no solution is found within that time, consult with me or the team or implement a temporary workaround to maintain momentum.

## Use Templates and Code Snippets
- **Leverage templates, boilerplate code, or snippets** from previous projects to speed up repetitive tasks. Don’t reinvent the wheel—reuse existing code that has already proven effective.

## Adopt Agile Practices
- Work in **short, focused sprints**, ensuring progress is continuous and measurable. Break larger tasks into smaller, actionable steps and complete them sequentially. This keeps the workflow moving and avoids getting stuck on long, complex tasks.

## Limit Refactoring During Active Development
- Refactor only when necessary during feature development. Extensive refactoring can delay progress, so if it's not essential for the task at hand, it should be deferred until after the feature is delivered.

## Use Debugging Tools Early
- Don’t wait until the end of the task to debug. Use **React Developer Tools**, browser dev tools, and logging to catch bugs early in the process. This prevents spending too much time fixing issues at the end of development.

## Communicate and Seek Feedback
- If something is unclear, **ask for clarification immediately**. It’s faster to communicate and resolve issues early than to spend unnecessary time implementing something incorrectly. Seek feedback on progress frequently to avoid misunderstandings.
