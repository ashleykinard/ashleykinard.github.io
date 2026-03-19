---
layout: page
title: Portfolio
subtitle: A selection of API documentation, developer guides, and technical writing projects.
permalink: /portfolio/
---

<style>
  .portfolio-grid { display: grid; grid-template-columns: 1fr; gap: 25px; margin-top: 20px; }
  .project-card { border: 1px solid #e2e8f0; border-radius: 10px; padding: 25px; background: #ffffff; transition: 0.3s cubic-bezier(0.25, 0.8, 0.25, 1); border-left: 5px solid #2c3e50; }
  .project-card:hover { box-shadow: 0 10px 20px rgba(0,0,0,0.05); border-color: #cbd5e0; transform: translateY(-2px); }
  .tag-container { margin-bottom: 12px; display: flex; flex-wrap: wrap; gap: 6px; }
  .tag { background: #f1f5f9; color: #475569; padding: 3px 10px; border-radius: 4px; font-size: 0.7em; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; border: 1px solid #e2e8f0; }
  .project-title { margin: 0 0 10px 0; color: #1e293b; font-size: 1.4em; }
  .project-desc { color: #475569; line-height: 1.6; margin-bottom: 20px; font-size: 0.95em; }
  .btn-link { display: inline-block; background: #2c3e50; color: white !important; padding: 8px 18px; border-radius: 6px; text-decoration: none !important; font-size: 0.85em; font-weight: bold; transition: background 0.2s; }
  .btn-link:hover { background: #4a5568; }
  .section-hr { margin: 40px 0 30px 0; border: 0; border-top: 1px solid #eee; }
</style>

The following is a curated look at my work, focusing on **Developer Experience (DX)**, **API Reference**, and **Systems Documentation**.

<hr class="section-hr">

## API Documentation and Developer Experience

*High-level documentation for global developer ecosystems.*

<div class="portfolio-grid">

  <div class="project-card">
    <div class="tag-container">
      <span class="tag">Postman</span> <span class="tag">OpenAPI</span> <span class="tag">JSON</span>
    </div>
    <h3 class="project-title">Postman Public API Reference</h3>
    <p class="project-desc">
      Collaborated with the Postman API engineering team to refine the public API workspace. Strong focus on structural clarity in OpenAPI definitions to ensure auto-generated documentation remained accurate and user- and machine-friendly.
    </p>
    <a href="https://www.postman.com/postman/workspace/postman-public-workspace/collection/12932820-8356948a-6b83-42e4-98c7-43f9a742886c" class="btn-link" target="_blank" rel="noopener">View Collection</a>
  </div>

  <div class="project-card">
    <div class="tag-container">
      <span class="tag">Zoom</span> <span class="tag">Webhooks</span> <span class="tag">Technical Review</span>
    </div>
    <h3 class="project-title">Zoom Developer Documentation</h3>
    <p class="project-desc">
      Managed documentation for Zoom's API and webhooks. This involved reviewing engineering merge requests for technical accuracy and documenting monthly releases for a global developer community.
    </p>
    <a href="https://developers.zoom.us/docs/api/" class="btn-link" target="_blank" rel="noopener">View API Docs</a>
  </div>

</div>

<hr class="section-hr">

## Technical Guides and Tutorials

*End-user and administrator-facing documentation for complex server software.*

<div class="portfolio-grid">

  <div class="project-card">
    <div class="tag-container">
      <span class="tag">cPanel</span> <span class="tag">Markdown</span> <span class="tag">Systems</span>
    </div>
    <h3 class="project-title">cPanel Linked Nodes Guide</h3>
    <p class="project-desc">
      Authored the primary documentation for server clustering features. This involved deep-diving into terminal scripts and translating engineering logic into task-oriented guides for system administrators.
    </p>
    <a href="https://docs.cpanel.net/knowledge-base/general-topics/linked-nodes-guide/" class="btn-link" target="_blank" rel="noopener">View Guide</a>
  </div>

  <div class="project-card">
    <div class="tag-container">
      <span class="tag">CLI</span> <span class="tag">Automation</span> <span class="tag">Technical Reference</span>
    </div>
    <h3 class="project-title">Balance Linked Node Quotas Reference</h3>
    <p class="project-desc">
      Developed a technical reference for a command-line script used to automate resource balancing. Focused on clear parameter definitions and practical usage examples.
    </p>
    <a href="https://docs.cpanel.net/cpanel/scripts/the-balance_linked_node_quotas-script/" class="btn-link" target="_blank" rel="noopener">View Script Reference</a>
  </div>

</div>

<hr class="section-hr">

## Process and Governance

*Templates and style guides to maintain documentation quality.*

<div class="portfolio-grid">
  <div class="project-card">
    <div class="tag-container">
      <span class="tag">Governance</span> <span class="tag">Markdown Templates</span>
    </div>
    <h3 class="project-title">Developer Relations Style Guide</h3>
    <p class="project-desc">
      Created Markdown templates (FAQs, troubleshooting, and article submissions) to unify the voice and tone of the Zoom Developer Relations team.
    </p>
  </div>
</div>