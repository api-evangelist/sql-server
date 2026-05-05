---
title: "FabCon and SQLCon 2026: Unifying databases and Fabric on a single data platform"
url: "https://azure.microsoft.com/en-us/blog/fabcon-and-sqlcon-2026-unifying-databases-and-fabric-on-a-single-data-platform/"
date: "Wed, 18 Mar 2026 12:45:00 +0000"
author: "Arun Ulag"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<p>Welcome to the third annual FabCon and our first ever SQLCon here in Atlanta, Georgia. With nearly 300 workshops and sessions, this joint event will highlight how they are bringing the power of Microsoft SQL and Microsoft Fabric together to create a single, unified platform. But FabCon 2026 and SQLCon 2026 are about more than product innovation. It’s about providing space for our 8,000 attendees to come together and share real experiences, learn from each other, and solve challenges side-by-side. Only together can we move beyond the hype and into meaningful results.</p>



<p>Learn more about FabCon and SQLCon 2026<br />The excitement surrounding this event reflects the same momentum we’re seeing across our data portfolio. Just two and a half years after Microsoft Fabric reached general availability, it’s already serving more than 31,000 customers and remains the fastest-growing data platform in Microsoft’s history. Fortune 500 companies like The Coca-Cola Company are already using Fabric at scale across their organizations.</p>



<p>Microsoft Fabric is helping us evolve our data foundation into a more unified, AI-ready platform. Combined with Power BI and capabilities like Fabric IQ, it enables the enterprise to turn data into intelligence and act on it faster.</p>



<p>Shekhar Gowda, Vice President of Global Marketing Technologies at The Coca-Cola Company<br />Our databases are accelerating just as quickly, with SQL Server 2025 growing more than twice as fast as the previous version.</p>



<p>Today, we’re thrilled to share how we are bringing the power of databases and Fabric together to form a truly converged data platform—one that unifies transactional, operational, and analytical data under a single, consistent architecture. I’ll also highlight how we’ve enhanced Fabric to help you transform data into the semantic knowledge AI needs to understand your business, powered by Fabric IQ and Power BI’s industry-leading semantic model technology.</p>



<p>Introducing the Database Hub in Microsoft Fabric<br />Databases sit at the heart of the enterprise data estate—a system of record powering applications, transactions, and mission‑critical insights. Yet as organizations scale across cloud, on‑premises, and edge environments, database estates have become increasingly fragmented and isolated. As AI places even greater demands on data estates, unifying databases under a single access point and control plane has become essential.</p>



<p>To address this challenge, Fabric is expanding its role as the central access point for enterprise data with the Database Hub in Fabric, now available in early access. Database Hub in Fabric provides a unified database management experience that brings together databases across edge, cloud, and Fabric into a single, coherent view. Teams now have one place to explore, observe, govern, and optimize their entire database estate—including Azure SQL, Azure Cosmos DB, Azure Database for PostgreSQL, SQL Server (enabled by Azure Arc), Azure Database for MySQL, and Fabric Databases—without changing how each service is deployed.</p>



<p>Built for scale, the Database Hub in Fabric introduces an agent‑assisted, human-in-the loop approach to database management. With built-in observability, delegated governance, and Microsoft Copilot-powered insights, teams can deploy intelligent agents to continuously reason over estate‑wide signals and surface what changed, explain why it matters, and guide teams toward what to do next. The result is a simpler, more confident way to manage databases at scale. Over time, this model enables database estates to become more proactive, resilient, and intelligent, laying the foundation for greater autonomy, while keeping humans firmly in control of goals, boundaries, and trust.</p>



<p>Learn more about Database Hub in Fabric and what’s new across Databases<br />Bringing databases together under a single management layer is a critical step as you prepare your estates for AI at scale. But it’s not the end of the journey. The challenge shifts from where data lives to how data is understood, connected, and activated across the enterprise.</p>



<p>Getting your data estate ready for AI with Fabric<br />As organizations move from traditional applications to AI‑powered, multi‑agent systems, the advantage is shifting away from the specific model you deploy. It now lies in the intelligence and context that allow agents to understand how your business is run, the state of your business, and your institutional knowledge to help take meaningful action.</p>



