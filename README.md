# Botometer Pro MCP Server

Welcome to the Botometer Pro MCP Server, a comprehensive tool for analyzing Twitter accounts to determine their level of automation. Botometer Pro provides multiple endpoints to assess the bot-like characteristics of Twitter accounts, allowing users to make informed decisions based on the scores received.

## Overview

The Botometer Pro server offers a variety of tools to evaluate Twitter accounts for bot-like activities. These tools are designed to cater to different needs and can analyze accounts in bulk or individually, providing flexibility to users.

## Tools

### Botometer X

The Botometer X tool checks Twitter accounts for potentially automated activities. It operates in archival mode, using pre-calculated scores based on historical data. This tool is ideal for users who do not have access to live Twitter data, as it only requires user IDs and/or usernames for analysis.

Key Features:
- No need for live Twitter data input.
- Utilizes historical data up to May 31, 2023.
- Provides scores with timestamps for context.
- Suitable for bulk analysis, handling up to 100 accounts per request.

### Botometer V4 (Legacy)

The Botometer V4 tool offers a detailed analysis of a single Twitter account. Users need to provide Twitter data, such as user information and tweets, for the tool to compute bot scores. This version is comparable to previous iterations of Botometer.

Key Features:
- Requires Twitter data, including user info and timeline tweets.
- Analyzes and scores accounts using comprehensive features.
- Provides detailed results with sub-scores for various bot types.

### BotometerLite (Legacy)

BotometerLite is designed for bulk analysis, allowing users to check multiple accounts simultaneously. This tool requires either tweet data or user profile data from Twitter for evaluation.

Key Features:
- Suitable for bulk checks, handling up to 100 accounts per request.
- Offers a simplified scoring system for quick assessments.
- Requires tweet objects or user profiles for input.

## Usage

- **Botometer X**: Best for users without direct Twitter API access, focusing on historical data analysis.
- **Botometer V4**: Ideal for detailed analysis of individual accounts, requiring complete Twitter data.
- **BotometerLite**: Efficient for bulk account analysis, using either tweets or user profile data.

The Botometer Pro MCP Server is a versatile and powerful tool for anyone looking to understand the automation levels of Twitter accounts. Whether you are a researcher, developer, or data analyst, the tools provided by Botometer Pro can help you gain insights into the bot-like behavior of accounts with ease and precision.