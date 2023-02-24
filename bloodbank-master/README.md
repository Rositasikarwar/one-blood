<div align="center">
  <h1> One Blood Bank</h1>
</div>

This is a simple Blood Bank Web Application we made for our mini project assigment. Uses Node JS and MongoDB primarily.

## 📝 Table of Contents

- [About](#-about-)
- [Getting Started](#-getting-started-)
- [Testing](#-running-the-tests-)
- [Deployment](#-deployment-)
- [Built Using](#-built-using-)
## 🧐 About

Blood Bank is a very simple yet functional and secure Blood Bank Web Application.

If you are familiar enough in a beginner level with `Node JS` and `mongoose` this is a good project to clone and try to replicate.

## 🏁 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

- Node > 8
- Git
- MongoDB > 3.0

### Installing

Clone the repo and install the dependencies.

```bash
git clone https://github.com/rishav394/bloodbank.git
cd bloodbank-master
```

```bash
npm install
```

### Running Locally

Create a new file in root directory `.env`
Copy contents from `.env.expmple`
Make changes if required.

```bash
npm start
```

### Populating database with sample data

Edit JSON files under `util` for dummy data

```bash
npm run populate
```

## 🔧 Running the tests

Still in todos

## 🚀 Deployment

Make changes in `.env`

1. Set `DBURI` to your remote mongoDB URI
2. Scale the PORT accounrding to your host/server
3. Change NODE_ENV to production for `Morgan`
4. Remove everything after `DEBUG=`

## ⛏️ Built Using

- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - MongoDB Wrapper
- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment
- [VS Code](https://code.visualstudio.com/) - Awesome IDE