<p>This is the challenge Microsoft IQ is designed to address. Unlike point solutions on the market today, Microsoft IQ provides an intelligence layer that delivers shared, enterprise-grade business context to every agent. That context is built from three complementary sources: productivity signals from Work IQ, institutional knowledge from Foundry IQ, and live business data from Fabric IQ.</p>



<p>However, like the database layer, while the IQ context layer is a critical part of a successful, and healthy AI foundation, it is not the full story. Building a complete AI-ready data foundation requires investing in four core steps:</p>



<p>Unifying your data estate to eliminate silos and reduce architectural complexity.<br />Processing and harmonizing data so it becomes AI-ready, clean, connected, and structured for both operational and analytical use.<br />Curating semantic meaning to give agents contextual understanding, enabling them to interpret data the way your teams already do. This is where Microsoft IQ comes into play.<br />Empowering AI agents to act, applying that context to automate workflows, accelerate decisions, and transform operations end‑to‑end.<br />Unifying your data estate with Microsoft OneLake<br />Every AI initiative starts with the same fundamental challenge: understanding where your data lives and how to bring it together. Microsoft OneLake was built to solve that problem by unifying data across clouds, on-premises environments, and third-party platforms into a single logical data lake without unnecessary extracting, transforming, and loading (ETL), fragmentation, or duplicated copies.</p>



<p>Are my agents hunting for data?</p>



<p>Watch the podcast<br />Connecting to more sources than ever before<br />Today, we’re expanding Mirroring in Fabric to support even more systems our customers rely on. Mirroring for SharePoint lists and Dremio are now in preview with Azure Monitor coming soon, while mirroring for Oracle and SAP Datasphere are generally available—all of which are available as part of the core mirroring capabilities. We are also introducing extended capabilities in mirroring designed to help you operationalize mirrored sources at scale, including Change Data Feed (CDF) and the ability to create views on top of mirrored data, starting with Snowflake. Extended capabilities for mirroring will be offered as a paid option.</p>



<p>Shortcut transformations are also now generally available, allowing data to be shaped automatically as it connects to or moves within OneLake. You can convert formats such as Excel to Delta tables, now in preview, and apply AI-powered transformations.</p>



<p>Additionally, we are continuing to invest in open interoperability, ensuring OneLake works seamlessly with the platforms organizations already use. We are excited to announce the ability to natively read from OneLake through Azure Databricks Unity Catalog is now in public preview. We also recently announced the general availability of our interoperability with Snowflake.</p>



<p>I’m also excited to share that Auger, a rapidly growing supply chain platform designed to bring intelligence and automation to global operations, has built its platform on Fabric, with all data stored natively in OneLake. This architecture enables Auger customers to seamlessly access their operations data through OneLake shortcuts within their own Fabric environments and use the full power of the platform including Power BI, Fabric data agents, and more. Learn more in my blog, co-authored with Auger Chief Executive Officer Dave Clark.</p>



<p>Protect your data with OneLake security, now generally available<br />Security and governance remain foundational to OneLake. I’m thrilled to announce OneLake security will be generally available in the coming weeks, enabling data owners to define roles, enforce row- and column-level controls, and manage permissions through a single unified model that follows the data.</p>



<p>To learn more about these announcements, read the OneLake blog and the Fabric Data Factory blog.</p>



<p>Processing and harmonizing data with Fabric analytics<br />AI agents are only as reliable as the data you feed them. Before data can train or ground an agent, it must be integrated, cleaned, and structured, so the agent operates from consistent, trusted information. With industry-leading engines in Fabric like Spark, T-SQL, KQL, and Analysis Services, we can equip data teams to do exactly that.</p>



<p>Now, we are expanding these capabilities with the introduction of Runtime 2.0 in preview, purpose-built for large-scale data computation. It incorporates Apache Spark 4.x, Delta Lake 4.x, Scala 2.13, and Azure Linux Mariner 3.0 to power advanced enterprise workloads. Materialized lake views are also now generally available, simplifying medallion architecture implementation in Spark SQL and PySpark and enabling always up-to-date pipelines with no manual orchestration. In addition, a new agentic Copilot experience in notebooks delivers deeper context awareness, reasoning over your workspace, and generating code with greater speed and precision.</p>



<p>For real-time scenarios, we’re launching Microsoft Fabric Maps into general availability. Maps add geospatial context to your agents and operations by turning large volumes of location-based data into interactive, real-time visual insights.</p>



