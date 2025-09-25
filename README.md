# Developer Roadmap (Tech-Stack Agnostic)

This roadmap is about the **foundations** that matter regardless of the frameworks, languages, or tools you use.  
It doesn’t matter what tech stack you choose.

---

## 1. How the Web Works
Understand the fundamentals of requests, responses, headers, and status codes.  
This is the backbone of web development — everything else builds on it.

- Learn how browsers and servers talk (HTTP).
- Know common status codes (200, 301, 404, 500).
- Understand headers and why they matter (cookies, caching, CORS).

**Resources:**
- [MDN Web Docs: HTTP Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)  
- [HTTP Status Codes Explained](https://httpstatuses.com/)

---

## 2. Data and SQL
Being able to model, query, and optimize data is core to any application.

- Learn how to design tables and relationships.
- Write SQL joins (`INNER JOIN`, `LEFT JOIN`, etc.).
- Add indexes when queries get slow.

**Resources:**
- [SQLBolt Interactive Lessons](https://sqlbolt.com/)  
- [What is Index in SQL](https://stackoverflow.com/questions/2955459/what-is-an-index-in-sql)
- [SQL Roadmap](https://roadmap.sh/sql/)

---

## 3. State and Caching
Applications are about **data at the right time**. Know when to fetch, store, or invalidate.

- When to cache results vs. when to re-fetch.
- Avoid stale or inconsistent data.
- Understand session state, local storage, and distributed caching.

**Resources:**
- [Caching Fundamentals (Cloudflare)](https://developers.cloudflare.com/cache/about/)  
- [Caching Strategies](https://medium.com/@mmoshikoo/cache-strategies-996e91c80303)
- [A Developer’s Guide to Browser Storage: Local Storage, Session Storage, and Cookies](https://dev.to/aneeqakhan/a-developers-guide-to-browser-storage-local-storage-session-storage-and-cookies-4c5f)

---

## 4. Errors and Logs
Things break. Good developers know how to find **why**.

- Learn how to surface meaningful error messages.
- Centralize logs for visibility.
- Know where to start debugging when issues happen.

**Resources:**
- [12 Factor App: Logs](https://12factor.net/logs)  
- [Effective Logging Practices (Better Stack Guide)](https://betterstack.com/community/guides/logging/)

---

## 5. Testing
Tests give you confidence to ship changes without fear.

- Start small: test the critical parts first.
- Write a test before a big change.
- Automate running them as much as possible.

**Resources:**
- [Testing Best Practices (Kent C. Dodds)](https://kentcdodds.com/blog/common-mistakes-with-react-testing-library) *(applies beyond React)*  
- [Martin Fowler: Test Pyramid](https://martinfowler.com/bliki/TestPyramid.html)

---

## 6. Git and Reviews
Version control is non-negotiable. Start with **Git fundamentals**, then build on collaboration practices.

### Git Fundamentals
- Initialize and clone repositories.  
- Stage, commit, and push changes.  
- Branching and merging.  
- Resolving conflicts.  
- Basic history inspection (`git log`, `git diff`).  

### Collaboration & Reviews
- Keep pull requests small and focused.  
- Write clear, descriptive commit messages.  
- Provide kind but direct feedback in code reviews.  

**Resources:**
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)  
- [Pro Git (Free Book)](https://git-scm.com/book/en/v2)  
- [How to Write a Git Commit Message (Chris Beams)](https://chris.beams.io/posts/git-commit/)  

---

## 7. Deploy Basics
Shipping your work is part of development. Know how to do it safely.

- Use environment variables for secrets/configs.
- Document how to roll back if something goes wrong.
- Always leave a “what to do if it breaks” note.

**Resources:**
- [12 Factor App: Config](https://12factor.net/config)  
- [Introduction to CI/CD (Red Hat)](https://www.redhat.com/en/topics/devops/what-is-ci-cd)

---

Stacks change. Frameworks come and go. But if you master these foundations, you’ll be ready to build and grow in any environment.

When you learn a new stack, fill a simple checklist: print text, make an HTTP call, read/write a file, talk to a DB, write one test, log one error.
