---
title: "Enhancing reporting and analytics with SQL Server 2025 tools and services"
url: "https://www.microsoft.com/en-us/sql-server/blog/2025/06/19/enhancing-reporting-and-analytics-with-sql-server-2025-tools-and-services/"
date: "Thu, 19 Jun 2025 16:00:00 +0000"
author: "Debbi Lyons"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<div class="wp-block-msxcm-kicker-container">
	<div class=" wp-block-msxcm-kicker-block wp-block-msxcm-kicker--align-right">
		<p class="wp-block-msxcm-kicker__title small text-neutral-400 text-uppercase">
			SQL Server 2025 public preview announcement		</p>
		<a class="wp-block-msxcm-kicker__cta btn btn-link p-0 text-decoration-none" href="https://aka.ms/sqlserver2025" target="_blank">
			<span>Read the blog</span> <span class="glyph-append glyph-append-xsmall wp-block-msxcm-kicker__glyph glyph-append-go"></span>
		</a>
	</div>
</div>



<p>At Microsoft Build 2025, we announced the public preview of SQL Server 2025. Built on a foundation of best-in-class security, performance, and availability, <a href="https://info.microsoft.com/ww-landing-sql-server-2025.html">SQL Server 2025</a> empowers customers to accelerate AI using their own data. The momentum doesn’t stop there. This release also brings major updates to the tools and services that power enterprise-grade reporting, analysis and integration services. In this blog, we’ll walk you through what’s new across these services so you can plan your upgrade holistically and unlock the full potential of SQL Server 2025.</p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button has-custom-width wp-block-button__width-50"><a class="wp-block-button__link wp-element-button" href="https://info.microsoft.com/ww-landing-sql-server-2025.html">Get started with SQL Server 2025</a></div>
</div>



<h2 class="wp-block-heading" id="sql-server-2025-reporting-services">
  SQL Server 2025 Reporting Services
</h2>



<p>
  For over two decades, SQL Server Reporting Services (SSRS) has been the go-to on-premises solution for creating and managing paginated reports using Report Definition Language (RDL). With SQL Server 2025, we’re taking a step forward.
</p>



<p>
  Power BI Report Server will now be the default reporting solution for SQL Server 2025. This modern platform supports both paginated and interactive reports, enabling users to build reusable data models and deliver rich, customized reporting experiences. It also offers built-in compatibility with Power BI, providing a seamless path to the cloud.
</p>



<p>
  As part of this transition, we will not be releasing a new version of SSRS for SQL Server 2025. However, if you prefer to continue using SSRS, support will remain in place for both SQL Server 2025 and all in-market versions of SQL Server.
</p>


<figure class="wp-block-image"><img alt="Power BI Report Server will now be the default reporting solution for SQL Server 2025. This modern platform supports both paginated and interactive reports, enabling users to build reusable data models and deliver rich, customized reporting experiences." class="wp-image-51261 webp-format" src="https://www.microsoft.com/en-us/sql-server/blog/wp-content/uploads/2025/06/a-screenshot-of-a-computer-ai-generated-content-m.webp" /></figure>



<p>If you’re testing SQL Server 2025 preview, we recommend including the move to Power BI Report Server in your upgrade plan. Download the <a href="https://learn.microsoft.com/power-bi/report-server/install-report-server" rel="noreferrer noopener" target="_blank">free trial</a> of Power BI Report Server and explore the latest features to see if it meets your reporting needs. When SQL Server 2025 becomes generally available, any customer with a paid SQL Server license will have access to Power BI Report Server, which was previously limited to Enterprise edition customers with Software Assurance.</p>



<p>For customers currently using Enterprise edition of SQL Server 2022 or earlier with Software Assurance, migrating from SQL Server Reporting Services (SSRS) to Power BI Report Server (PBIRS) is a <a href="https://learn.microsoft.com/power-bi/report-server/migrate-report-server#migration-to-power-bi-report-server-from-ssrs-sharepoint-integrated-mode" rel="noreferrer noopener" target="_blank">straightforward process</a>. Most RDL report assets created in SSRS are fully compatible with PBIRS, making the transition less effort for the majority of users.</p>



<p>For more questions, <a href="https://learn.microsoft.com/sql/reporting-services/reporting-services-consolidation-faq?view=sql-server-ver17" rel="noreferrer noopener" target="_blank">review the FAQ</a>. </p>



<h2 class="wp-block-heading" id="sql-server-2025-analysis-services">SQL Server 2025 Analysis Services </h2>



