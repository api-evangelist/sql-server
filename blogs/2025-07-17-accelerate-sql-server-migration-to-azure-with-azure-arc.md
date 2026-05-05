---
title: "Accelerate SQL Server Migration to Azure with Azure Arc"
url: "https://www.microsoft.com/en-us/sql-server/blog/2025/07/17/accelerate-sql-server-migration-to-azure-with-azure-arc/"
date: "Thu, 17 Jul 2025 21:00:00 +0000"
author: "Debbi Lyons"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<p>We’re excited to announce a new migration capability in Azure Arc to simplify and accelerate SQL Server migration. This new capability, now generally available, is powered by Azure Database Migration Service and it offers seamless, end-to-end migration capabilities including continuous migration assessments, simplified provisioning, and real-time database replication, assisted by Copilot in Azure. What once took months can now be accomplished in just days, with confidence, continuity, and control.&nbsp;</p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://learn.microsoft.com/en-us/sql/sql-server/azure-arc/migrate-to-azure-sql-managed-instance">Learn more about the new migration capability in Azure Arc</a></div>
</div>



<h2 class="wp-block-heading" id="end-to-end-migration-simplified">End-to-end migration simplified</h2>



<p>If you’ve been using SQL Server enabled by Azure Arc, you’re likely familiar with <a href="https://techcommunity.microsoft.com/blog/microsoftdatamigration/general-availability-continuous-migration-assessment-for-sql-server-enabled-by-a/4430603" rel="noreferrer noopener" target="_blank">continuous migration assessments</a> that offer target recommendations, technical readiness, and cost estimates. Now, we’re taking the next step forward by introducing automated, end-to-end migration capabilities in SQL Server enabled by Azure Arc.</p>



<p>Once you&#8217;ve assessed the Azure readiness of your SQL Server instances, you can now select or provision your Azure targets such as <a href="https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview?view=azuresql" rel="noreferrer noopener" target="_blank">Azure SQL Managed Instance</a>, without jumping between various tools or places in the Azure portal. This streamlined workflow eliminates context switching and simplifies provisioning. You’ll see estimated costs during the provisioning process, giving you clear visibility and confidence to plan ahead. Plus, you can take advantage of the <a href="https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/free-offer?view=azuresql" rel="noreferrer noopener" target="_blank">free Azure SQL Managed Instance offer</a> to evaluate at no cost, making it easier to get started.&nbsp;</p>



<p>Real-time database replication is also integrated into the new migration capability. This new method, built on top of distributed availability groups, enables near real-time database replication from SQL Server to Azure SQL Managed Instance. Setting up real-time replication manually can be a complex multi-step process, but Azure Arc simplifies the entire process while providing best-in-class monitoring. If a customer decides to go back to on-premises, Azure SQL Managed Instance Link also supports seamless failback (if the source SQL Server instance is SQL Server 2022 and above).&nbsp;</p>



<h2 class="wp-block-heading" id="migrate-with-confidence">Migrate with confidence&nbsp;</h2>



<p>The new capability empowers customers to migrate with confidence. Before officially cutting over, you can validate that the target Azure SQL Managed Instance meets your business requirements by using the target instance as a read-only replica.&nbsp;&nbsp;</p>



<p>In addition, the <a href="https://techcommunity.microsoft.com/blog/microsoftdatamigration/client-connection-summary-for-sql-server-enabled-by-azure-arc/4398297" rel="noreferrer noopener" target="_blank">client connection summary feature</a> in SQL Server, enabled by Azure Arc, automatically and continuously captures and displays which clients are connecting to each instance. This replaces the previous manual and time-consuming process of tracing applications to their databases, giving customers clear visibility and helping ensure a smooth transition to Azure.</p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://learn.microsoft.com/en-us/sql/sql-server/azure-arc/connect?view=sql-server-ver17&amp;tabs=windows">Innovate anywhere with Azure Arc</a></div>
</div>



<h2 class="wp-block-heading" id="get-started-today">Get started today&nbsp;</h2>



<p>If you’re looking to simplify and accelerate your migration to Azure, this new connected capability can help you get there faster—with less downtime, lower overhead, and more confidence.&nbsp;</p>



<ul class="wp-block-list">
<li>Learn more on our <a href="https://aka.ms/arc-migrations-ga-blogpost" rel="noreferrer noopener" target="_blank">Tech Community blog</a>.</li>



