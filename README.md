# fortune500

A dataset of privacy policies from 2019 Fortune 500 companies.

# Datasets

- [x] **fortune500.csv**: A high-level dataset of the latest Fortune 500 companies (accurate as of February 2020). Columns: **company_name**, **rank**, **revenue**, **revenue_percent_change**, **profits**, **profits_percent_change**, **assets**, **employees**, **previous_rank**, **industry**, **sector**, **ceo**, **ceo_title**, **location**,	**website**, **years_on_F500**.

- [x] **fortune500_policy_urls.csv**: Fortune 500 company privacy policy URLs. If available, an online privacy policy takes precedent. If not, a general or global policy URL is used. If these are not available, a Terms page is included. Otherwise, the **policy_url** column will be blank. Columns: **company_name**, **rank**, **website**, **policy_url**. 

- [x] **fortune500_policy_htmls**: A .tar.gz containing Fortune 500 privacy policies in HTML or PDF format. Extracted from URLs in **fortune500_policy_urls.csv**. Filename structure: **RANK_URL.html** (ex. *1_corporate_walmart_com.html*).

- [ ] **fortune500_policy_screenshots**: A .tar.gz containing Fortune 500 privacy policy URL page screenshots. Filename structure: **RANK_URL.png** (ex. 1_corporate_walmart_com.png).

- [ ] **fortune500_raw_policy_text**: A .tar.gz containing all text extracted from the Fortune 500 privacy policy HTMLs or PDFs from **fortune500_policy_htmls**, boilerplate included.

- [ ] **fortune500_policy_text**: A folder containing text extracted from the Fortune 500 privacy policy HTMLs or PDFs from **fortune500_policy_htmls** (no boilerplate). Extracted using [extractarticletext.com](https://extractarticletext.com).


