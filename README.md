# Naveed MD V2

An advanced, multi-functional automation tool built on top of Node.js, designed to run seamlessly with multiple options including Heroku, Docker, and local servers.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/naveedahmed35581-arch/naveed-mdv2)

## 🚀 Features

- **Multi-Device Support**: Powered by robust underlying socket connections.
- **Docker Support**: Completely configured `Dockerfile` ready for deployment.
- **One-Click Deploy**: Fast setup with preloaded configurations from `app.json` on Heroku.
- **Extensible**: Modular command handler with straightforward plugins structure.

## ⚡ Heroku Deployment

Deploy your application directly to Heroku with one simple click of the button below:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/naveedahmed35581-arch/naveed-mdv2)

### Deployment Steps

1. Click the **Deploy to Heroku** button above.
2. Log in to your Heroku account (or sign up if you don't have one).
3. Set a unique app name and select your region.
4. Fill in the required environment variables config vars listed under the configuration fields (refer to `app.json` for all options).
5. Click **Deploy App** and watch the logs build successfully!

## 📦 Local Installation

To run the application on your local machine:

```bash
# Clone the repository
git clone https://github.com/naveedahmed35581-arch/naveed-mdv2.git

# Navigate into the project folder
cd naveed-mdv2

# Install dependencies
npm install

# Start the application
npm start
```

## 🐳 Docker Deployment

If you prefer containerized deployment, build and run using Docker:

```bash
# Build image
docker build -t naveed-mdv2 .

# Run container
docker run -d --name naveed-bot naveed-mdv2
```

## 🔧 Configuration

Configure the application by setting up environmental variables in Heroku or a `.env` file locally:

| Environment Variable | Description | Default |
|---|---|---|
| `SESSION_ID` | Unique connection session string | Required |
| `PREFIX` | Command identifier prefix | `.` |
| `OWNER_NUMBER` | The admin phone number | Required |

## 📄 License

Distributed under the MIT License. See standard terms for details.
