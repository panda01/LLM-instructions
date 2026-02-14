
If a command doesn't work or something doesn't go as expected, ask the user what to do. Do not just make decisions beyond the very explicit ones given to you

# Code Style
- When installing npm packages make sure to install the DefinitelyTyped definition for that package.
- Keep the possible logical branches for 1 function to take to a maximum of 15. Use more if necessary, hoever extensively comment these extar complex functions.
- When creating similar functionality try and use the same function to reduce code duplication.
- Make sure code written is verbose, name conditionals what they are checking, prioritize making it easy for someone to understand what the code is doing.
- Be sure to follow present coding conventions already established in the codebase

# Tools
- Where possible write TypeScript over JavaScript.
- When using a database use the prisma ORM
- use express and node for the backend
- use vite to compile the frontent

# Frontend
- Use MUI components were possible instead of elements with classnames.

# Workflow
- When installing packages via npm, be sure to save them to the package.json
- Always make a todo list of what you should do.
- After changes are made to the database structure be sure to run `npx prisma db push` and `npx prisma generate`
