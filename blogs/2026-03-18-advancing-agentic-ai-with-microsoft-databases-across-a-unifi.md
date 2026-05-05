---
title: "Advancing agentic AI with Microsoft databases across a unified data estate"
url: "https://www.microsoft.com/en-us/sql-server/blog/2026/03/18/advancing-agentic-ai-with-microsoft-databases-across-a-unified-data-estate/"
date: "Wed, 18 Mar 2026 12:45:00 +0000"
author: "Shireesh Thota"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<p>This week, we are excited to kick off <a href="https://sqlcon.us/">SQLCon 2026 alongside FabCon</a> in Atlanta. Bringing these SQL and <a href="https://www.microsoft.com/en-us/microsoft-fabric">Fabric</a> communities together creates a unique opportunity to learn, connect, and share what’s next across the Microsoft databases portfolio.</p>



<p>This year is especially meaningful, as it marks the return of a Microsoft‑led SQL community event, while also showcasing how SQL continues to evolve as a critical part of Fabric. It is not just about new technology, but about reconnecting with each other and building the future of SQL together.</p>



<p>It’s inspiring to see the Microsoft SQL community continue to grow and engage, with user groups worldwide keeping conversations active across the SQL portfolio and a lot of customers using Microsoft SQL to innovate every day. With a comprehensive portfolio built on strategic common foundations and available across edge, PaaS, and SaaS, Microsoft databases form a unified platform for modern enterprise needs, whether you are migrating and modernizing, building cloud-native AI applications, or unifying your data.</p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://sqlcon.us/" rel="noreferrer noopener" target="_blank">Learn more about what&#8217;s happening at SQLCon</a></div>
</div>



<h2 class="wp-block-heading" id="migrate-and-modernize-with-azure-sql">Migrate and modernize with Azure SQL</h2>



<p>Many of our customers are not modernizing in one big leap. You are evolving from SQL Server to hybrid and then to cloud services, and you want that journey to feel familiar, predictable, and low risk. That is exactly what Azure SQL is designed to deliver. Built on a consistent Microsoft SQL foundation from on premises to the cloud, Azure SQL brings AI capabilities directly into your database experience, along with enterprise‑grade security, high availability, and the flexibility to scale as your needs grow. Azure SQL is fully SQL compatible, delivers strong performance and low latency, and supports hybrid scenarios through Azure Arc.</p>



<p><a href="https://www.youtube.com/watch?v=uTv-E-vz570&amp;list=PLLasX02E8BPBCP7KdYsjKKFFQUmNEUmE9&amp;index=2">AI agents</a> are becoming an important accelerator for database migration and modernization at Microsoft, helping our customers reduce manual effort and move faster with more guided experiences across the journey. The <a href="https://aka.ms/ssms-2241-blog" rel="noreferrer noopener" target="_blank"><strong>general availability of GitHub Copilot in SSMS 22</strong></a> is a great example of that investment in action: you can use the same GitHub Copilot experience you already use in Visual Studio and VS Code, now inside <a href="https://learn.microsoft.com/en-us/ssms/sql-server-management-studio-ssms">SQL Server Management Studio</a> (SSMS), with chat and code assistance that helps you write, edit, and refactor T‑SQL more quickly and confidently. Whether you are a developer or database administrator (DBA), new to SQL or highly experienced, GitHub Copilot can support common workflows like improving queries and assisting with troubleshooting and administration tasks right where you work, and we are continuing to expand what it can do.</p>



<p>Today we are announcing <strong>savings plan for databases</strong>, a flexible, spend-based pricing option that helps you <a href="https://aka.ms/savings-plan-db" rel="noreferrer noopener" target="_blank">save up to 35%<sup>1</sup> vs. pay-as-you-go prices</a> on a one-year commitment. Savings plan for databases is designed for modern, evolving database environments: Customers commit to a fixed hourly spend for one year and receive lower prices across eligible Azure database services. Savings are automatically applied to the highest-value usage each hour, helping reduce costs while supporting migration, modernization, and architectural change.</p>



