---
permalink: /projects/
title: "Projects"
---

- **Project 1.** Creation of Data Pipeline within AWS Sagemaker

Utilizing Google Big Query datasets and Python's Pandas and Polars packages, I created a data pipeline that converted large data sets into optimized Parquet files, and then Hyper files for Tableau. I made use of Polar's LazyFrame feature which allowed me to process and maniulate large datasets by deffering computations until collecting the final end-result and improve speed and memory efficiency. I aggregated, filtered, and joined data tables through Polars. 

The result at the collection of the final lazyframe was a parquet file that was a combination of an excel file and multiple BigQuery data sets that spanned over 20 million rows. Once I created the Parquet file and turned it into Hyper file, it was ready for use in Tableau as an extract data source. Below is the flowchart of this project.

<div style="position: relative; width: 100%; height: 0; padding-top: 75.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGteKsDZYA/0jtpPTpshZqG-__PNTcjsA/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGteKsDZYA&#x2F;0jtpPTpshZqG-__PNTcjsA&#x2F;view?utm_content=DAGteKsDZYA&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Google Big Query Tables</a> by Andreas Michaeloff

- **Project 2.** Decision Support System

  Through advanced SQL techniques (CTEs, window functions, nested queries) and Tableau dashboarding, I generated a automated data source within Custom SQL code in Tableau that simplifies customer decision-making. This tool makes it easier for customers to either replace or repair a large piece of equipment, when its time for that decision to be made. This tool provides the customer and PMs with all the information needed to quickly take action, through a recommendation that takes into account equipment age, component costs, and lead times to name a few.
