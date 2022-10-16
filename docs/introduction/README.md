# Introduction
## What is Playwright
Playwright is an awesome cross-browser end-to-end testing solution, faster than the competition on realistic benchmark scenarios.

Playwright Test is an amazing solution for end-to-end browser testing. In this article, we will see how to set up a sandbox to automate browser tests from a web page with StackBlitz.

Playwright is an open-source project maintained and sponsored by Microsoft. It offers a unified API that can drive the main web browsers: Chromium, Webkit and Firefox. The project started in 2020, but is based on several principles of Puppeteer, the famous tool to automate Chrome headless (without GUI). Indeed, part of the team left Google to create a more ambitious solution, supporting the most popular browser families. Playwright not only automates browsers, but also facilitates reliable end-to-end testing for the modern web.

![Playwright logo](image1.png)

## Requirements
### System requirements
- Windows or Windows Subsystem for Linux (WSL)
- macOS 11 (Big Sur) or above
- Depending on your Linux distribution, you might need to install additional dependencies to run the browsers

:::note
Only Ubuntu 18.04, 20.04, and 22.04 are officially supported.
:::

https://playwright.dev/docs/troubleshooting#system-requirements

### Node.js LTS
Playwright requires Node.js 14 or higher. I recommend Node LTS via nvm
https://playwright.dev/docs/troubleshooting#nodejs-requirements

### VS Code + Playwright Test for VS Code
https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright


References  
https://playwright.dev/docs/troubleshooting  
