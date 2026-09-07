# Task management API

An Express and MongoDB task API with create, list, detail, update, completion, and delete operations. It also contains a server-rendered task listing route.

**Collection:** Node.js and APIs · [Project directory](https://github.com/Rspinelli93/Rspinelli93/blob/main/PROJECTS.md)

**Related repository:** [iamfullstackdev](https://github.com/Rspinelli93/iamfullstackdev)

## Stack

`cors`, `dotenv`, `express`, `mongoose`.

## Run locally

Install Node.js and npm, then run:

```bash
git clone https://github.com/Rspinelli93/back-join.git
cd back-join
npm install
npm start
```

The start script uses Node’s `--watch` option; use a Node version that supports it.

## Configuration

The source reads these environment variables. Configure them locally before starting the relevant integrations; values are not included here.

| Variable | Used by |
| --- | --- |
| `MONGO_URI` | [`config/config.js`](config/config.js) |
| `PORT` | [`index.js`](index.js) |

## Available commands

| Command | Script in package.json |
| --- | --- |
| `npm run start` | `node --watch index.js` |

The `test` script is a placeholder; an automated test suite is not configured through that command.

## Repository guide

- [`config/`](config/)
- [`controllers/`](controllers/)
- [`index.js`](index.js)
- [`models/`](models/)
- [`package.json`](package.json)
- [`routes/`](routes/)

---

[Back to my GitHub profile](https://github.com/Rspinelli93)
