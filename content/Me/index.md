---
title : "ABOUT ME"
description: "This is a demo of adding content to the homepage."
showAuthorBottom: true
showTableOfContents: true
showComments: true
showSummary: true
---

<style>
  details summary .show-less { display: none; }
  details[open] summary .show-less { display: inline; }
  details[open] summary .read-more { display: none; }
</style>

# Soon Kien Yuan

I’m a platform engineer who builds and runs data systems.
Redstonetics is my lab — where I turn ideas into working infrastructure.

This timeline shows how I got here.
{{< timeline >}}

{{< timelineItem icon="graduation-cap" header="How I got into building systems" badge="Early years" subheader="FinalYearProject" >}}
<p>I started with my bachelor Degree’s industry-collaboration data science project: <strong>"Self-Service Analytics data lakehouse"</strong> using <strong>Dremio</strong> as the data platform.</p>

<p>The project itself was far from perfect — my work and paper were rough and not very production-ready — but it showed me something important:</p>

<ul>
  <li>Real data systems are not just about design and technology</li>
  <li>They depend on platforms, infrastructure, and how people actually use them</li>
</ul>

<p>That experience sparked my curiosity and led me toward:</p>

<ul>
  <li>Infrastructure</li>
  <li>Automation</li>
  <li>Cloud-based data platforms and architecture</li>
</ul>

That opportunity grew my curiostiy and grew into a focus on infrastructure, automation, and eventually data platforms and cloud architecture   
{{< /timelineItem >}}


<!-- -------------------------------------------------------------------------------------- 
-->

{{< timelineItem icon="lightbulb" header="First production systems" badge="2023" subheader="From scripts to platforms" >}}



<p>My first real-world project was building a <strong>Network Data Platform for a telecommunications company’s Network Analytics & Intelligence team</strong>.</p>

<p>I worked with enterprise-scale Azure environments, including:</p>

<ul>
  <li>Microsoft Cloud Adoption Framework</li>
  <li>Connectivity, Management, and Application Landing Zone </li>
</ul>

<p>I learned & built an end-to-end ML platform (Azure ML) that enabled data scientists to:</p>

<ul>
  <li>Transition models from pickle files to MLflow </li>
  <li>Enabled experiment tracking and metadata logging for reproducibility</li>
  <li>centralized Model Registry for versioning and governance</li>
  <li>Track metadata and experiment logs</li>
  <li>Development and serving environments so data scientists could train and deploy models on cost-efficient compute/endpoint </li>
  
<details>
<summary>
  <strong>
    <span class="read-more">Read more</span>
  </strong>
</summary>
<p>I also learned and built a serverless lakehouse to support SQL-based analytics on the data lake:</p>
<ul>
  <li>Enabled downstream analytics and applications</li>
  <li>Supported a modern lakehouse-style data architecture</li>
</ul>

<p>To ensure enterprise-grade reliability and security, I Learnt and implemented:</p>
<ul>
  <li>Azure Defender for Cloud across VM and Azure Env</li>
  <li>Centralized secrets and key management</li>
  <li>Centralized Log collection & Analytics and forwarding to the customer’s SIEM Env</li>
  <li>SAST and security scanning for all Terraform code for compliance assurance</li>
</ul>

<p>This is where infrastructure, data engineering, and architecture come together into systems teams can actually use.</p>
<div class="text-right cursor-pointer text-sm font-bold opacity-70 hover:opacity-100 mt-2" onclick="this.parentElement.removeAttribute('open')">
  ↑ Show less
</div>
</details>
{{< /timelineItem >}}


<!-- -------------------------------------------------------------------------------------- 
-->

{{< timelineItem icon="cloud" header="Cloud Engineering & Data Platform" badge="Present" subheader="Platforms, Data, and DevOps" >}}


<blockquote class="border-l-4 border-primary-500 pl-4 italic my-4">
  I currently design, build, and operate data platforms on Azure
</blockquote>

<p>My work spans the <strong>full platform lifecycle:</strong></p>
<ul>
  <li>Designing Azure Cloud architecure, Landing Zone (networking, identity, isolation, security)</li>
  <li>Building data platforms from ingestion to analytics</li>
  <li>Automating everything with Terraform, CI/CD, and policy-driven governance</li>
  <li>Designing data flows and medallion architectures (raw → curated → consumer → Dashboard or Database)</li>
</ul>

<p>I design storage and network boundaries intentionally:</p>

<ul>
  <li>Landing storage accounts live in subnets exposed to data sources (internet or on-prem)</li>
  <li>Raw, structured, curated, and consumer zones live in private subnets, isolated from direct external access</li>
  <li>Data moves inward through controlled pipelines, not open endpoints</li>
