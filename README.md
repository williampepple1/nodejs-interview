# Node.js Interview Preparation

A comprehensive, hands-on guide to Node.js concepts — organized as Jupyter notebooks with runnable code examples and detailed explanations. Built for interview prep.

## Prerequisites

- **Node.js** v18+ installed
- **Jupyter Notebook** with the [IJavascript kernel](https://github.com/nickkidd/ijavascript) or use VS Code's built-in notebook support

## Notebooks

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | [Node.js Fundamentals](./01-nodejs-fundamentals.ipynb) | V8 Engine, Event Loop, Single-threaded model, `process`, `global` |
| 02 | [Modules & npm](./02-modules-and-npm.ipynb) | CommonJS vs ESM, `require` resolution, package.json, semver |
| 03 | [Async Programming](./03-async-programming.ipynb) | Callbacks, Promises, async/await, microtasks vs macrotasks |
| 04 | [Events & Streams](./04-event-emitters-streams.ipynb) | EventEmitter, Readable/Writable streams, Buffers, piping |
| 05 | [Express & APIs](./05-express-and-apis.ipynb) | Express middleware, REST design, routing, request lifecycle |
| 06 | [Error Handling & Debugging](./06-error-handling-debugging.ipynb) | Error types, try/catch patterns, uncaught exceptions, debugging |
| 07 | [Security & Performance](./07-security-and-performance.ipynb) | OWASP, CORS, Helmet, clustering, caching, memory leaks |
| 08 | [Databases & ORMs](./08-databases-and-orms.ipynb) | MongoDB/Mongoose, SQL/Sequelize, connection pooling, transactions |
| 09 | [Testing & Deployment](./09-testing-and-deployment.ipynb) | Jest, Mocha, supertest, Docker, CI/CD, PM2 |
| 10 | [Advanced Topics](./10-advanced-topics.ipynb) | Worker Threads, Child Processes, Design Patterns, Microservices |

### Interview Q&A (MCQs + Detailed Answers)

| # | Topic | Contents |
|---|-------|----------|
| 11 | [Q&A: Fundamentals & Event Loop](./11-interview-qa-fundamentals.ipynb) | 43 MCQs + 7 detailed Q&A on Node.js architecture, event loop output prediction, modules |
| 12 | [Q&A: Async, Streams & Express](./12-interview-qa-async-streams.ipynb) | 40 MCQs + 7 detailed Q&A on Promises, async/await, streams, REST API design |
| 13 | [Q&A: Security, DB, Testing & Advanced](./13-interview-qa-advanced.ipynb) | 45 MCQs + 7 detailed Q&A on security, databases, testing, microservices, design patterns |

> **Total: 128 multiple-choice questions + 21 detailed interview Q&As with model answers**

## How to Use

1. Clone the repo
2. Open notebooks in VS Code or Jupyter
3. Each notebook contains:
   - **Concept explanations** with diagrams
   - **Runnable code examples**
   - **Common interview questions** with model answers
   - **Gotchas & tips** interviewers love to ask about

## Quick Interview Tip

> Interviewers don't just want to hear *what* something is — they want to know *why* it matters and *when* you'd use it. Each notebook is structured to help you build that deeper understanding.
