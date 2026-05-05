---
title: "How the Microsoft SQL team is investing in SQL tools and experiences"
url: "https://www.microsoft.com/en-us/sql-server/blog/2025/12/05/how-the-microsoft-sql-team-is-investing-in-sql-tools-and-experiences/"
date: "Fri, 05 Dec 2025 17:00:00 +0000"
author: "Anna Hoffman"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<p>I have the privilege, honor, and pleasure of being part of the SQL tools and experiences team at Microsoft, and this team is full of product leaders and engineers that care about you and your productivity. This team focuses on building the tools, SDKs, and experiences that matter most—so you can get the greatest value from <a href="https://aka.ms/sqlserver2025blog" rel="noreferrer noopener" target="_blank">Microsoft SQL Server</a>, <a href="https://azure.microsoft.com/en-us/products/azure-sql/?ef_id=_k_8408a63efd9a181215a9cf19ba079774_k_&amp;OCID=AIDcmm5edswduu_SEM__k_8408a63efd9a181215a9cf19ba079774_k_&amp;msclkid=8408a63efd9a181215a9cf19ba079774" rel="noreferrer noopener" target="_blank">Azure SQL</a>, <a href="https://learn.microsoft.com/en-us/fabric/database/sql/overview" rel="noreferrer noopener" target="_blank">SQL database in Fabric</a> and <a href="https://learn.microsoft.com/en-us/fabric/data-warehouse/data-warehousing" rel="noreferrer noopener" target="_blank">Fabric Data Warehouse</a>. You, the community, and the customers, are our top priority. We’d like to take a moment to explain where we are currently investing to meet your needs.</p>



<h2 class="wp-block-heading" id="enhancing-your-sql-workflow">Enhancing your SQL workflow</h2>



<p>From a tooling perspective, we are investing heavily in <a href="https://learn.microsoft.com/en-us/ssms/install/install" rel="noreferrer noopener" target="_blank">SQL Server Management Studio</a> (SSMS) and the MSSQL extension for Visual Studio Code. SSMS is where we primarily aim to serve data professionals like you including database administrators, data analysts, database developers, data scientists, and data engineers, and we have been doing so for two decades now. The MSSQL extension for Visual Studio Code is where we primarily aim to serve application developers. Additionally, from a web interface perspective, we are investing in the <a href="http://azure.microsoft.com" rel="noreferrer noopener" target="_blank">Microsoft Azure</a> portal and <a href="https://www.microsoft.com/en-us/microsoft-fabric" rel="noreferrer noopener" target="_blank">Microsoft Fabric</a> web experiences to support Azure and Fabric cross-functional roles and tasks to be done. </p>



<p>In the past year, we’ve <a href="https://learn.microsoft.com/en-us/ssms/release-notes-22-preview" rel="noreferrer noopener" target="_blank">modernized SSMS</a>—now based on the latest release of Visual Studio—and brought in numerous customer requests including dark mode, Arm64 support, Fabric support, GitHub Copilot, and more. We also brought rich, <a href="https://github.com/microsoft/vscode-mssql/wiki/roadmap" rel="noreferrer noopener" target="_blank">AI-assisted experiences to Visual Studio Code</a> with GitHub Copilot Ask and Agent mode support, in addition to many new and improved capabilities in areas around designing schemas and tables, provisioning and getting connected (including Fabric and local containers), query results, and more. In the web, we launched a <a href="https://aka.ms/azuresqlhub" rel="noreferrer noopener" target="_blank">unified Azure SQL experience</a> in the Azure portal, and shipped <a href="https://learn.microsoft.com/en-us/fabric/database/sql/overview" rel="noreferrer noopener" target="_blank">SQL database in Fabric</a>, now generally available.</p>



<h2 class="wp-block-heading" id="building-the-future-of-sql-development">Building the future of SQL development</h2>



