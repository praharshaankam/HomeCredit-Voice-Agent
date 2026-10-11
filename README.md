# Home Credit Loan Against Property Voice Agent

## Project Overview

This project implements an AI-powered voice agent for Home Credit to conduct preliminary Loan Against Property (LAP) eligibility checks with existing customers.

The agent explains the preliminary offer, collects customer and property information, identifies disqualification conditions, detects loan-transfer requests, and directs eligible customers to a senior loan expert for further assistance.

## Technology Stack

- Retell AI — voice agent and conversation flow
- Large Language Model — natural-language understanding and response generation
- VS Code — prompt development, documentation and testing records

## Key Features

- Natural customer conversations and identity confirmation
- Seven-item preliminary eligibility checklist
- Handling of interruptions and out-of-order answers
- Immediate disqualification for specified ineligible conditions
- Loan-transfer request detection
- Callback handling when a customer is busy
- Senior loan expert follow-up after successful qualification

## Eligibility Rules

- Eligible property types: Residential, Commercial and Industrial
- Agricultural property: Not eligible
- Ownership: Sole or Joint
- Original property documents must be available
- Maximum offer: ₹75,00,000
- Income must be received through a bank
- Accepted occupations: Salaried and Self-employed
- Repayment tenure: 3–15 years
- Market value: Captured without inventing an additional threshold

## Testing

Eleven test scenarios were executed. The detailed scenarios and actual results are documented in `test_scenarios.md` and `test_results.md`.

## Evidence

- Retell AI Agent: [Add your agent access link if available]
- Call Recordings and Logs: [Add your public evidence link]
- System Prompt: `system_prompt.md`
- Test Scenarios: `test_scenarios.md`
- Test Results: `test_results.md`

## Limitations

The agent performs preliminary qualification only. Final loan approval and exact interest rates are determined through the appropriate loan expert and lender process.