<p>For a comprehensive overview of these announcements and much more, read the Fabric Analytics announcement blog and the Fabric Real-Time Intelligence announcement blog.</p>



<p>Creating semantic meaning with Fabric IQ<br />Preparing raw data for AI is essential. The next step is transforming that data into meaningful, unified business context. That is where Fabric IQ comes in.</p>



<p>Fabric IQ unifies analytical data and operational data, including telemetry, time series, graph, and geospatial data, within a shared semantic framework of business entities, relationships, properties, rules, and actions. Instead of thinking in terms of tables and schemas, your teams and agents can operate on this framework, or ontology, aligned to how the business actually runs.</p>



<p>Fabric IQ ontologies will soon become accessible through an MCP server in preview, enabling agents to discover, understand, and act on this semantic layer. Ontologies can also serve as context sources for maps and soon in operations agents in Fabric, extending shared business context directly into operational decision-making and execution.</p>



<p>We are also excited to announce planning in Fabric IQ, a new enterprise planning capability that enables organizations to create plans, budgets, forecasts, and scenario models directly on top of Fabric’s semantic models. By complementing Fabric IQ’s ontologies with integrated planning, you get a complete, contextual view of your historical, real-time, and forward planning data. This allows users and agents to quickly answer what has happened, what is happening, and what should happen all from a single source. See this in action:</p>



<p>Finally, we recently announced a strategic partnership with NVIDIA to power the next generation of Physical AI by integrating Real-Time Intelligence and Fabric IQ with NVIDIA Omniverse libraries. The combined platform unifies real‑time operational data, business semantics, and physical simulation to enable organizations to optimize their physical operations in scenarios like intelligent digital twins, predictive maintenance, autonomous logistics, and energy optimization.</p>



<p>To learn more about all of our partner announcements, read the Fabric ISV announcement blog and the planning in Fabric IQ blog.</p>



<p>Enhancing the underlying Fabric IQ technology<br />Powering much of Fabric IQ’s rich experience is a combination of Power BI’s industry-leading, rich semantic model technology and graph in Fabric, our highly scalable graph database. Already delivering insights to more than 35 million active users, semantic models provide the ideal foundation for training agents through Fabric IQ. Now, with the general availability of Direct Lake on OneLake, your tables can be read directly from OneLake with native security enforcement, richer cross-item modeling, and import-class performance without data movement or refresh.</p>



<p>I’m also excited to share that graph in Fabric will be generally available in the coming weeks, enabling teams to visualize and query complex relationships across customers, partners, and supply chains.</p>



<p>To learn more, check out the Fabric IQ announcement blog and the Power BI announcement blog.</p>



<p>Empowering agents to act with Fabric data and operations agents<br />Frontier organizations are moving beyond general-purpose assistants and instead, adopting multi-agent systems composed of specialized agents. These agents are each grounded on specific data and reusable across different systems, allowing you to deliver more accurate, accelerated, and scalable outcomes.</p>



<p>To support your multi-agent systems, Fabric comes with built-in agent creation capabilities with Fabric data agents and operations agents. I’m excited to share that Fabric data agents are now generally available. Fabric data agents can be thought of as virtual analysts, aligned to specific domain data to support deeper analysis and deliver insights. Operations agents complement them by monitoring real-time data, detecting patterns, and taking proactive action.</p>



<p>Check out a quick demo of operations agents in Fabric:</p>



<p>These agents can be used across Fabric or as foundational knowledge sources in leading AI tools like Microsoft Foundry, Copilot Studio or even Microsoft 365 Copilot. To learn more about our AI announcements, check out the Fabric analytics blog covering data agents and the Fabric IQ blog covering operations agents.</p>



<p>Building mission-critical applications with developer experiences in Fabric<br />Developers building the next generation of AI applications need a comprehensive, cost-effective data platform that’s already integrated with your existing tools and workflows. Today, we are expanding Fabric’s developer tooling to meet that demand.</p>



<p>First, Fabric Model Context Protocol (MCP) is advancing with two major milestones. Fabric local MCP is now generally available, providing an open-source local server that connects AI coding assistants such as GitHub Copilot directly to Fabric. Alongside this, we’re introducing the public preview of Fabric remote MCP, a secure, cloud‑hosted execution engine that enables AI agents and automation tools to perform authenticated actions in Fabric.</p>



