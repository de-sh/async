# Asynchronously yours
A journey through rust-land
---

Writing code is tough, but asking a newbie programmer to work on async code might be considered a human rights violation. There are just so many open manholes that can prey on the unknowing, which is why I want to share my journey.

## What is async?
Computers can multi-task like crazy, shifting through everything from complex calculations to moving pixels across a window in well under the time it takes to bat an eyelid. Facilitating this capability is both sophisticated hardware and software. Processors now come with multiple cores which help with running tasks in parallel, and these cores themselves have multiple threads to facilitate concurrency, which can be further extended with OS threads.

Asynchronous programming takes things a step further and allows mutliple threads within a process to run tasks, emblazing individual operations with the ability to run and stop as they please, through the power of cooperative concurrency.

### keywords
Two importants words to keep in mind are `async` and `await`.
