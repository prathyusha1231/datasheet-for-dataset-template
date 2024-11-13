# Datasheet for dataset "AIAAIC"

Questions from the [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) paper, v7.

Jump to section:

- [Motivation](#motivation)
- [Composition](#composition)
- [Collection process](#collection-process)
- [Preprocessing/cleaning/labeling](#preprocessingcleaninglabeling)
- [Uses](#uses)
- [Distribution](#distribution)
- [Maintenance](#maintenance)

## Motivation

The AIAAIC Repository (AI, Algorithmic, and Automation Incidents and Controversies) is an independent, open, public-interest resource designed to document incidents and controversies driven by AI, algorithms, and automation.

### For what purpose was the dataset created? 
By providing detailed accounts of risks and harms associated with these systems, the Repository seeks to make AI technologies more transparent, open, and ultimately accountable.

Unlike traditional technical databases focused solely on safety, the AIAAIC Repository adopts a broader "outside-in" perspective, addressing non-technical issues such as:
* Job displacements and economic impacts.
* Environmental damage linked to automation.
* Misleading or hyped marketing practices.
* Anthropomorphism and its societal effects.
* Unethical data usage and privacy concerns.

### Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)?

The AIAAIC Repository is operated by a group of human volunteers committed to fostering responsible AI practices. The repository is maintained as part of a broader initiative to ensure AI systems are transparent and accountable.

### Who funded the creation of the dataset? 

The AIAAIC Repository is funded by donations from individuals worldwide. As a public interest initiative, AIAAIC is dedicated to maintaining independence and being technologically and politically non-partisan. To uphold this commitment, AIAAIC does not accept funding or in-kind donations from commercial entities, ensuring that potential conflicts of interest are avoided.

### Any other comments?

## Composition

### What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)?

The dataset comprises documented incidents and controversies involving AI, algorithms, and automation. Each instance represents a specific incident, described by key details such as the technology involved, affected sectors, and associated harms.

### How many instances are there in total (of each type, if appropriate)?

The dataset includes multiple entries. Based on the sample data, it contains incidents categorized as "Issue" or "Incident." The exact count is 1799.

### Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?

The dataset is a curated sample of incidents and controversies reported globally. While comprehensive, it does not capture all potential incidents and is likely subject to ongoing updates.

### What data does each instance consist of? 

Each instance consists of:
* A unique identifier (AIAAIC ID#).
* Headline or description of the incident.
* Type (Issue/Incident).
* Date and location of occurrence.
* Impacted sectors and entities (Deployers, Developers).
* Issues, transparency concerns, and associated harms.
* Links to further information.

### Is there a label or target associated with each instance?

Yes, labels include:
* Type: "Issue" or "Incident."
* Sector(s): Industry impacted.
* Issues: Core themes, such as employment or environmental concerns.
* Harms: External (societal) or internal (organizational).

### Is any information missing from individual instances?

Some entries have incomplete data, such as missing developer names, exact geographic locations, or detailed harms, likely due to limitations in the original reporting.

### Are relationships between individual instances made explicit (e.g., users’ movie ratings, social network links)?

No explicit relationships between instances are documented. However, shared attributes like "Sector" or "Issue" can be used to infer connections.

### Are there recommended data splits (e.g., training, development/validation, testing)?

No predefined splits are provided, as the dataset is primarily for analysis and reference purposes.

### Are there any errors, sources of noise, or redundancies in the dataset?

The dataset may include minor inconsistencies or redundancies, such as overlapping issues across similar incidents, due to variations in reporting.

### Is the dataset self-contained, or does it link to or otherwise rely on external resources (e.g., websites, tweets, other datasets)?

The dataset includes links to external resources, such as reports and news articles, for detailed descriptions of incidents. These links are subject to availability over time.

### Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals’ non-public communications)?

No, the dataset is built entirely from publicly available information and does not include confidential or privileged data.

### Does the dataset contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety?

Yes, some incidents involve sensitive topics, such as discrimination, economic harm, or safety concerns, which could cause anxiety for certain audiences.

### Does the dataset relate to people? 

Yes, some incidents involve individuals or groups impacted by AI systems. However, the dataset does not contain personally identifiable information (PII).

### Does the dataset identify any subpopulations (e.g., by age, gender)?

The dataset does not explicitly identify subpopulations but may reference affected demographics (e.g., workers, students) in the descriptions.

### Is it possible to identify individuals (i.e., one or more natural persons), either directly or indirectly (i.e., in combination with other data) from the dataset?

No, the dataset does not include information that could directly or indirectly identify individuals.

### Does the dataset contain data that might be considered sensitive in any way (e.g., data that reveals racial or ethnic origins, sexual orientations, religious beliefs, political opinions or union memberships, or locations; financial or health data; biometric or genetic data; forms of government identification, such as social security numbers; criminal history)?

The dataset references sensitive issues in the context of incidents (e.g., ethical violations or discrimination) but does not include sensitive personal data.

### Any other comments?
The AIAAIC dataset provides a broad and ethical overview of incidents and controversies, with a focus on transparency and public accountability, ensuring responsible use.

## Collection process

### How was the data associated with each instance acquired?

All entries in the AIAAIC Repository are manually compiled by the team. Incidents are identified through:
* Submissions from third parties via the AIAAIC website.
* Contributions from community members shared via email or social media.
* Web searches and Google Alerts.

### What mechanisms or procedures were used to collect the data (e.g., hardware apparatus or sensor, manual human curation, software program, software API)?

The data collection process involves a six-step manual workflow:
  1.  Detect: Identifying incidents through submissions, web searches, and alerts.
  2.  Assess: Evaluating incidents against qualitative criteria, such as relevance, impacts, and credibility.
  3.  Classify: Categorizing entries based on AIAAIC's classifications and definitions.
  4.  Summarize: Writing a brief summary for each entry.
  5.  Approve: Ensuring accuracy, fairness, and legality through editorial review.
  6.  Publish: Publishing the entries on the AIAAIC website and Google sheet.

### If the dataset is a sample from a larger set, what was the sampling strategy (e.g., deterministic, probabilistic with specific sampling probabilities)?

The dataset is a curated sample of incidents, selected based on their relevance to AI, algorithmic, and automation controversies. The sampling strategy focuses on ensuring diverse geographic, sectoral, and technological representation.

### Who was involved in the data collection process (e.g., students, crowdworkers, contractors) and how were they compensated (e.g., how much were crowdworkers paid)?

The dataset is created and maintained by a team of human volunteers. No monetary compensation is provided, as the project operates on a public-interest model and relies on donations.

### Over what timeframe was the data collected?

The dataset is continuously updated, with new incidents added as they occur. Historical incidents have been documented retrospectively to provide a comprehensive view of AI-related controversies over time.

### Were any ethical review processes conducted (e.g., by an institutional review board)?

No formal ethical review processes were conducted. However, the editorial team ensures that all entries meet standards of accuracy, fairness, balance, and legality before publication.

### Does the dataset relate to people?

Yes, some incidents involve individuals or groups impacted by AI systems. However, no personal or identifiable data is included.

### Did you collect the data from the individuals in question directly, or obtain it via third parties or other sources (e.g., websites)?

The data is obtained from third-party sources, including news reports, legal documents, and research studies. In some cases, whistleblowers or third parties submit information directly to the Repository.

### Were the individuals in question notified about the data collection?

Not applicable, as the data is gathered from publicly available sources, and no direct data collection from individuals occurs.

### Did the individuals in question consent to the collection and use of their data?

Not applicable, as the data does not involve personal or private information requiring consent.

### If consent was obtained, were the consenting individuals provided with a mechanism to revoke their consent in the future or for certain uses?

Not applicable.

### Has an analysis of the potential impact of the dataset and its use on data subjects (e.g., a data protection impact analysis) been conducted?

No formal data protection impact analysis has been conducted, as the dataset does not include personal data and relies entirely on publicly available information.

### Any other comments?

The AIAAIC Repository is designed with a focus on ethical curation and responsible documentation. Its rigorous verification and editorial processes ensure that the dataset is accurate, balanced, and suitable for public use.

## Preprocessing/cleaning/labeling

### Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)?

Based on the nature of the dataset:
* The dataset appears to have been curated manually by the AIAAIC team.
* Entries are likely reviewed and classified based on relevance, impacts, and categories (e.g., "Type," "Sector," and "Issues").

### Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)?

There is no indication that raw data is retained. The publicly available dataset contains only the curated and approved entries.

### Is the software used to preprocess/clean/label the instances available?

Preprocessing and labeling appear to have been conducted manually. No specific software or automated tools are mentioned.

### Any other comments?

## Uses

### Has the dataset been used for any tasks already?

Yes, the AIAAIC Repository has been used as a reference and research tool by various stakeholders, including:
* Researchers studying AI ethics and risks.
* Educators developing training and educational materials.
* Policymakers and advocacy groups analyzing AI's societal impacts.

### Is there a repository that links to any or all papers or systems that use the dataset?

No specific repository for related papers or systems is mentioned. However, users of the dataset may refer to it directly through the AIAAIC website and the Google sheet.

### What (other) tasks could the dataset be used for?

The dataset has broad applicability, including:
* Qualitative and Quantitative Research: Studying patterns in AI-related controversies, such as biases or environmental harms.
* Policy Development: Informing guidelines for responsible AI adoption.
* Educational Campaigns: Creating training programs or workshops focused on AI ethics.
* Public Advocacy: Supporting campaigns highlighting the societal risks of AI systems.

### Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses?

Yes, the following considerations may affect future use:
* Bias in Incident Selection: While curated carefully, incidents may reflect certain geographic or media biases based on available reports.
* Qualitative Nature: The dataset’s qualitative focus may limit its direct application to highly quantitative tasks, such as predictive modeling.

### Are there tasks for which the dataset should not be used?

The dataset is not intended for:
* Developing AI systems directly, as it documents controversies and risks.
* Tasks requiring granular, quantitative data, such as detailed statistical modeling or benchmarking.

### Any other comments?

The AIAAIC Repository is a valuable resource for analyzing ethical and societal implications of AI systems. Users should be mindful of its focus on qualitative insights and potential biases in incident representation.

## Distribution

### Will the dataset be distributed to third parties outside of the entity (e.g., company, institution, organization) on behalf of which the dataset was created? 

Yes, the dataset is publicly available and accessible to anyone through the AIAAIC website and Google sheet.

### How will the dataset will be distributed (e.g., tarball on website, API, GitHub)?

The dataset is distributed via:
* A publicly accessible Google sheet.
* The AIAAIC Repository website.
No, the dataset does not currently have a DOI.

### When will the dataset be distributed?

The dataset is continuously available to the public and updated regularly.

### Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?

There are no specific details about licensing provided. However, as a public-interest initiative, the dataset is likely intended for open use with proper attribution. Users should check the AIAAIC website for any specific terms of use.

### Have any third parties imposed IP-based or other restrictions on the data associated with the instances?

No third-party restrictions on the dataset have been mentioned. The data is curated from publicly available sources.

### Do any export controls or other regulatory restrictions apply to the dataset or to individual instances?

No export controls or regulatory restrictions are indicated.

### Any other comments?

The dataset’s open-access model ensures wide usability for researchers, educators, policymakers, and the general public. Users should verify any specific usage terms on the AIAAIC website.

## Maintenance

### Who is supporting/hosting/maintaining the dataset?

The dataset is maintained by the AIAAIC team, a group of human volunteers committed to promoting transparency, openness, and accountability in AI systems.

### How can the owner/curator/manager of the dataset be contacted (e.g., email address)?

The AIAAIC team can be contacted through the official AIAAIC website or via email and social media channels, as specified on their website.

### Is there an erratum?

No specific erratum has been mentioned. Any corrections or updates are likely made directly within the dataset.

### Will the dataset be updated (e.g., to correct labeling errors, add new instances, delete instances)?

Yes, the dataset is continuously updated to include:
* Newly reported incidents and issues.
* Corrections to existing entries as needed.
Updates are made by the AIAAIC team and published on the repository.

### If the dataset relates to people, are there applicable limits on the retention of the data associated with the instances (e.g., were individuals in question told that their data would be retained for a fixed period of time and then deleted)?

Not applicable, as the dataset does not include personal or identifiable data about individuals.

### Will older versions of the dataset continue to be supported/hosted/maintained?

Older versions are not explicitly maintained, as updates are made directly to the live dataset. Users always have access to the latest version via the AIAAIC website.

### If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?

Yes, contributions can be made via:
* Submissions through the AIAAIC website.
* Sharing relevant incidents via email or social media.
* Submissions are assessed and verified before being added to the dataset.

### Any other comments?
The AIAAIC team’s commitment to ongoing updates ensures that the dataset remains relevant and reflective of emerging issues in AI, algorithms, and automation. Contributions from the community further enhance its comprehensiveness.
