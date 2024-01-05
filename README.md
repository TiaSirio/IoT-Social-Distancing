# IoT Social Distancing 🛜

## Overview 🌐

Welcome to the IoT Social Distancing project! Developed by Mattia Siriani and Matteo Visotto, this project is about the social distancing between multiple devices.

## Project Description 🔍

Our solution utilizes TinyOS, Node-Red, Cooja, and IFTTT to create a robust social distancing monitoring system. The TinyOS code, provided for motes, broadcasts messages at a frequency of 2 Hz, containing mote ID and a progressive message number for synchronization.

## Implementation 🛠️

### TinyOS Motes
We present TinyOS code for 5 motes, each broadcasting essential data to report their presence. The frequency is set at 2 Hz for optimal monitoring.

### Node-Red Configuration
Our Node-Red flow is configured to efficiently receive data through a single socket and relay mote IDs to the IFTTT platform.

### Integration with IFTTT
We leverage IFTTT for seamless integration, allowing real-time notifications and responses based on the received mote data.

### Telegram Channel
We've created a Telegram channel for additional notifications. Node-Red manages these notifications using both the Telegram official API and IFTTT Telegram bot.

## Getting Started 🚀

1. Install dependencies: TinyOS, Node-Red, Cooja, IFTTT.
2. Upload provided TinyOS code to your motes.
3. Import the Node-Red flows.
4. Setup Telegram bot and insert Telegram key.

## University Course 📖

This is the project of the exam "Internet of Things" for the Computer Science and Engineering degree at Polytechnic of Milano.

## Authors 👨‍💻

- [TiaSirio](https://www.github.com/TiaSirio)
- [matteovisotto](https://www.github.com/matteovisotto)

## Documentation 📄

For detailed information and results, refer to the [IoT_Final_Project.pdf](IoT_Final_Project.pdf) document.