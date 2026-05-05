---
title: "Accelerating SQL Server 2025 momentum: Announcing the first release candidate"
url: "https://www.microsoft.com/en-us/sql-server/blog/2025/08/22/accelerating-sql-server-2025-momentum-announcing-the-first-release-candidate/"
date: "Fri, 22 Aug 2025 15:00:00 +0000"
author: "Priya Sathy"
feed_url: "https://www.microsoft.com/en-us/sql-server/blog/feed/"
---
<p>The first release candidate (RC0) of SQL Server 2025 is <a href="https://aka.ms/getsqlserver2025">now available</a>. As we move toward general availability, our focus shifts to delivering enhanced stability, performance, and product improvements based on your feedback.  </p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-16018d1d wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link wp-element-button" href="https://aka.ms/getsqlserver2025">Download the first release candidate of SQL Server 2025</a></div>
</div>



<h2 class="wp-block-heading" id="adoption-gains-speed">Adoption gains speed&nbsp;</h2>



<p>We’re seeing incredible momentum with SQL Server 2025 since its public preview debut at Microsoft Build. From lighting up community events like SQL Saturdays to being featured at SQLBits 2025 with CTP 2.1, the excitement is electric. SQL Server 2025 isn’t just keeping pace, it’s setting a new standard. Customers are adopting SQL Server 2025 twice as fast as SQL Server 2022 based on downloads of the public preview.</p>


<div class="wp-block-msxcm-kicker-container">
	<div class=" wp-block-msxcm-kicker-block wp-block-msxcm-kicker--align-right">
		<p class="wp-block-msxcm-kicker__title small text-neutral-400 text-uppercase">
			announcing sql server 2025		</p>
		<a class="wp-block-msxcm-kicker__cta btn btn-link p-0 text-decoration-none" href="https://www.microsoft.com/en-us/sql-server/blog/2025/05/19/announcing-sql-server-2025-preview-the-ai-ready-enterprise-database-from-ground-to-cloud/" target="_blank">
			<span>Read the blog</span> <span class="glyph-append glyph-append-xsmall wp-block-msxcm-kicker__glyph glyph-append-chevron-right"></span>
		</a>
	</div>
</div>



<p>In the early adoption program, participants were asked to rank the SQL Server 2025 features they were most interested in testing. Built-in AI emerged as one of the top priorities, alongside performance and scalability enhancements. In addition, based on feedback from our preview customers, developer-friendly enhancements—especially the introduction of native JSON support—along with powerful T-SQL additions like regular expression support, have also been positively received—streamlining data processing and boosting developer efficiency. Enterprise customers like Entain, Mediterranean Shipping Company, Kramer &amp; Crew, Schultz, and Bühler are already hands-on, exploring how SQL Server 2025 can power their next-gen applications.&nbsp;</p>



<blockquote class="wp-block-quote blockquote is-layout-flow wp-block-quote blockquote-is-layout-flow">
<p><em>&#8220;As one of the largest SQL Server consulting firms in Brazil, we are excited about the AI features in SQL Server 2025, especially the potential for text processing that can benefit companies of all sizes. AI brings new ways to process and extract insights from data and with SQL Server being the core repository for many businesses, native AI features like embeddings, REST API support, and vector indexes are game changers. They eliminate the need for external vector databases, making AI integration more seamless and efficient.” </em></p>
<cite>Rodrigo Ribeiro Gomes, Head of Innovation, Power Tuning</cite></blockquote>



<blockquote class="wp-block-quote blockquote is-layout-flow wp-block-quote blockquote-is-layout-flow">
<p><em>“SQL Server 2025 introduces seamless Azure and Arc integration and features, enhanced JSON and RegEx capabilities, and enhancements to database engine.”&nbsp;</em>&nbsp;</p>
<cite><em>Shailesh Panday, Deputy Manager, IT, Buhler AG</em></cite></blockquote>



<h2 class="wp-block-heading" id="explore-capabilities-with-new-preview-features">Explore capabilities with new preview features</h2>



<p>SQL Server 2025 introduces a new <strong>preview feature option</strong>, giving customers the flexibility to balance production stability with early access to innovation. When turned on, it unlocks access to upcoming features still in preview, enabling developers to test and evaluate new capabilities like vector indexing, improved text chunking, and change event streaming without impacting production workloads (a complete list of <a href="https://learn.microsoft.com/sql/sql-server/what-s-new-in-sql-server-2025" rel="noreferrer noopener" target="_blank">preview features is here</a>). &nbsp;</p>



<p>This opt-in model brings the agility of the cloud to on-premises SQL Server, empowering customers to innovate on their terms. Preview features are provided in alignment with Microsoft&#8217;s supportability guidelines. They are intended for evaluation and testing purposes only and are not recommended for use in production environments. The database itself in SQL Server 2025 remains as fully supported and is an essential component of the general availability release. Preview features are optional and designed to operate independently in preview mode. Enabling these features does not impact the stability or supportability of your database.  </p>



