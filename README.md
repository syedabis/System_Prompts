# 🤖 Production-Ready AI System Prompts Repository

A curated collection of production-grade, highly structured system prompts optimized for LLMs (Gemini, ChatGPT, Claude, Grok, etc.) across diverse business and operational use cases.

---

## 📁 Repository Overview

### 1. 💬 General & Conversational AI
- **[`general_chatbot.md`](./general_chatbot.md)**: Master general-purpose AI assistant prompt featuring zero-hallucination policies, context-aware memory, adaptive depth (ELI5 to technical), and safety guardrails.

### 2. 📧 Sales, Marketing & Copywriting
- **[`cold_email_writer.md`](./cold_email_writer.md)**: Specialized B2B outbound cold email sequence generator pitching AI Chatbot & Automation services. Includes target deliverability metrics (Open/Reply rates), ROI numbers, and an optimization checklist.
- **[`blog_writer.md`](./blog_writer.md)**: SEO long-form article generator with headline CTR formulas, meta descriptions, readability constraints (Flesch-Kincaid), and CTA structures.

### 3. 👥 HR & Talent Acquisition
- **[`job_description_writer.md`](./job_description_writer.md)**: Inclusive Job Description builder with role summaries, must-have/nice-to-have qualifications, and an objective 4-tier candidate evaluation rubric.

### 4. 🛠️ Customer Support & Support Operations
- **[`ticket_priority_classifier.md`](./ticket_priority_classifier.md)**: Ticket classifier evaluating urgency, sentiment, and issue types into CRITICAL/HIGH/MEDIUM/LOW tiers.
- **[`response_template_generator.md`](./response_template_generator.md)**: Dynamic response template generator with tone variations (Professional vs. Casual) and placeholder schemas.
- **[`customer_sentiment_analyzer.md`](./customer_sentiment_analyzer.md)**: Multi-dimensional sentiment scoring (-1.0 to +1.0), emotional triggers, and pain points extractor.
- **[`troubleshooting_decision_tree.md`](./troubleshooting_decision_tree.md)**: Diagnostic flowchart builder outputting structured, valid JSON decision trees.
- **[`faq_knowledge_base_builder.md`](./faq_knowledge_base_builder.md)**: SEO-optimized FAQ architect with internal linking strategies, anchor targets, and search metadata.
- **[`customer_churn_risk_identifier.md`](./customer_churn_risk_identifier.md)**: Churn risk predictor detecting signal trends, retention probabilities, and targeted intervention plans.
- **[`support_script_optimizer.md`](./support_script_optimizer.md)**: Script analyzer enhancing empathy, objection handling, and generating A/B test variations.
- **[`complaint_root_cause_analyzer.md`](./complaint_root_cause_analyzer.md)**: "5 Whys" root cause analysis framework categorizing systemic issues and severity impact.
- **[`multilingual_response_translator.md`](./multilingual_response_translator.md)**: Technical support translator with glossary mapping, tone calibration, and cultural adaptation.
- **[`customer_profile_summarizer.md`](./customer_profile_summarizer.md)**: Customer persona aggregator synthesizing LTV, purchase patterns, and personalized support needs.
- **[`support_metric_dashboard_designer.md`](./support_metric_dashboard_designer.md)**: Specification builder for real-time support operations analytics dashboards.
- **[`escalation_workflow_builder.md`](./escalation_workflow_builder.md)**: Incident management and escalation matrix designer spanning Level 1 to Executive sign-off.
- **[`email_template_compliance_checker.md`](./email_template_compliance_checker.md)**: Audit prompt evaluating email templates against GDPR/CCPA, brand guidelines, and WCAG accessibility standards.
- **[`product_issue_documentation_creator.md`](./product_issue_documentation_creator.md)**: Technical issue documentation architect crafting problem descriptions, workarounds, and user timelines.
- **[`support_team_training_curriculum.md`](./support_team_training_curriculum.md)**: Onboarding and progressive skill curriculum designer for support representatives.

---

## 🛠️ Prompt Architecture Standard

All system prompts in this repository follow a standardized XML-tagged modular structure:
- `<system_context>` / `<system_identity>`: Defines role, objective, and persona boundaries.
- `<copywriting_rules>` / `<directives>`: Guardrails, tone standards, and behavioral constraints.
- `<input_placeholders>`: Standardized `{VARIABLE}` syntax for dynamic population.
- `<output_format>`: Clean Markdown or JSON schema expectations.
