🕵️‍♂️ Random Secrets App

Ever wondered what anonymous strangers are hiding?

This is a simple Node.js app that pulls **random secrets** from the internet using the [Secrets API](https://secrets-api.appbrewery.com/) and displays them on the homepage — all wrapped in an EJS template and powered by Express.

Perfect for getting started with APIs, templating, and making something weird and fun.

---

🔧 What I Used

- **Express.js** – backend framework
- **EJS** – to render the dynamic content
- **Axios** – to fetch random secrets from the API
- **Body-parser** – included for future use (forms maybe?)
- **Node.js** – obviously

---

📦 Getting Started

Clone the repo and install the dependencies:

```bash
git clone https://github.com/YOUR-USERNAME/random-secrets-app.git
cd random-secrets-app
npm install
node index.js
```

Go to http://localhost:3000 in your browser — you'll see a random secret and the name of the person who (supposedly) shared it.
