STATS SA CHANGE MANAGEMENT PROCESS SELECTOR — POWER APPS CODE APP

This project keeps the original interactive HTML/JavaScript application.
DO NOT paste index.html into Canvas App View Code/Source Code (PaYaml).

Requirements: Node.js LTS, Power Apps Code Apps enabled in your environment, and access to the Power Apps CLI.

1. Extract the ZIP and open its folder in Visual Studio Code.
2. In the VS Code terminal, run:
   npm install --global @microsoft/power-apps-cli
   npm install --global @microsoft/power-apps
   npm install
3. Run: pa app init --display-name "Stats SA Change Process Selector" --environment-id YOUR_ENVIRONMENT_ID
4. Run: pa app run
   Test all 11 questions and result calculation using the Local Play URL.
5. Run: npm run build
6. Run: pa app push
7. Open the returned Power Apps URL and share the app through the Power Apps portal.

Notes: Power Apps initialization creates environment-specific configuration, so this ZIP cannot be deployed just by clicking Import or pasting YAML. Your original application stores no central records and exports CSV locally. Governance pathways remain provisional.

Official guide: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/how-to/create-an-app-from-scratch
