# Building an AI-Ready Analytics Platform with Microsoft Fabric

**ESPC 2026 | Hands-on tutorial | 30 November 2026**

Welcome to the companion repository for **Building an AI-Ready Analytics Platform with Microsoft Fabric** at ESPC 2026.

This tutorial explores how to build an end-to-end analytics platform with Microsoft Fabric and extend trusted analytics data into AI-powered experiences. The session is hands-on: attendees will follow guided exercises in **their own Microsoft Fabric and Azure environments**.

> **Workshop materials are being prepared.** Datasets, code, notebooks, SQL scripts, lab guides and PowerPoint slides **will be uploaded to this repository before the tutorial**. Some folders or links described below may not yet exist. Please check back for updates.

## What you will learn

By the end of the tutorial, you will have explored how to:

1. Design an end-to-end, AI-ready analytics platform using Microsoft Fabric.
2. Implement a **Bronze, Silver and Gold** Medallion architecture using Lakehouse patterns.
3. Build reusable, metadata-driven ingestion pipelines.
4. Explore **Git integration** and introductory **CI/CD** practices for Fabric items.
5. Use **Fabric Data Agents, Copilot and Microsoft Foundry** to enable intelligent analytics experiences, subject to feature availability in your environment.

## Who should attend?

A basic understanding of data engineering or analytics concepts such as ingestion, transformation and SQL is helpful. **Previous Microsoft Fabric experience is not required.** Basic Python familiarity may help with notebook exercises, but guided materials will be provided.

## Before you attend: bring your own environment

**ESPC is not providing a shared Fabric or Azure lab environment for this tutorial.** Please arrange access to your own services and test them **before 30 November**.

| Service / tool | What you need to check |
| --- | --- |
| **Microsoft Fabric** | An active Fabric Trial or suitable paid Fabric capacity, with a workspace assigned to it. Verify that your capacity and tenant settings support the planned features. |
| **Workspace permissions** | Sufficient rights to create, edit and run Lakehouses, Data Factory pipelines, Notebooks and Warehouses. Workspace **Contributor or higher** is generally appropriate for core labs, subject to tenant and item-level controls. |
| **Lakehouse / OneLake** | Permission to upload sample files, create tables and read/write the lab data. |
| **Data Factory pipelines** | Permission to create connections and run pipelines. Some connectors may require additional approval. |
| **Spark notebooks** | Permission and available capacity to start Spark sessions and execute notebooks. |
| **Warehouse** | Permission to create and query a Warehouse and run the provided SQL scripts. |
| **Fabric Data Agent** | Confirm that your tenant, region, capacity and permissions support creating and using a Data Agent. Feature availability may vary. |
| **Fabric Copilot** | Check whether Copilot is enabled and supported in your tenant/capacity. Copilot-dependent activities may be demonstrated if it is unavailable to attendees. |
| **Azure subscription** | An active subscription you are authorised to use for workshop exercises; organisational policies may restrict resource creation. |
| **Microsoft Foundry** | Access to a Foundry project and a usable model deployment, with appropriate project/resource permissions, supported region and sufficient quota. Your administrator may need to provision these in advance. |
| **GitHub / Git integration** | Access to GitHub and permission to connect Fabric to a repository, if participating in the Git exercise. Organisational tenant settings may restrict this. |
| **Browser and laptop** | Bring your laptop with an up-to-date Microsoft Edge or Google Chrome browser. Visual Studio Code is optional. |

**Cost note:** Fabric trials have eligibility and duration limits. Azure resources and AI model usage may incur charges. Check your organisation's policies, subscription budget and quotas. Do not activate a time-limited trial too early.

## Five-minute readiness check

Before travelling, confirm that you can:

- [ ] Sign in to [Microsoft Fabric](https://app.fabric.microsoft.com/) and open a workspace backed by an appropriate capacity.
- [ ] Create a **Lakehouse** and upload a small test CSV file.
- [ ] Create and run a **Notebook** with a simple Spark statement.
- [ ] Create or open a **Data Factory pipeline** and access the pipeline editor.
- [ ] Create or open a **Warehouse** and execute a simple SQL query.
- [ ] Confirm whether **Data Agents** and **Copilot** are available in your tenant.
- [ ] Sign in to [Microsoft Foundry](https://ai.azure.com/) and verify project access and a usable model deployment.
- [ ] Access [GitHub](https://github.com/) and check whether Fabric Git integration is permitted if you plan to complete that exercise.
- [ ] Confirm your laptop can access the workshop repository: <https://github.com/alpaBuddhabhatti/ESPC2026/>.

If any of these checks fail, contact your organisation's Fabric or Azure administrator **before the tutorial**. Feature-specific exercises may have alternate guided or demonstration paths.

## Planned hands-on journey

The workshop will use a connected **retail analytics** scenario, subject to final lab validation:

| Lab | Focus | Expected outcome |
| --- | --- | --- |
| 0 | Environment check | Confirm workspace, capacity and required access. |
| 1 | Data ingestion | Load sample retail datasets using Fabric pipelines and metadata-driven patterns. |
| 2 | Medallion architecture | Use Lakehouse and notebooks to transform Bronze → Silver → Gold data. |
| 3 | Analytics serving | Use Warehouse and SQL to query curated retail data. |
| 4 | Git and CI/CD | Explore source control and introductory deployment practices. |
| 5 | AI-ready analytics | Explore Fabric Data Agents, Copilot and Foundry for grounded analytics questions. |

**Scenario:** Investigate retail sales performance using synthetic sales, products, stores and inventory data. The exercises will illustrate how reliable data engineering supports trustworthy AI insights.

## Materials that will be uploaded

This repository will be updated before the tutorial with the final set of materials:

- **Sample datasets** — synthetic retail data for the hands-on exercises.
- **Notebooks** — guided Bronze, Silver and Gold processing examples.
- **SQL scripts** — Warehouse objects and analytical queries.
- **Pipeline examples and metadata** — reusable ingestion patterns.
- **AI examples** — Data Agent and Foundry configuration, prompts and guidance.
- **Lab documentation** — step-by-step instructions, expected outcomes and troubleshooting.
- **Presentation slides** — tutorial PowerPoint and supporting architecture diagrams.

**Estimated download size:** approximately **50–100 MB per attendee** (planning estimate; final size to be confirmed). Most activities will run in browser-based Microsoft services; no large software installation is expected during the tutorial.

## Scope and limitations

This is a practical introduction to an AI-ready Fabric architecture. The tutorial **does not** cover Azure tenant setup, provisioning Azure OpenAI from scratch, advanced Power BI modelling, real-time streaming architecture, enterprise networking, a full Microsoft Purview governance rollout, legacy platform migrations or advanced DevOps automation beyond introductory CI/CD concepts.

Because each attendee uses their own environment, feature availability and permissions may differ. We will use synthetic datasets rather than confidential organisational data.

## Useful links

- [Microsoft Fabric](https://app.fabric.microsoft.com/)
- [Microsoft Fabric documentation](https://learn.microsoft.com/fabric/)
- [Microsoft Foundry](https://ai.azure.com/)
- [Microsoft Foundry documentation](https://learn.microsoft.com/azure/ai-foundry/)
- [Workshop repository](https://github.com/alpaBuddhabhatti/ESPC2026/)

## Questions and updates

Please check this repository again closer to **30 November 2026** for the final lab package and any updated prerequisite instructions. For issues with your own tenant, capacity, subscription or permissions, contact your organisation's administrator ahead of the session.

---

*ESPC 2026 — Building an AI-Ready Analytics Platform with Microsoft Fabric.*
