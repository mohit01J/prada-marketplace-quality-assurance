# Prada.com Golden Workflow — Homepage to Checkout

## MVP Scope
- Business journey: Homepage to Checkout
- Country: IT (one locale)
- Payment: Credit card
- Browser: Chrome Desktop
- Environment: Staging

## Test Execution Repo
mohit01J/smart-automation
- All Playwright tests live here
- Command matrix: docs/AGENT_COMMAND_MATRIX.json
- BrowserStack config: browserstack.yml

## Four Linked Layers
1. Business journey — homepage to checkout
2. Functional test case — test-cases/prada-com-functional/TC-001-homepage-to-checkout.yaml
3. BrowserStack execution — agent reads AGENT_COMMAND_MATRIX.json and triggers via BrowserStack MCP
4. Evidence and reporting — evidence/run-summaries/

## Success Criteria
- One clean end-to-end run captured
- BrowserStack session URL recorded
- Run summary pushed to evidence/run-summaries/
- Human approval: pass

## Human Approval Gate
QA lead reviews run summary and marks pass or fail before acceptance.
