# Lab 7 - Unit & E2E Testing

## Team
- Name: Siddharth Sivalanka

## Check Your Understanding

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

My automated tests would fit within GitHub Action (CI/CD) that would ideally run whenever code is pushed. This catches issues immediately, and it keeps the main branch stable, and is able to provide feedback quickly without depending on each person to remember to run tests manually.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No we should not. End-to-end tests only verify user workflows across many components. In this case, to check a specific function's return value, it is much better handled with a standard unit test.

3. What is the difference between navigation and snapshot mode?

Navigation mode audits the page as it loads from a fresh navigation and can measure load-related performance metrics. Snapshot mode audits the current DOM state at a single moment and is mainly useful for static checks like accessibility issues, not load-time JavaScript performance.

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

- Avoid chaining critical results by reducing the length of the chains, and reducing the download size of the chains
- Improve Image Delivery is something that was suggested. We need to reduce the download time of images to improve percieved load time of the app
- We can optimize the LCP by making the LCP image discoverable from the HTML. This is good, because it will avoid the problem of lazy-loading. 