<li>Learn more about the <a href="https://learn.microsoft.com/sql/sql-server/azure-arc/migrate-to-azure-sql-managed-instance" rel="noreferrer noopener" target="_blank">new migration capability in Azure Arc</a> on Microsoft Learn.</li>



<li>Onboard your <a href="https://learn.microsoft.com/en-us/sql/sql-server/azure-arc/connect?view=sql-server-ver17&amp;tabs=windows" rel="noreferrer noopener" target="_blank">SQL Server to Azure Arc</a> today.</li>



<li>Learn more about <a href="https://techcommunity.microsoft.com/blog/microsoftdatamigration/general-availability-continuous-migration-assessment-for-sql-server-enabled-by-a/4430603" rel="noreferrer noopener" target="_blank">continuous migration assessment</a> from SQL Server enabled by Azure Arc.</li>
</ul>



<h2 class="wp-block-heading" id="frequently-asked-questions">Frequently asked questions&nbsp;</h2>



<p><strong>1. What is SQL Server enabled by Azure Arc?&nbsp;&nbsp;</strong></p>



<p><a href="https://review.learn.microsoft.com/en-us/sql/sql-server/azure-arc/overview?view=sql-server-ver17&amp;branch=pr-en-us-34175" rel="noreferrer noopener" target="_blank">SQL Server enabled by Azure Arc</a> extends Azure services to SQL Server instances hosted outside of Azure: in your data center, in edge site locations like retail stores, or any public cloud or hosting provider.&nbsp;</p>



<p>Azure Arc enables you to consistently manage SQL Server instances across hybrid and multicloud environments, bringing cloud innovations such as automated updates, unified policy, best practices assessment, and advanced security to SQL Server running anywhere.</p>



<p><strong>2. What’s the continuous migration assessment from Azure Arc?&nbsp;</strong>&nbsp;</p>



<p>Microsoft has <a href="https://techcommunity.microsoft.com/blog/microsoftdatamigration/general-availability-continuous-migration-assessment-for-sql-server-enabled-by-a/4430603" rel="noreferrer noopener" target="_blank">announced</a> the general availability of continuous migration assessments for SQL Server enabled by Azure Arc, marking a step forward in simplifying cloud migration planning. This release introduces a redesigned assessment experience that provides deeper insights and more intuitive navigation, especially for single Arc-enabled instances.&nbsp;</p>



<p>One of the standout features is the integration of retail pricing visibility across all Azure savings options, including Azure Hybrid Benefit (AHB), reserved instances, and Azure savings plans. These pricing insights are now available for Azure SQL Database, SQL Managed Instance, and SQL Server on Azure Virtual Machines (VMs), helping users make informed cost decisions. &nbsp;</p>



<p><strong>3. What is Azure Database Migration Service?&nbsp;</strong></p>



<p>Azure Database Migration Service is a fully managed service designed to seamlessly migrate databases to Azure with minimal downtime. It supports both homogeneous migrations (such as SQL Server to Azure SQL) and heterogeneous migrations (such as Oracle to Azure PostgreSQL).</p>



<p><strong>4. What are the migration methods in the new migration capability?&nbsp;</strong></p>



<p>The following methods are built into the migration process.&nbsp;<a href="https://review.learn.microsoft.com/en-us/azure/azure-sql/managed-instance/managed-instance-link-feature-overview?view=azuresql&amp;branch=main" rel="noreferrer noopener" target="_blank">Azure SQL Managed Instance link</a>&nbsp;enables near real-time database replication using distributed availability groups.&nbsp;<a href="https://review.learn.microsoft.com/en-us/azure/azure-sql/managed-instance/log-replay-service-overview?view=azuresql&amp;branch=main" rel="noreferrer noopener" target="_blank">Log Replay Service</a>&nbsp;uses SQL Server log-shipping technology and requires a brief planned cutover. Review&nbsp;<a href="https://review.learn.microsoft.com/en-us/azure/azure-sql/managed-instance/log-replay-service-compare-mi-link?view=azuresql&amp;branch=main" rel="noreferrer noopener" target="_blank">the Microsoft Learn page</a>&nbsp;to understand the differences between these two migration methods and choose the option that best suits your needs.</p>
<p>The post <a href="https://www.microsoft.com/en-us/sql-server/blog/2025/07/17/accelerate-sql-server-migration-to-azure-with-azure-arc/">Accelerate SQL Server Migration to Azure with Azure Arc </a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
