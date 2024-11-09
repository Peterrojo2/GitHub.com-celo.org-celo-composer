Celo

Celo Composer
Build, deploy, and iterate quickly on decentralized applications using Celo.

GitHub Contributors GitHub Contributors Issues GitHub pull requests MIT License

Table of Contents
About The Project
Celo Composer allows you to quickly build, deploy, and iterate on decentralized applications using Celo. It provides a number of frameworks, examples, and Celo specific functionality to help you get started with your next dApp.

(back to top)

Built With
Celo Composer is built on Celo to make it simple to build dApps using a variety of front-end frameworks, and libraries.

Celo
Solidity
Next.js
React.js
viem
Hardhat
(back to top)

Prerequisites
Node (v20 or higher)
Git (v2.38 or higher)
How to use Celo Composer
The easiest way to start with Celo Composer is using @celo/celo-composer. This CLI tool lets you quickly start building dApps on Celo, including several templates. To get started, just run the following command, and follow the steps:

Step 1
npx @celo/celo-composer@latest create
Step 2: Provide the Project Name: You will be prompted to enter the name of your project.
What is your project name: 
Step 3: Choose to Use Hardhat: You will be asked if you want to use Hardhat. Select Yes or No.
Do you want to use Hardhat? (Y/n)
Step 4: Choose to Use a Template: You will be asked if you want to use a template. Select Yes or No.
Do you want to use a template?
Step 5: Select a Template: If you chose to use a template, you will be prompted to select a template from the list provided.
- Minipay
- Valora
- Social Connect
Step 6: Provide the Project Owner's Name: You will be asked to enter the project owner's name.
Project Owner name:
Step 7: Wait for Project Creation: The CLI will now create the project based on your inputs. This may take a few minutes.

Step 8: Follow the instructions to start the project. The same will be displayed on the console after the project is created.

🚀 Your starter project has been successfully created!

Before you start the project, please follow these steps:

1. Rename the file:
   packages/react-app/.env.template
   to
   packages/react-app/.env

2. Open the newly renamed .env file and add all the required environment variables.

Once you've done that, you're all set to start your project!

Run the following commands from the packages/react-app folder to start the project:

   yarn install
   yarn dev

If you prefer npm, you can run:

   npm install
   npm run dev

Thank you for using Celo Composer! If you have any questions or need further assistance, please refer to the README or reach out to our team.
🔥Voila, you have a dApp ready to go. Start building your dApp on Celo.

Getting started
Once your custom dApp has been created, just install dependencies, either with yarn or npm i, and run the respective script from the package.json file.

Supported Frameworks
React / Nextjs
Support for Website and Progressive Web Application.
Works with all major crypto wallets.
Check nextjs docs to learn more about it.

Hardhat
Robust framework for building and testing smart contracts.
Compatible with various Ethereum development tools and plugins.
Check hardhat docs to learn more about it.

Supported Templates
Minipay
Pre-built template for creating a mini-payment application.
Seamless integration with Celo blockchain for handling payments.
Checkout minipay docs to learn more about it.

Valora
Template designed for Valora wallet integration.
Facilitates easy wallet connectivity and transaction management.
Checkout valora docs to learn more about it.

Social Connect
Template for building applications with social connectivity features.
Supports various social login methods and user interactions.
Checkout social connect docs to learn more about it.

🔭 Learning Solidity
📕 Read the docs: https://docs.soliditylang.org

Primitive Data Types
Mappings
Structs
Modifiers
Events
Inheritance
Payable
Fallback
📧 Learn the Solidity globals and units

Support
Join the Celo Discord server at https://chat.celo.org. Reach out on the dedicated repo channel here.

Roadmap
See the open issues for a full list of proposed features (and known issues).

(back to top)

Contributing
We welcome contributions from the community.

(back to top)

License
Distributed under the MIT License. See LICENSE.txt for more information.

Contact
@CeloDevs
Discord
(back to top)