<p>SQL Server has traditionally used trace flags to enable or disable specific behaviors within the database engine. The new preview feature switch in SQL Server 2025 is fundamentally different from traditional trace flags. While trace flags are primarily used for debugging and diagnostics, often by DBAs or support engineers to control internal engine behavior, the preview feature switch is designed for developers to explore and test new, user-facing capabilities. Trace flags typically operate at the instance level, affecting the entire server, whereas the preview feature switch is a database-scoped configuration, offering more granular control and safer experimentation without impacting other workloads. Learn more about the preview features in the <a href="https://learn.microsoft.com/en-us/sql/sql-server/preview-features-faq?view=sql-server-ver17" rel="noreferrer noopener" target="_blank">frequently asked questions</a>.</p>



<h2 class="wp-block-heading" id="new-feature-highlights">New feature highlights</h2>



<p>As SQL Server adoption on Linux continues to grow, we’re excited to introduce preview support for <strong>Ubuntu 24.04</strong>, one of the most widely used and trusted Linux distributions. This marks a significant step forward in our commitment to cross-platform flexibility and developer choice. By embracing the latest Ubuntu release, SQL Server 2025 ensures developers and IT teams can build and run modern, cloud-connected applications on a familiar and up-to-date Linux environment.&nbsp;</p>



<p><strong>PolyBase</strong> plays a critical role in enabling analytics scenarios by allowing SQL Server to query external data sources like <a href="https://azure.microsoft.com/en-us/solutions/data-lake" rel="noreferrer noopener" target="_blank">Microsoft Azure Data Lake</a> or <a href="https://azure.microsoft.com/en-us/products/storage/blobs" rel="noreferrer noopener" target="_blank">Azure Blob Storage</a> using familiar T-SQL. As many of SQL Server’s modern analytics capabilities are deeply integrated with <a href="http://azure.microsoft.com" rel="noreferrer noopener" target="_blank">Microsoft Azure services</a>, secure and seamless access to cloud storage is essential. With preview support for <strong>Managed Identity</strong> authentication to Azure Storage, SQL Server 2025 takes a step forward in simplifying security and access management. This enhancement aligns with SQL Server’s decade-long track record as the most secure database and reinforces our commitment to enterprise-grade security. By eliminating the need for storing secrets or keys, Managed Identity makes it easier and safer for customers to build scalable, cloud-connected analytics solutions using PolyBase. </p>



<p>Mirroring in <a href="https://www.microsoft.com/en-us/microsoft-fabric" rel="noreferrer noopener" target="_blank">Microsoft Fabric</a> is a game-changing capability that unlocks seamless, near real-time analytics on operational data from SQL Server 2025. To help customers manage compute resources efficiently during the mirroring process, SQL Server now supports creating a dedicated <strong>Resource Governor (RG)</strong> pool. Each phase of mirroring—such as ingestion, transformation, and synchronization—can be assigned to a specific workload group, giving administrators fine-grained control over resource allocation. These workload groups can be placed in the same or different pools depending on capacity planning needs.&nbsp;&nbsp;</p>



<h2 class="wp-block-heading" id="discover-more">Discover more&nbsp;</h2>


<div class="wp-block-msxcm-cta-block">
	<div class="card d-block mx-ng mx-md-0">
		<div class="row no-gutters material-color-brand-dark">

							<div class="col-md-4">
					<img alt="A man sitting at a desk using a computer" class="card-img img-object-cover" height="467" src="https://www.microsoft.com/en-us/sql-server/blog/wp-content/uploads/2025/06/Untitled-1024x467.webp" width="1024" />				</div>
			
			<div class="d-flex col-md">
				<div class="card-body align-self-center p-4 p-md-5">
					
					<h2>SQL Server 2025</h2>

					<div class="mb-3">
						<p>An AI-ready enterprise database with best-in-class security, performance, and availability.</p>
					</div>

											<div class="link-group">
							<a class="btn btn-link text-decoration-none p-0" href="https://aka.ms/getsqlserver2025" target="_blank">
								<span>Download RC0 today</span>
								<span class="glyph-append glyph-append-chevron-right glyph-append-xsmall"></span>
							</a>
						</div>
									</div>
			</div>

					</div>
	</div>
</div>



<ul class="wp-block-list">
<li>Download <a href="http://aka.ms/getsqlserver2025">release candidate (RC0)</a>.&nbsp;</li>



<li>Learn more on <a href="https://learn.microsoft.com/sql/sql-server/what-s-new-in-sql-server-2025" rel="noreferrer noopener" target="_blank">Microsoft Learn</a>.</li>



<li>Discover what&#8217;s new in SQL Server 2025 in our latest <a href="https://youtu.be/PvA3Ah3JJxg?si=z6Z9RGkwuopfvf0c" rel="noreferrer noopener" target="_blank">Mechanics video</a>.</li>
</ul>
<p>The post <a href="https://www.microsoft.com/en-us/sql-server/blog/2025/08/22/accelerating-sql-server-2025-momentum-announcing-the-first-release-candidate/">Accelerating SQL Server 2025 momentum: Announcing the first release candidate</a> appeared first on <a href="https://www.microsoft.com/en-us/sql-server/blog">Microsoft SQL Server Blog</a>.</p>