</ul>


<details>
<summary>
  <strong>
    <span class="read-more">Read more</span>
  </strong>
</summary>
<p>When data engineers are not available, I also work at the data-ingestion and pipeline layer:</p>

<ul>
  <li>Writing Python scripts to pull data from APIs and sources</li>
  <li>Orchestrating and scheduling pipelines using Azure Data Factory</li>
</ul>

<p>On a typical platform I work across:</p>

<ul>
  <li>Networking & isolation (hub-spoke, private endpoints, segmented subnets)</li>
  <li>Compute & PaaS (VMs, managed services, Kubernetes when appropriate)</li>
  <li>Data flows (ingestion → raw → curated → consumer)</li>
  <li>Security & governance (IAM, secrets, logging, compliance, cost controls)</li>
</ul>

<p>I focus on building platforms that are:</p>

<ul>
  <li>Operable (easy to run, monitor, and troubleshoot)</li>
  <li>Cost-aware</li>
  <li>Safe to change</li>
</ul>

<p>This is where infrastructure, data engineering, and architecture come together into systems teams can actually use.</p>
<div class="text-right cursor-pointer text-sm font-bold opacity-70 hover:opacity-100 mt-2" onclick="this.parentElement.removeAttribute('open')">
  ↑ Show less
</div>
</details>
{{< /timelineItem >}}

<!-- -------------------------------------------------------------------------------------- 
-->


{{< timelineItem icon="code" header="Redstonetics — my lab" badge="Ongoing" subheader="Learning by building, build the Systems that work">}}

<p>Redstonetics is where I turn learning into working systems. I use it to document experiments, write about failures, and build small but real projects — not demos, but systems that run.</p>

<p>Beyond cloud infrastructure, I explore how data systems behave in the real world — outside of vendor platforms and managed services.</p>

<p>This includes working with:</p>

<ul>
  <li>Open-source data platforms</li>
  <li>Self-hosted data stacks on VMs and Kubernetes</li>
  <li>On-prem, hybrid, and low-cost cloud environments</li>
</ul>

<p>I build and test how:</p>

<ul>
  <li>Data moves from raw sources into analytical models</li>
  <li>Metadata, lineage, and quality are managed</li>
  <li>Failures, retries, and backfills actually behave</li>
</ul>


<p>It keeps my work grounded in reality — not just in diagrams or vendor architectures, but in systems that engineers and analysts can actually run and trust.</p>

{{< /timelineItem >}}

<!-- -------------------------------------------------------------------------------------- 
-->

{{< timelineItem icon="globe" header="Where I’m going" badge="Future" subheader="Principal  platform engineer?" >}}

<p>My goal is to become a principal platform engineer, specializing in building and running data systems.</p>

<p>I want to work across:</p>

<ul>
  <li>Public cloud, private cloud, and on-prem environments</li>
  <li>Open-source </li>
  <li>Infrastructure, platforms, and data pipelines</li>
</ul>

<p>I care about systems that:</p>

<ul>
  <li>Actually work and provide real value</li>
  <li>Easy for teams to operate, without vendor lock-in</li>
  <li>Survive real-world usage, load, and mistakes</li>
</ul>



{{< /timelineItem >}}


<!-- {{< timelineItem icon="code" header="Key Projects" badge="Links" subheader="Real systems, real constraints" >}}
Each bullet:

What problem

What you built

What tech

What you learned

Example:

Cloud data pipeline

Kubernetes lab

Monitoring stack

Cost-optimized architecture
{{< /timelineItem >}} -->

<!-- {{< timelineItem icon="code" header="Another Awesome Header" badge="date - present" subheader="Awesome Subheader" >}}
With html code
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
{{< /timelineItem >}}


{{< timelineItem icon="star" header="Shortcodes" badge="AWESOME" >}}
With other shortcodes
{{< gallery >}}
  <img src="gallery/01.jpg" class="grid-w33" />
  <img src="gallery/02.jpg" class="grid-w33" />
  <img src="gallery/03.jpg" class="grid-w33" />
  <img src="gallery/04.jpg" class="grid-w33" />
  <img src="gallery/05.jpg" class="grid-w33" />
  <img src="gallery/06.jpg" class="grid-w33" />
  <img src="gallery/07.jpg" class="grid-w33" />
{{< /gallery >}}
{{< /timelineItem >}}

{{< timelineItem icon="code" header="Another Awesome Header">}}
{{< github repo="nunocoracao/blowfish" >}}
{{< /timelineItem >}}

{{< /timeline >}} -->