<h2 class="wp-block-heading" id="build-cloud-native-ai-apps-at-scale">Build cloud-native AI apps at scale</h2>



<p>Once you move to the cloud, the questions shift. How do you build faster, scale smarter, and unlock more value from your data without re‑architecting everything you have already built? That is where <a href="https://learn.microsoft.com/en-us/azure/azure-sql/database/service-tier-hyperscale?view=azuresql" rel="noreferrer noopener" target="_blank">Azure SQL Database Hyperscale</a> comes in.</p>



<p>With Azure SQL Database Hyperscale, customers gain better price-performance, elastic scale and resilience for any workload, without the cost or disruption of rewriting T‑SQL or reworking operational models. Its unique architecture, built on shared storage and multiple replicas, allows you to scale reads independently from writes. With built‑in HTAP isolation, applications can handle massive transactional and analytical workloads without complex redesign. New capabilities now in public preview extend that foundation even further, including the SQL MCP Server for securely connecting SQL data to AI agents and Copilots, as well as larger 160 and 192 vCore options for high‑throughput workloads. </p>



<p>We’re delivering faster, more capable vector indexes to power AI applications. Recent enhancements improve vector search performance and efficiency with no code changes required. With full insert, update, and delete support, vector indexes stay current in real time, enabling dynamic applications. Features like quantization, iterative filtering, and tighter query optimizer integration provide faster, more predictable results, helping teams build responsive AI experiences directly on their SQL data.</p>



<p><a href="https://aka.ms/SQLDB_Temenos" rel="noreferrer noopener" target="_blank">Temenos</a> built its next‑generation banking platform, Temenos Core, on Azure using Azure SQL Database Hyperscale to achieve global scale, high availability, and resilient performance. The platform processes billions of transactions daily and more than 17,500 transactions per second at peak. By building on Hyperscale, Temenos reduced onboarding time, accelerated innovation, and shifted banks from worrying about downtime to competing on availability and digital innovation. </p>



<h2 class="wp-block-heading" id="unify-your-data-estate-with-sql-database-in-fabric">Unify your data estate with SQL database in Fabric</h2>



<p>We continue to raise the bar on enterprise readiness for <strong><a href="https://aka.ms/Fabric-databases-FabCon-SQLCon26" rel="noreferrer noopener" target="_blank">SQL database in Fabric</a></strong> by bringing <strong>enterprise-grade security and compliance</strong> capabilities directly into the platform. Today at SQLCon, we announced the general availability of features including SQL Auditing, Customer‑Managed Keys, and Dynamic Data Masking, and the preview of workspace‑level Private Link. We brought these enhancements to help customers meet strict governance and regulatory requirements without adding operational complexity. The result is confidence that your SQL workloads in Fabric are secure, compliant, and ready for production.</p>



<p>SQL database in Fabric is becoming even more powerful for AI‑driven applications. The same vector indexing enhancements available in Azure SQL Database Hyperscale are now built into SQL database in Fabric as well. Because both are powered by the same Microsoft SQL engine, customers benefit from consistent performance, capabilities, and innovation across the SQL portfolio—making it easier to build intelligent applications wherever their data lives.</p>



<p>Finally, moving to SQL database in Fabric is simpler than ever. The <strong>Migration Assistant </strong>now supports SQL database in Fabric as a target destination. It provides a Copilot-assisted experience that helps SQL developers assess readiness, migrate schema, identify compatibility issues, and copy data with less manual effort. By preserving familiar SQL skills and workflows, customers can modernize at their own pace while accelerating time to value on Fabric’s unified analytics and AI platform.</p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://aka.ms/Fabric-databases-FabCon-SQLCon26" rel="noreferrer noopener" target="_blank"> Learn more about SQL database in Fabric</a></div>
</div>