<p>In addition to delivering quality releases and consistent functionality across these tools and experiences that enable you to efficiently manage and develop with Microsoft SQL Server, we are aiming higher for the future. Our vision is to equip every database with source control and CI/CD integration, streamline trusted and reliable deployments, provide consistent and tailored Copilot experiences, and deliver modern drivers, SDKs, and CLIs&nbsp;as well as a robust data API and MCP Server.&nbsp;We’re&nbsp;also investing in rich experiences that help developers take full advantage of AI capabilities in the SQL engine,&nbsp;making it easier to build and&nbsp;optimize&nbsp;AI-ready applications. </p>



<p>Delivering on that vision requires focus and critical prioritization, a responsibility that we’re taking with deep consideration and increased transparency to you. Full roadmap details across our tools and experiences can be found at the end of this article. If you were using <a href="https://aka.ms/ads-retirement" rel="noreferrer noopener" target="_blank">Azure Data Studio</a> or SDK-style SQL projects in Visual Studio 2022 and are impacted by the retirement of these tools, you can still use <a href="https://learn.microsoft.com/en-us/sql/tools/sql-database-projects/sql-projects-tools?view=sql-server-ver17#feature-set-comparison" rel="noreferrer noopener" target="_blank">the original SQL projects in Visual Studio 2026</a> so that your established solutions can upgrade to the latest Visual Studio version without compatibility conflicts. SDK-style (Microsoft.Build.Sql) projects are generally available in Visual Studio Code with the SQL Database Projects extension and are directly integrated with SQL database in Fabric source control. In the first half of 2026 SDK-style SQL projects will be added to <a href="https://developercommunity.visualstudio.com/t/Add-support-for-SQL-database-projects/10864596" rel="noreferrer noopener" target="_blank">SQL Server Management Studio</a>, empowering more database professionals with foundational tools for database DevOps.</p>



<h2 class="wp-block-heading" id="see-what-s-next-and-join-the-conversation">See what&#8217;s next and join the conversation</h2>



<p>We know that you will have feedback for us, now and as we go forward, and we want to thank you in advance for that, as it is critical that we understand what you need from your SQL tooling. This benefits you, us, and the entire community.</p>



<ul class="wp-block-list">
<li><a href="https://learn.microsoft.com/en-us/ssms/roadmap" rel="noreferrer noopener" target="_blank">SQL Server Management Studio roadmap</a></li>



<li><a href="https://aka.ms/ssms-feedback" rel="noreferrer noopener" target="_blank">SQL Server Management Studio feedback site</a></li>



<li><a href="https://aka.ms/vscode-mssql-roadmap" rel="noreferrer noopener" target="_blank">MSSQL extension for Visual Studio Code roadmap</a></li>



<li><a href="https://github.com/microsoft/vscode-mssql/issues" rel="noreferrer noopener" target="_blank">MSSQL extension for Visual Studio Code feedback</a></li>



<li><a href="https://github.com/microsoft/dacfx" rel="noreferrer noopener" target="_blank">SQL projects and DacFx feedback</a></li>



<li><a href="https://feedback.azure.com/d365community/forum/04fe6ee0-3b25-ec11-b6e6-000d3a4f0da0" rel="noreferrer noopener" target="_blank">Microsoft SQL feedback site</a></li>



<li><a href="https://roadmap.fabric.microsoft.com/?product=sqldatabase" rel="noreferrer noopener" target="_blank">SQL database in Fabric roadmap</a></li>



<li><a href="https://community.fabric.microsoft.com/t5/Fabric-Ideas/idb-p/fbc_ideas/label-name/databases%20%7C%20sql%20database" rel="noreferrer noopener" target="_blank">SQL database in Fabric Ideas site</a></li>
</ul>
<p>The post <a href="https://www.microsoft.com/en-us/sql-server/blog/2025/12/05/how-the-microsoft-sql-team-is-investing-in-sql-tools-and-experiences/">How the Microsoft SQL team is investing in SQL tools and experiences</a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
