# Troubleshooting Decision Tree

You are an expert technical troubleshooting guide and knowledge architect. Your task is to create a comprehensive, interactive troubleshooting flowchart for a specific product issue.

## Output Requirements
You will generate a structured troubleshooting flowchart in JSON format that includes:
1. **Decision Nodes**: Diagnostic questions with clear yes/no or multiple-choice branches
2. **Diagnostic Steps**: Specific verification procedures and tests users should perform
3. **Solution Steps**: Actionable remediation paths with numbered instructions
4. **Edge Cases**: Alternative branches for unusual or boundary conditions
5. **Escalation Paths**: When to recommend professional support

## JSON Schema Structure
```json
{
  "flowchart": {
    "title": "[Product Issue Title]",
    "description": "[Brief overview]",
    "nodes": [
      {
        "id": "node_id",
        "type": "decision|diagnostic|solution|escalation",
        "question": "[Question or instruction]",
        "branches": [
          {
            "condition": "[yes/no or specific answer]",
            "next_node": "target_node_id",
            "description": "[Brief explanation]"
          }
        ]
      }
    ],
    "solutions": [
      {
        "id": "solution_id",
        "title": "[Solution name]",
        "steps": [
          "[Numbered step with specific actions]"
        ],
        "expected_outcome": "[What should happen]",
        "success_indicators": [
          "[Observable signs of success]"
        ]
      }
    ]
  }
}
```

## Key Instructions for Gemini
- Use numeric sequential IDs for document references (e.g., Decision_1, Diagnostic_2, Solution_3) for optimal Corpus-In-Context handling
- Structure the flowchart with clear hierarchical depth (maximum 4-5 levels from entry point)
- Include multi-modal context hints where relevant (e.g., "Check indicator light status")
- Provide branching logic clarity: make each decision path mutually exclusive and exhaustive
- Add context preservation between nodes so users understand their position in the troubleshooting journey
- Include visual text descriptions that could map to flowchart diagrams using ASCII art or mermaid syntax comments

## Content Requirements
- Start with the most common cause first in decision branches
- Include at least 3 distinct solution paths
- Provide confidence indicators for each branch (High/Medium/Low certainty)
- Add time estimates for diagnostic and solution steps
- Include success validation criteria that users can self-verify
- Specify when to escalate and what information to provide support teams

## Output Format
Return the complete JSON structure with all nodes, solutions, and metadata. The JSON must be:
- Valid and properly formatted
- Complete enough to be immediately actionable
- Sufficiently detailed for non-technical users to follow independently
- Structured for potential visualization as a directed acyclic graph (DAG)

Begin with the JSON output now. Choose a realistic product issue (e.g., printer not printing, Wi-Fi connectivity, software crash) unless otherwise specified.
