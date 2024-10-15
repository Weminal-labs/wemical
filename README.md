# Wemical 🧪
[![Follow me](https://img.shields.io/github/followers/Weminal-labs?label=follow%20me&style=social)](https://github.com/Weminal-labs)
[![Follow Twitter](https://img.shields.io/twitter/follow/blueedgetechno?label=Follow%20me&style=social)](https://x.com/Wemical)
[![Join](https://img.shields.io/discord/868499076432408627.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/NcjaNdwtnR)
[![Build & Deploy](https://github.com/blueedgetechno/win11React/actions/workflows/deploy.yml/badge.svg)](https://github.com/blueedgetechno/win11React/actions/workflows/Build-Deploy.yml)
[![PR Preview](https://github.com/blueedgetechno/win11React/actions/workflows/pr-preview.yml/badge.svg)](https://github.com/blueedgetechno/win11React/actions/workflows/PR-Preview.yml)
![Uptime](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/win11react/status/master/api/win11-react/uptime.json)
[![Translate](https://badges.crowdin.net/win11react/localized.svg)](https://translate.win11react.com/)

This project is a frontend application designed to allows users to automate token swaps, provide liquidity, stake tokens, and withdraw rewards. The goal of the project is to simplify the interaction with decentralized exchanges (DEXs) and pools, offering customizable swap flows and liquidity management, with future AI integration to optimize liquidity strategies.
<p align="center">
  <a href="https://gitpoint.co/">
    <img alt="GitPoint" title="GitPoint" src="https://github.com/user-attachments/assets/838cc122-fbd3-4504-a0ca-1e9b7318fb95" width="800">
  </a>
</p>

#### Launch Demo🌈: [wemical.weminal](https://wemical.weminal.com/)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Interaction with Smart Contracts](#interaction-with-smart-contracts)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

This is a frontend repository that connects users to the Aptos blockchain. The app facilitates:
- Automated token swaps between APT, amAPT, USDC, BTC, and WEM.
- Providing and managing liquidity in various pools such as APT/amAPT, APT/USDC, and more.
- Staking and withdrawing tokens with ease.
- Customizing swap flows for users to optimize their liquidity strategies.

## Features

- **Custom Swap Flows**: Users can define and automate token swap sequences.
  ![image](https://github.com/user-attachments/assets/fcff7735-54b7-4347-9ff6-4945954bca94)

- **Liquidity Management**: Stake tokens, provide liquidity, and withdraw LP tokens from pools.
- **DEX Automation**: Automated interactions with decentralized exchanges.
- **Cross-token Swaps**: Seamless swaps between multiple tokens.
- **User-friendly Interface**: Intuitive UI that abstracts complex blockchain operations.


## Project Structure

```bash
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json    
├── public  
├── src
│   ├── App.css
│   ├── App.tsx
│   ├── assets
│   ├── components      # Reusable UI components
│   │   ├── Input
│   │   │   └── InputList.tsx
│   │   ├── Action
│   │   │   └── ActionList.tsx
│   │   └── SwapToken.tsx
│   ├── contexts        # Context providers
│   ├── index.css
│   ├── main.tsx
│   ├── pages           # Main app pages (DashboardPools, etc.)
│   ├── redux           # Redux store and slices
│   ├── types           # TypeScript types
│   ├── utils           # Utility functions and helpers
│   └── Var.ts
│   └── vite-env.d.ts
├── tailwind.config.js
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts   
└── README.md
```

# Interaction with Smart Contracts
![image](https://github.com/user-attachments/assets/3b083210-10f0-4ce0-9174-1c93b8c775ee)





# License
This project is licensed under the MIT License - see the LICENSE file for details.
