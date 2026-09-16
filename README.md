## About me

👋 Hi, my name is April Wu.

I build case studies in machine learning, NLP, operations analytics, and valuation, taking each from raw data through to a decision someone can act on. Before moving into data I spent over three years in corporate finance and investment operations. As an investment accountant at a licensed asset manager I handled portfolio valuation, daily NAV production and custodian reconciliation across the book of funds I carried.

**[Portfolio](https://portfolio-april-wu.netlify.app)** · The case studies below, each written up in full.

**[Career Suite](https://career-suite.ilume2cloud.workers.dev/)** · A free job-search management platform I built and shipped, open for sign-up.

---

### Case studies

Repositories are published progressively; linked titles are the ones already up.

#### Machine Learning & Text Analytics

**[Building Energy](https://github.com/aries-cloud/Portfolio_Building-Energy)** · Nine models across regression, classification and clustering on Seattle benchmarking data. Upgrading the model bought ΔR² −0.002; upgrading the features bought +0.078. The conclusion was replicated independently on CBECS national survey data.
`XGBoost` `Random Forest` `SVR` `MLP` `leakage audit`

**[Clickbait Spoiling](https://github.com/aries-cloud/Portfolio_Clickbait-Spoiling)** · A four-stage system on the Webis corpus. The decisive finding came from the data rather than the models: 81.5% of spoilers appear verbatim in the linked article, which reframes generation as reading comprehension. Extractive QA duly beat free-form generation at METEOR 0.420 against 0.331, and classification reached 0.739 macro-F1, 3.6× the naive baseline.
`RoBERTa` `T5` `PyTorch` `ablations`

**Review Sentiment** · Three text representations over 800k Amazon reviews, on one test set. Naive Bayes on n-gram counts (0.8321) beats a neural network on mean-pooled Word2Vec (0.7919). The four-point gap traces back to word order, which mean pooling destroys.
`Naive Bayes` `Word2Vec` `PyTorch`

---

#### Operations & Decision Analytics

**[Clinic Capacity](https://github.com/aries-cloud/Portfolio_Clinic-Capacity)** · Free-text therapy notes turned into a validated progress measure, then trajectory clusters, then a newsvendor reassessment policy. Frees 29.2% of baseline demand as new intake capacity.
`K-means` `logistic regression` `newsvendor`

**Demand Estimation** · Sold-out items make sales a record of the shelf rather than of demand. Curve clustering recovers the 10.5% that sales data cannot see, and prices are then optimized under business constraints.
`regression tree` `predict-then-optimize`

**Ride-Hailing Pricing** · A raw price comparison between two platforms that reverses direction once trip distance is controlled, and a significant interaction term that turns out to be a false alarm. The gap sits in the base fare, not the per-mile rate.
`Welch t-test` `ANOVA`

---

#### Valuation

**Fund Valuation Reconciliation** · An asset manager and its custodian bank each keep a full set of books for the same fund, under charts of accounts that differ in granularity, grouping and naming. A five-step pandas pipeline translates one chart into the other and reports only the breaks. Two rows carry the result: a 1.84M difference in retained earnings sitting beside a period profit that agreed to within one cent. Figures throughout are from an anonymised dataset.
`pandas` `chart-of-accounts mapping` `break detection` `anonymised data`

---

**Toolkit** Python · SQL · R · scikit-learn · PyTorch / Transformers · pandas / NumPy

**Reach me** [LinkedIn](https://www.linkedin.com/in/yawu/) · aries2cloud@gmail.com
