# ROSS Index

- **2020:** [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2020/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2020/Q3), [Q4](https://github.com/RunaCapital/ROSS-Index/tree/main/2020/Q4)  
- **2021:** [Q1](https://github.com/RunaCapital/ROSS-Index/tree/main/2021/Q1), [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2021/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2021/Q3), [Q4](https://github.com/RunaCapital/ROSS-Index/tree/main/2021/Q4)  
- **2022:** [Q1](https://github.com/RunaCapital/ROSS-Index/tree/main/2022/Q1), [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2022/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2022/Q3), [Q4](https://github.com/RunaCapital/ROSS-Index/tree/main/2022/Q4)
- **2023:** [Q1](https://github.com/RunaCapital/ROSS-Index/tree/main/2023/Q1), [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2023/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2023/Q3), [Q4](https://github.com/RunaCapital/ROSS-Index/tree/main/2023/Q4)
- **2024:** [Q1](https://github.com/RunaCapital/ROSS-Index/tree/main/2024/Q1), [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2024/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2024/Q3), [Q4](https://github.com/RunaCapital/ROSS-Index/tree/main/2024/Q4)
- **2025:** [Q1](https://github.com/RunaCapital/ROSS-Index/tree/main/2025/Q1), [Q2](https://github.com/RunaCapital/ROSS-Index/tree/main/2025/Q2), [Q3](https://github.com/RunaCapital/ROSS-Index/tree/main/2025/Q3)

## Overview

Since Q2 2020, the **[ROSS Index](https://runacap.com/ross-index/url)** publishes the top open-source startups by the relative growth rate of GitHub stars at their repositories. The calculation of the growth rate starts from the moment when a repo crosses a 1000-star mark, and the results are published every quarter.

The purpose of this index is to highlight new, trending open-source startups using a simple and transparent basis. It is maintained by venture capital firm Runa Capital, which has invested early in many OSS startups, including [n8n](https://n8n.io/), [Nginx](http://nginx.com/), [MariaDB](https://mariadb.com/), [Twenty](https://twenty.com/) and [Mastra](https://mastra.ai/).

## Methodology

### Why do we only use GitHub star growth?

We chose only one basic metric as, otherwise, it would be hard to verify the index results externally. Any composite and complex derivative metrics overcomplicate the picture and are better consumed internally. 

We chose “stars” because it allows for a reasonable comparison between various repos using the same scale while showing trending open-source products. There is no perfect business metric for open-source software — all have their flaws. For instance, “contributors” are good for comparing “apples to apples” (e.g. databases), but can barely be used for different categories of software. Stars seem the best single metric for index purposes.

We measure the relative growth of stars (and not absolute) because it shifts focus from established open-source champions to interesting newcomers in the developer community. GitHub has network effects, so it is easier to acquire stars for already well-starred repos. But this index is about startups!

### Calculation approach (since Q1 2024)
We rank repositories based on their maximum star growth rate over all 90-day periods ending within the target quarter. The ranking criteria are:

1. The observation period can begin only when the repo has 1,000+ stars.
2. The observation period always consists of 90 consecutive days.
3. The observation period must end within the target quarter.
4. Growth rate is calculated as: (Stars at period end) / (Stars at period start)

Repositories are then ranked by their growth rate in descending order. Our team only selects the repos belonging to startups and publishes the top-20 in the ranking. If a startup has several top repos, we will only mention the one with the best growth rate.

### Startup definition
For purposes of the index, we define a “startup” as a product-focused commercial organization that

1. was founded fewer than ten years ago
2. raised less than $100M in total known funding
3. has a product reasonably connected to its open-source repos
4. was not acquired or went public before the end of the target period

This definition does not cover, for instance, side projects. For example, when a founder has another full-time job. Nor does it include projects without any associated commercial product-focused entity or those developed by large tech corporations. The definition also excludes businesses that are mostly focused on the provision of professional services.

### Open source definition

As VC investors, here we stick to the commercial perception of an “open source company” - a tech business leveraging OSS playbook as an approach for product development and go-to-market strategy. So, we would consider, for example, MongoDB as an example of such a company, although their Server Side Public License is not approved by the OSI. The same applies to some source-available participants in the ROSS Index.﻿

### Data sources

The index publications are based only on public data from GitHub, Crunchbase, mass media, and other sources. We strive to show cities and countries connected with the origin of companies, not just formal HQ locations. We are purely focused on companies using English descriptions, so some local startups (e.g. Chinese) could be missed.

Given the open-source nature of data, some inaccuracies are possible. In any case, Runa Capital does not use any private information received from startups for the index. For instance, we may know that a company raised a new VC round but we will only publish publicly available numbers like those on Crunchbase.

### Old calculation approach (2020-2023)
In 2020-2023, we have been calculating the relative growth of stars within the fixed period (quarter or year) for all repos with at least 1,000 stars at the start of the period. For that rankings, we used the annualized growth rate which was calculated as AGR = (value now / value 1 quarter ago)⁴ – 1.

Since Q1 2024, we slightly updated the approach with sliding “90-day windows” to detect fast-growing repos even if their growth spike happened between calendar period.
