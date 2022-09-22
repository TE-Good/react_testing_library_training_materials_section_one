# React Testing Library Training

What will you learn;

## Sections

1. What is Jest?
2. What is React Testing Library (RTL)
3. React Testing Library Ethos: Testing behaviour instead of implementation
4. Test Structure
5. Mocking

### What is Jest?

https://jestjs.io/

- How its one of the largest testing frameworks (close to 17 million weekly downloads)
- Basic functionality with introduction to basic functions

### What is React Testing Library

https://testing-library.com/docs/react-testing-library/intro/

- How it used to test React
- Testing behaviour instead of implementation
- Core functions (render, screen, getById)
- Show more queries and the matrix of them https://testing-library.com/docs/react-testing-library/cheatsheet#queries
- Addition of `userEvents` -> https://testing-library.com/docs/react-testing-library/migrate-from-enzyme#what-is-react-testing-library
- Addition of `jest-dom`

### Test structure

https://kentcdodds.com/blog/avoid-nesting-when-youre-testing

- file naming
- File location
- setup functions
- flat test structure

### Jest Mocks

- Be clear this is part of the jest framework.
- A short intro to how they can be used.
- spyOn, jest.mock, jest.fn. mockImplementation, mockReturnValue
- How we use them in the eigen codebase.
