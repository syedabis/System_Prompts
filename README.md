# 🤖 Production AI System Prompts & Model Specifications

A curated collection of production-grade, highly structured system prompts organized by domain, alongside a comprehensive directory of system prompts and tools from leading AI applications (Cursor, Devin, v0, Manus, Perplexity, Windsurf, Replit, and more).

---

## 📁 Repository Directory Structure

```
.
├── conversational-ai/        # General Assistant & Universal Chatbot Prompts
├── n8n-prompts/             # Specialized n8n Workflow AI Chatbot Prompts (E-commerce, SaaS, HR)
├── sales-and-marketing/     # Landing Pages, Cold Email Sequences, SEO Articles
├── social-media-and-growth/  # Viral LinkedIn Posts & Lead Magnet Prompts
├── software-engineering/    # Code Audit, Security Audits, Refactoring & Test Suites
├── hr-and-recruiting/        # Job Descriptions & Candidate Evaluation Rubrics
├── customer-support/        # Ticket Classification, Churn Risk, Sentiment, FAQs
├── operations-and-finance/   # Standard Operating Procedure (SOP) Builders
└── ai-tool-system-prompts/  # Prompts from Cursor, Devin, v0, Manus, Perplexity, etc.
```

---

## 📚 Categorized System Prompts

### 1. 💬 General & Conversational AI (`/conversational-ai`)
- **[`general_chatbot.md`](./conversational-ai/general_chatbot.md)**: Master general-purpose AI assistant prompt featuring zero-hallucination policies, context-aware memory, adaptive depth (ELI5 to technical), and safety guardrails.
- **[`universal_chatbot_agent.md`](./conversational-ai/universal_chatbot_agent.md)**: Multi-domain AI chatbot prompt featuring company profile grounding and knowledge base rules.

### 2. ⚡ n8n Workflow Chatbot Prompts (`/n8n-prompts`)
- **[`n8n_ecommerce_chatbot.md`](./n8n-prompts/n8n_ecommerce_chatbot.md)**: Specialized n8n workflow chatbot prompt for online stores (Order tracking, shipping, 30-day returns, discount codes).
- **[`n8n_saas_chatbot.md`](./n8n-prompts/n8n_saas_chatbot.md)**: Specialized n8n workflow chatbot prompt for software platforms (Subscriptions, 14-day free trial, billing settings, API access).
- **[`n8n_hr_chatbot.md`](./n8n-prompts/n8n_hr_chatbot.md)**: Specialized n8n workflow chatbot prompt for internal HR support (PTO requests, sick leave, hybrid remote policy, expense claims).

### 3. 💻 Software Engineering & Security (`/software-engineering`)
- **[`code_audit_and_refactoring.md`](./software-engineering/code_audit_and_refactoring.md)**: Comprehensive code quality, OWASP security audit, performance optimization ($O(n)$ complexity & N+1 queries), clean code refactoring, and unit test generator.

### 4. 📣 Social Media & Growth (`/social-media-and-growth`)
- **[`linkedin_post_generator.md`](./social-media-and-growth/linkedin_post_generator.md)**: High-converting LinkedIn post & lead magnet generator featuring scroll-stopping hook formulas, storytelling frameworks, and comment CTA mechanics.

### 5. 📧 Sales, Marketing & Copywriting (`/sales-and-marketing`)
- **[`landing_page_copywriter.md`](./sales-and-marketing/landing_page_copywriter.md)**: High-converting SaaS landing page architect covering Hero section, logo cloud, problem agitation, 3-pillar features, pricing table, FAQ accordion, and CRO metrics.
- **[`cold_email_writer.md`](./sales-and-marketing/cold_email_writer.md)**: Specialized B2B outbound cold email sequence generator pitching AI Chatbot & Automation services. Includes target deliverability metrics (Open/Reply rates), ROI numbers, and an optimization checklist.
- **[`blog_writer.md`](./sales-and-marketing/blog_writer.md)**: SEO long-form article generator with headline CTR formulas, meta descriptions, readability constraints (Flesch-Kincaid), and CTA structures.

### 6. 👥 HR & Talent Acquisition (`/hr-and-recruiting`)
- **[`job_description_writer.md`](./hr-and-recruiting/job_description_writer.md)**: Inclusive Job Description builder with role summaries, must-have/nice-to-have qualifications, and an objective 4-tier candidate evaluation rubric.

### 7. ⚙️ Operations & Process Management (`/operations-and-finance`)
- **[`sop_builder.md`](./operations-and-finance/sop_builder.md)**: Standard Operating Procedure generator transforming raw meeting transcripts and unorganized notes into step-by-step SOPs complete with roles, troubleshooting matrices, and QA checklists.

