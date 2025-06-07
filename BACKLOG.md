# Backlog for Branded Extension with Grant Mill Software Credit

This backlog captures the high level work to customize and validate the Visual Studio Code extension contained in this repository.

## Milestone 1: Environment Setup
- [ ] Install Node.js 18+
- [ ] Install .NET 8
- [ ] Install Python 3.10
- [ ] Install Docker
- [ ] Install `yo` and `generator-code`

## Milestone 2: Extension Foundation
- [ ] Run `yo code` to scaffold the base extension
- [ ] Configure project files and dependencies
- [ ] Set up debugging in VS Code

## Milestone 3: Semantic Kernel Integration
- [ ] Reference Semantic Kernel libraries
- [ ] Implement API calls for code analysis features

## Milestone 4: Promptflow Integration
- [ ] Add Promptflow logic for conversational interactions
- [ ] Connect planner features for improved prompts

## Milestone 5: Branding and Credit
- [ ] Update `package.json` `displayName` to "Grant Mill Copilot"
- [ ] Add credit line "© Grant Mill Software" to README and UI banner
- [ ] Include Grant Mill logo in `/media` assets if available

## Milestone 6: Packaging and Testing
- [ ] Run the extension via `npm run test`
- [ ] Verify commands: Check Code, Explain Code, Regeneration Code
- [ ] Create screenshots or GIFs showing the extension in action

## Milestone 7: Publish and Demo
- [ ] Build VSIX package with `vsce package`
- [ ] Install the VSIX in a fresh VS Code environment
- [ ] Capture evidence of the branded extension running

