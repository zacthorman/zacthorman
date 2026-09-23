### Isaac (Zac) Thorman

Economics graduate from the University of Nottingham, working in tech recruitment and research in London. In the evenings I build analytical tools in Python and then test whether they actually work, which is usually the more interesting half.

[**CV and portfolio**](https://zacthorman.github.io) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/isaacthorman) &nbsp;·&nbsp; [zdthorman@gmail.com](mailto:zdthorman@gmail.com)

---

#### Projects

**[stocksignal](https://github.com/zacthorman/stocksignal)** &nbsp;`Python` `pandas` `SQLite` `pytest` `GitHub Actions`  
Turns a written trading rulebook into mechanical daily screens, logs every call and scores it against what happened next. The backtest ran walk-forward over six years and 252 US equities, with costs, next-open fills and success criteria committed before the run. The screens did not beat an index tracker, and the README says so. 580 tests, CI on every push, a scan that runs itself every weekday.

**[Hit-Rates](https://github.com/zacthorman/Hit-Rates)** &nbsp;`Python` `pandas` `JavaScript` `GitHub Pages` &nbsp;[live site](https://zacthorman.github.io/Hit-Rates/)  
Pulls every stat SofaScore tracks for a fixture and prices each hit rate twice: on the raw figure and on the bottom of its confidence interval, because ten matches cannot tell 80% from 55%. A backtest replays past fixtures to check the probabilities are calibrated. When confident player calls said 75.5% and landed 68.2%, the model got a correction tested out of sample. Nine competitions across football and the NFL, rebuilt and published on a schedule.

**[breakpoint-arcade](https://github.com/zacthorman/breakpoint-arcade)** &nbsp;`HTML` `JavaScript` `PWA`  
A single-file app for learning to read code: read listings, drill the patterns, then break six browser games built to be broken. Three tasks a day, every round regenerated so it cannot be memorised, and it installs to a phone and works offline.

---

#### How I work

- **Decide the test before seeing the data.** Success criteria go in a pre-registration file and get committed before the run, so a result cannot be argued into looking good afterwards.
- **Publish the negative result.** Most portfolio projects claim to work. These say what was measured, including where it fell short.
- **Check the checker.** A backtest that measures the wrong thing is worse than no backtest, so the tests and the backtests get tested too.

#### Toolkit

Python (pandas, NumPy) · SQLite · pytest · GitHub Actions · Excel · Bloomberg · Macrobond · statistical inference · walk-forward backtesting