<p>SQL Server 2025 Analysis Services (SSAS) introduces several key enhancements aimed at improving performance, scalability, and modeling flexibility. </p>



<p>We have made significant performance improvements for Multidimensional Expressions (MDX) queries on models with Calculation Groups and Format Strings to reduce memory usage and improve responsiveness. The latest changes will greatly improve the performance and reliability of operations in Analyze in Excel on models that include Dynamic Format Strings for Measures and Calculated Items with Format Strings. For more details, refer to the&nbsp;<a href="https://learn.microsoft.com/power-bi/create-reports/desktop-dynamic-format-strings" rel="noreferrer noopener" target="_blank">Dynamic format strings&nbsp;</a>documentation. </p>



<p>Improved parallelism in DirectQuery mode enables faster response times for complex queries. The fundamental idea is to maximize query performance by parallelizing multiple queries to the datasource for a single Data Analysis Expressions (DAX) query. This query parallelization reduces the impact of data source delays and network latencies on query performance.</p>



<p>For more details, refer to the&nbsp;<a href="https://powerbi.microsoft.com/blog/query-parallelization-helps-to-boost-power-bi-dataset-performance-in-directquery-mode/" rel="noreferrer noopener" target="_blank">Query parallelization helps to boost the Power BI dataset performance in DirectQuery mode</a>&nbsp;blog post.</p>



<p>SSAS 2025 incorporates the latest version of Horizontal Fusion, a query performance optimization that reduces the number of SQL queries generated by DAX, improving DirectQuery efficiency. For more details, refer to the&nbsp;<a href="https://powerbi.microsoft.com/blog/announcing-horizontal-fusion-a-query-performance-optimization-in-power-bi-and-analysis-services/" rel="noreferrer noopener" target="_blank">Announcing “Horizontal Fusion,” a query performance optimization in Power BI and Analysis Services</a>&nbsp;blog post.</p>



<p>Find more about what’s new in <a href="https://learn.microsoft.com/analysis-services/what-s-new-in-sql-server-analysis-services?view=sql-analysis-services-2025" rel="noreferrer noopener" target="_blank">SQL Server 2025 Analysis Services</a>.</p>



<h2 class="wp-block-heading" id="sql-server-2025-integration-services">SQL Server 2025 Integration Services</h2>



<p>
  One of the notable updates in SQL Server 2025 Integration Services (SSIS) is the improved support for ADO.NET connectivity. Historically, the ADO.NET connection manager had limitations such as the lack of ability to connect using Entra ID authentication. This posed challenges for organizations adopting modern identity solutions and cloud-first strategies.
</p>



<p>Now, with the introduction of the Microsoft SqlClient Data Provider in ADO.NET connection manager, SSIS addresses this gap. This new capability brings the support for Entra ID authentication, enabling more secure and flexible connection scenarios. </p>



<p>Find more about what’s new in <a href="https://learn.microsoft.com/sql/integration-services/what-s-new-in-integration-services-in-sql-server-2025?view=sql-server-ver17" rel="noreferrer noopener" target="_blank">SQL Server 2025 Integration Services</a>.</p>



<h2 class="wp-block-heading" id="explore-more-resources">Explore more resources</h2>



<ul class="wp-block-list">
<li>Check out the <a href="https://learn.microsoft.com/sql/sql-server/what-s-new-in-sql-server-2025?view=sql-server-ver17" rel="noreferrer noopener" target="_blank">SQL Server docs</a> to learn more about SQL Server 2025. </li>



<li>Visit the <a href="https://learn.microsoft.com/power-bi/report-server/" rel="noreferrer noopener" target="_blank">Power BI Report Server docs</a> to learn about PBRIS. </li>



<li>Learn more about <a href="https://learn.microsoft.com/power-bi/report-server/migrate-report-server#migration-to-power-bi-report-server-from-ssrs-sharepoint-integrated-mode" rel="noreferrer noopener" target="_blank">migrating to Power BI Report Server</a> from SSRS.</li>



<li>Get your questions answered with <a href="https://learn.microsoft.com/en-us/sql/reporting-services/reporting-services-consolidation-faq?view=sql-server-ver17" rel="noreferrer noopener" target="_blank">Reporting Services consolidation FAQ</a>.</li>
</ul>



<p></p>
<p>The post <a href="https://www.microsoft.com/en-us/sql-server/blog/2025/06/19/enhancing-reporting-and-analytics-with-sql-server-2025-tools-and-services/">Enhancing reporting and analytics with SQL Server 2025 tools and services</a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