<p>There is one more Fabric innovation that matters deeply for how we deliver Microsoft databases as a unified platform. As applications grow more sophisticated, most organizations now rely on a mix of SQL and NoSQL databases across cloud, on‑premises, and edge environments. Provisioning, monitoring, and maintaining health across a growing database fleet often requires multiple tools and portals, making it harder to see what’s happening and manage at scale. </p>



<p>To address this, we are introducing the <strong>Database Hub in Microsoft Fabric</strong>, now available in early access. The Database Hub provides a unified database management experience that brings together databases across edge, cloud, and Fabric into one coherent view. From a single place, database teams can explore, observe, govern, and optimize their entire estate, including Azure SQL, Azure Cosmos DB, Azure Database for PostgreSQL, SQL Server enabled by Azure Arc, and Azure Database for MySQL without changing how each service is deployed or operated. </p>



<p>Built for scale, the Database Hub introduces an agent-assisted, human-in-the-loop approach to database management. Intelligent agents continuously reason over estate-wide signals to surface what changed, explain why it matters, and guide teams toward what to do next, while built-in observability, delegated governance, and Copilot-powered insights help teams move from insight to action with greater confidence. With the Database Hub, teams spend less time navigating tools and more time enabling what comes next: unlocking deeper integration across applications, analytics, and AI from a single control plane for the Microsoft databases portfolio.</p>



<p>Database Hub is available today in early access. <a href="https://aka.ms/database-hub" rel="noreferrer noopener" target="_blank">Sign up</a> today and see how the Database Hub can bring clarity and control to your database estate.</p>



<h2 class="wp-block-heading" id="moving-forward-with-the-sql-community">Moving forward with the SQL community</h2>



<p>SQLCon is about bringing the SQL community together. It is about rebuilding connections and shared learning. It also reflects our long-term commitment to SQL. With a comprehensive portfolio built on strategic common foundations and available across edge, PaaS, and SaaS, Microsoft databases provide a unified platform for modern enterprise needs, whether you are migrating and modernizing, building cloud-native AI applications, or unifying your data. We are investing in SQL for the future, alongside the community that continues to shape it.</p>



<p>Finally, SQLCon is coming to Europe! Join the global data and SQL community from 28 Sep – 01st October, 2026 in Barcelona, Spain for hands-on learning, expert insights, and real-world stories. <a href="https://www.sharepointeurope.com/european-microsoft-fabric-community-conference-tickets/" rel="noreferrer noopener" target="_blank">Register to be a part of it</a>. I can’t wait to see you there.</p>



<h2 class="wp-block-heading" id="additional-sql-resources">Additional SQL resources</h2>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://aka.ms/database-hub" rel="noreferrer noopener" target="_blank">Get early access to Database Hub in Fabric</a></div>
</div>



<ul class="wp-block-list">
<li><a href="https://aka.ms/database-hub" rel="noreferrer noopener" target="_blank">Microsoft Azure Summit: Migrate and Modernize with Agentic AI</a></li>



<li><a href="https://aka.ms/Fabric-databases-FabCon-SQLCon26" rel="noreferrer noopener" target="_blank">What is new about SQL database in Fabric</a></li>



<li><a href="https://aka.ms/savings-plan-db" rel="noreferrer noopener" target="_blank">Learn more about savings plan for databases</a></li>
</ul>



<hr class="wp-block-separator has-alpha-channel-opacity" />



<p><sup>1</sup>Customers may see savings estimated to be between 0% and 35%. The 35% savings estimate is based on one Azure SQL Database serverless running for 12 months at a pay-as-you-go rate vs. a reduced rate for a 1-year savings plan. Based on Azure pricing as of March 2026. Prices are subject to change. Actual savings may vary based on location, database service, and/or usage. </p>
<p>The post <a href="https://www.microsoft.com/en-us/sql-server/blog/2026/03/18/advancing-agentic-ai-with-microsoft-databases-across-a-unified-data-estate/">Advancing agentic AI with Microsoft databases across a unified data estate</a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