<p>We’re also enhancing our Git integration with selective branching, allowing developers to branch out for a specific feature and pull only the items they need. You also get improved change comparisons to more easily review recent updates, and new folder relationships which show how feature workspaces connect to source workspaces.</p>



<p>We’re also launching two open-source projects to help teams move faster with Fabric: Agent Skills for Fabric and Fabric Jumpstart. Agent Skills for Fabric is an open-source set of purpose-built plugins that let you use natural language in the GitHub Copilot terminal to harness the full power of Microsoft Fabric. Additionally, Fabric Jumpstart is designed to help you get off the ground with detailed guidance, reference architectures, and single‑click deployments for sample datasets, notebooks, pipelines, and reports.</p>



<p>Finally, we are announcing that the Fabric Extensibility Toolkit (FET), an evolution of the Workload Development Kit (WDK), is now generally available. Along with this release, we are enabling support for full CI/CD, variable library, and a new management experience in the Admin portal.</p>



<p>Read the Fabric Platform announcement blog<br />Migrating your existing Azure service to Fabric<br />As Fabric continues to grow in functionality, we are also simplifying the migration from other Azure services. In addition to our existing Synapse tooling, we are bringing new migration assistants for Azure Data Factory, Azure Synapse Analytics, and Azure SQL in public preview.</p>



<p>The new Fabric migration assistant for Azure Data Factory and Synapse Analytics helps move your existing pipelines and artifacts like Spark pools and notebooks into Fabric with minimal disruption. It’s designed to support incremental modernization, allowing teams to evaluate, convert, and optimize pipelines as they transition to Fabric. The migration assistant for SQL databases helps move SQL Server into Fabric by importing schemas through DACPACs, identifying and resolving compatibility issues with AI assistance, and guiding teams through assessment and data copy workflows for a smoother cutover.</p>



<p>See more Fabric innovation<br />Explore the AI shift with The Shift podcast<br />In addition to the announcements above, we are also rolling out a broad set of Fabric innovations across the platform. For a deeper look at the updates and what’s new this month, visit the Fabric March 2026 Feature summary blog, the Power BI March 2026 feature summary blog, and the latest posts on the Fabric Updates channel.</p>



<p>Explore additional resources for Microsoft Fabric<br />Sign up for the Fabric free trial. View the updated Fabric Roadmap. Try the Microsoft Fabric SKU Estimator.<br />Visit the Fabric website. Join the Fabric community. Read other in-depth, technical blogs on the Microsoft Fabric Updates Blog.<br />Read additional blogs by industry-leading partners<br />Sonata Software: Building an AI-ready data platform with data agents, ontology, and governance in Microsoft Fabric<br />Quadrant Technologies LLC: Real-Time Operational Intelligence in Microsoft Fabric: Deep Dive into RTI Capabilities, Anomaly Detection and Activator Alerting<br />Inspark: Why switch from Azure Synapse to Microsoft Fabric?<br />Esri: Unlock the power of location intelligence with ArcGIS for Microsoft Fabric<br />Dream IT Consulting Services: 8 Real-World Use Cases of Data Agents in Microsoft Fabric<br />UB Technology Innovations Inc.: From Data Platform to Decision Platform: How Microsoft Fabric and Copilot are Redefining Enterprise Analytics<br />Simpson Associates: Fabric Data Warehouse: Bringing Structure to Modern Data Strategies<br />Synapx Ltd.: Migrating Power BI to Microsoft Fabric Lakehouse with Medallion Architecture: A Strategic Imperative for Modern Construction Enterprises<br />Cloud Services: Real-Time Intelligence in Action: How Microsoft Fabric Helped Delfi Transform Its Newsroom<br />Cloud Services: Microsoft Fabric Data Agents: A New Reality<br />iLink Digital: Detect to Act in Seconds: How Real-Time Intelligence Is Rewriting the Rules of Emissions Management<br />Valorem Reply: How Nonprofits Are Rethinking Data with Microsoft Fabric</p>
<p>The post <a href="https://azure.microsoft.com/en-us/blog/fabcon-and-sqlcon-2026-unifying-databases-and-fabric-on-a-single-data-platform/">FabCon and SQLCon 2026: Unifying databases and Fabric on a single data platform</a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
