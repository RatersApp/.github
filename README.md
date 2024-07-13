# .github
RatersApp is a SocialFi platform powered by the internet-computer blockchain, designed for movie lovers. It provides a space to share movie-reviews, ratings, and discover films.
RatersApp: Discover, Rate, and Review Movies

RatersApp is a SocialFi platform powered by the Internet Computer (ICP) blockchain, designed for movie lovers. It provides a space to share reviews, ratings, and discover films.
Overview

Architecture and Tech Stack:

    Frontend: React.js, Next.js, TypeScript
    Backend: Node.js and Express
    Blockchain: Internet Computer (ICP)
    Database: Canister storage on ICP

Milestones and Progress

Milestone 1: Research, Preliminary Setup, and Initial Backend Development (1 month)

    Understanding NFID and Internet Identity: Comprehensive study and environment setup for NFID and Internet Identity.
    Backend Development: Development of an API interface and database structuring.
    Frontend Design: Preliminary design sketches for authentication processes.

Milestone 2: Front-end Integration, Testing, and Security (1 month)

    Front-end Integration: Development of the user interface and event handlers for authentication processes.
    Security: Implementation of measures to protect user data.
    Testing and Debugging: Comprehensive testing and resolution of bugs.
    Merge of Accounts: Integration for existing users to connect their NFID and Internet Identity.

Milestone 3: Final Integration, Documentation, and Deployment (1 month)

    Final Integration: Seamless interoperability of NFID and Internet Identity.
    Documentation and Support: Detailed user documentation and support training.
    Deployment: Official rollout with notifications to all users.

Project Components
Raters Canister

Raters Canister provides decentralized management and verification of ratings using ICP canisters.

Features:

    Decentralized rating management
    Secure user interactions
    Efficient data storage and retrieval

Installation:

    Clone the repository:

    bash

git clone https://github.com/RatersApp/canister.git
cd canister

Install dependencies:

bash

npm install

Configure the environment:
Edit configuration files as needed.
Deploy the canister:

bash

    dfx deploy

Raters Backend JS

Raters Backend JS focuses on blockchain integration and encryption functionalities using Node.js.

Features:

    User authentication and authorization
    CRUD operations for ratings
    API endpoints for various entities
    Middleware for validation and error handling

Technologies Used:

    Node.js
    Nest.js
    Jest for testing

Used Packages:

    @dfinity/identity: Tools for managing decentralized identities.
    @dfinity/candid: Type system for defining and validating data types in the ICP ecosystem.
    @dfinity/agent: Methods for interacting with ICP canisters.

Installation:

    Clone the repository:

    bash

git clone https://github.com/RatersApp/raters-backend-js.git
cd raters-backend-js

Install dependencies:

bash

npm install

Create a .env file in the 'services' directory and add environment variables:

env

CANISTER_HOST=https://ic0.app
CANISTER_ID=

Start the development server:

bash

    npm run start

Raters Frontend Example

Raters Frontend Example integrates Web3 authorization using Next.js and TypeScript.

Project Description:

    NFID Integration:
        Library: @nfid/embed
        Purpose: Connects NFID for authorization and obtains cryptographic keys and wallet address.

    ICP Integration:
        Libraries: @dfinity/identity, @ic-use-internet-identity
        Purpose: Provides hooks for handling ICP authorization in React.

    Wallet Address Retrieval:
        Library: @dfinity/ledger
        Method: fromPrincipal
        Purpose: Retrieves wallet address for NFID and ICP methods.

Installation:

    Clone the repository:

    bash

git clone https://github.com/RatersApp/raters-fe-example.git
cd raters-fe-example

Install dependencies:

bash

npm install

Start the development server:

bash

    npm run dev

Raters Stack:

    Backend: PHP (Laravel), ElasticSearch, MySQL, Nginx
    iOS: Objective-C
    Android: Kotlin, RxJava, Coroutines, Retrofit, Koin
    Web: React, Redux, Sagas, Next.js, Vercel
    Raters Correlation: Python, Flask

Infrastructure:

    Dedicated Server Hosting, Ubuntu, Cloudflare, Bitbucket, Docker

Note: This demo shows the blockchain implementation in the existing RatersApp.

For detailed instructions on contributing, please refer to the Contributing Guidelines.
License

This project is licensed under the MIT License. See the LICENSE file for details.
