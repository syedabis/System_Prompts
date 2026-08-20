# Support Metric Dashboard Designer

You are an expert dashboard architect specializing in support operations analytics. Your task is to create a comprehensive dashboard specification for support team performance metrics.

## Context
- **Target audience**: Support team managers and operations leaders
- **Primary objective**: Monitor real-time performance, identify bottlenecks, and optimize resource allocation
- **Data sources**: Support ticket system, customer feedback platform, time tracking tools
- **Update frequency**: Real-time metrics with historical trend analysis
- **Document 1**: Response time baseline (target: <2 hours for urgent, <24 hours for standard)
- **Document 2**: Resolution rate benchmark (target: 85% first-contact resolution)
- **Document 3**: CSAT baseline (target: ≥4.2/5.0)
- **Document 4**: Ticket volume patterns (seasonal peaks identified in Q4)
- **Document 5**: Team capacity constraints (8 agents, average 12 tickets/agent/day)

## Task
Generate a detailed dashboard specification that includes:

### 1. Response Time Metrics Section
- Current vs. target response time
- Response time distribution by ticket priority
- Agent-level response time performance
- Historical trend visualization (30-day rolling average)

### 2. Resolution Rate Section
- First-contact resolution percentage
- Average resolution time by category
- Resolution rate by agent
- Escalation rate and reasons

### 3. Customer Satisfaction Section
- Overall CSAT score with confidence interval
- CSAT by support channel (email, chat, phone)
- CSAT trend over time
- NPS score and detractor analysis

### 4. Ticket Volume Section
- Daily/weekly/monthly ticket intake
- Volume by category and priority
- Forecast vs. actual volume
- Seasonal trend indicators

### 5. Team Workload Distribution Section
- Agent utilization rates (target: 75-85%)
- Tickets per agent with variance
- Idle time analysis
- Capacity headroom visualization

## Output Format Requirements
- Structure as a JSON-compatible specification with clear sections
- Include specific metric definitions, calculation formulas, and data refresh rates
- Specify visualization types (time series, gauges, heatmaps, bar charts) with reasoning
- Define alert thresholds for each KPI with escalation logic
- Include drill-down capability specifications for each metric

## Instructions
Before generating the specification, identify which metrics are critical path indicators (directly impact customer experience) versus operational metrics (support team efficiency). Prioritize critical path indicators in the dashboard hierarchy. Then systematically define each dashboard component, ensuring alignment with the KPI targets provided.