### 8. 🛠️ Customer Support & Support Operations (`/customer-support`)
- **[`ticket_priority_classifier.md`](./customer-support/ticket_priority_classifier.md)**: Ticket classifier evaluating urgency, sentiment, and issue types into CRITICAL/HIGH/MEDIUM/LOW tiers.
- **[`response_template_generator.md`](./customer-support/response_template_generator.md)**: Dynamic response template generator with tone variations (Professional vs. Casual) and placeholder schemas.
- **[`customer_sentiment_analyzer.md`](./customer-support/customer_sentiment_analyzer.md)**: Multi-dimensional sentiment scoring (-1.0 to +1.0), emotional triggers, and pain points extractor.
- **[`troubleshooting_decision_tree.md`](./customer-support/troubleshooting_decision_tree.md)**: Diagnostic flowchart builder outputting structured, valid JSON decision trees.
- **[`faq_knowledge_base_builder.md`](./customer-support/faq_knowledge_base_builder.md)**: SEO-optimized FAQ architect with internal linking strategies, anchor targets, and search metadata.
- **[`customer_churn_risk_identifier.md`](./customer-support/customer_churn_risk_identifier.md)**: Churn risk predictor detecting signal trends, retention probabilities, and targeted intervention plans.
- **[`support_script_optimizer.md`](./customer-support/support_script_optimizer.md)**: Script analyzer enhancing empathy, objection handling, and generating A/B test variations.
- **[`complaint_root_cause_analyzer.md`](./customer-support/complaint_root_cause_analyzer.md)**: "5 Whys" root cause analysis framework categorizing systemic issues and severity impact.
- **[`multilingual_response_translator.md`](./customer-support/multilingual_response_translator.md)**: Technical support translator with glossary mapping, tone calibration, and cultural adaptation.
- **[`customer_profile_summarizer.md`](./customer-support/customer_profile_summarizer.md)**: Customer persona aggregator synthesizing LTV, purchase patterns, and personalized support needs.
- **[`support_metric_dashboard_designer.md`](./customer-support/support_metric_dashboard_designer.md)**: Specification builder for real-time support operations analytics dashboards.
- **[`escalation_workflow_builder.md`](./customer-support/escalation_workflow_builder.md)**: Incident management and escalation matrix designer spanning Level 1 to Executive sign-off.
- **[`email_template_compliance_checker.md`](./customer-support/email_template_compliance_checker.md)**: Audit prompt evaluating email templates against GDPR/CCPA, brand guidelines, and WCAG accessibility standards.
- **[`product_issue_documentation_creator.md`](./customer-support/product_issue_documentation_creator.md)**: Technical issue documentation architect crafting problem descriptions, workarounds, and user timelines.
- **[`support_team_training_curriculum.md`](./customer-support/support_team_training_curriculum.md)**: Onboarding and progressive skill curriculum designer for support representatives.

---

### 9. ⚡ Popular AI Tools & Agent System Prompts (`/ai-tool-system-prompts`)
A complete reference collection of system prompts, tool schemas, and model configurations from industry-leading AI tools:
- **Coding Agents**: [`Cursor`](./ai-tool-system-prompts/Cursor%20Prompts), [`Devin AI`](./ai-tool-system-prompts/Devin%20AI), [`Windsurf`](./ai-tool-system-prompts/Windsurf), [`Replit`](./ai-tool-system-prompts/Replit), [`Trae`](./ai-tool-system-prompts/Trae), [`Warp.dev`](./ai-tool-system-prompts/Warp.dev), [`v0`](./ai-tool-system-prompts/v0%20Prompts%20and%20Tools), [`Augment Code`](./ai-tool-system-prompts/Augment%20Code)
- **AI Frontier Labs**: [`Anthropic`](./ai-tool-system-prompts/Anthropic), [`Google`](./ai-tool-system-prompts/Google), [`Perplexity`](./ai-tool-system-prompts/Perplexity)
- **Agent Frameworks**: [`Manus Agent Tools & Prompts`](./ai-tool-system-prompts/Manus%20Agent%20Tools%20%26%20Prompt), [`Lovable`](./ai-tool-system-prompts/Lovable), [`Emergent`](./ai-tool-system-prompts/Emergent)

---

## 🛠️ Prompt Architecture Standard

All system prompts in this repository follow a standardized XML-tagged modular structure:
- `<system_context>` / `<system_identity>`: Defines role, objective, and persona boundaries.
- `<copywriting_rules>` / `<directives>`: Guardrails, tone standards, and behavioral constraints.
- `<input_placeholders>`: Standardized `{VARIABLE}` syntax for dynamic population.
- `<output_format>`: Clean Markdown or JSON schema expectations.
