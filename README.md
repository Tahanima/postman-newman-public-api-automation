# Postman-Newman Public API Automation

[Public API](https://api.publicapis.org) test automation using Postman and Newman.

## Installation

1. Get a copy of [postman-newman-public-api-automation](https://github.com/Tahanima/postman-newman-public-api-automation/) by clicking the <kbd><b>Fork</b></kbd> button
2. Clone, i.e, download your copy of the repository to your local machine using
```bash
git clone https://github.com/[your_username]/postman-newman-public-api-automation.git
```
3. Install [Node.js](https://nodejs.dev/en/learn/how-to-install-nodejs/)
4. Install Newman
```bash
npm install -g newman
```
5. Go to the `postman-newman-public-api-automation` folder
```
cd postman-newman-public-api-automation
```
6. Now, run the test cases in Public API postman collection using
```bash
newman run "Public API.postman_collection.json" -g public_api.postman_globals.json
```
