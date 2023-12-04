# HTML Sportsmind Template

These templates are to show examples of a Sportsmind API setup, independent of framework. Components are styled using tailwindcss.

## Installation

The installation is very easy run the install command.

```bash
npm install
```

Next up we can run the dev server:

```bash
npm run dev
```

And the example website will start up.

**Note - You will need live-server globally as a dependancy. If you have not installed live-server, use the command below:**

```bash
npm install -g live-server
```

## What's included?

### `home.html``

An example homepage for a Sportsmind-like chat, including examples.

## API Basics

Our API is new and very rudimentary. We have one endpoing, our `/chat` endpoint. `/chat` takes in your API key and a question string as arguments, and returns an answer string.

If you intend to impose limits on your users with how often/much they can submit chats, you will need to handle that logic on your side before calling our API.
