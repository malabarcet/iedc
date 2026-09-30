### Contributing
---
#### 1. You can setup the project on your development machine using the following steps:

   ##### Install Prerequisites

   - Skip this step if Node.js and pnpm are already installed.

     <details>
     <summary>macOS / Linux</summary>

     Run in your terminal:

     ```bash
     curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.8/install.sh | bash
     \. "$HOME/.nvm/nvm.sh"
     nvm install 26
     npm install -g corepack
     corepack enable pnpm
     ```

     </details>

     <details>
     <summary>Windows</summary>

     Run in PowerShell:

     ```powershell
     powershell -c "irm https://community.chocolatey.org/install.ps1|iex"
     choco install nodejs --version="26.10.0"
     corepack enable pnpm
     npm install -g corepack
     corepack enable pnpm
     ```

     </details>

   ##### Download recommended extensions on VS Code.

   - If you're using any other IDE, your work might be easier if you download an Astro LSP.
   - You may refer [this page](https://docs.astro.build/en/editor-setup/) for help on setting up the LSP on popular IDEs.

   #### Install dependencies

   ```bash
   pnpm i
   ```
---
#### 2. Start the development server.

   ```bash
   pnpm dev
   ```
---
#### 3. Hack away! you will now be able to view live updates on the open port as you make changes to the source.
---
#### 4. You can submit PRs with your code and an admin will review it ASAP.
---
