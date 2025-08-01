# hackathonnextgen
GIIS Hackathon Next Gen

# README.MD
Explanation of the **Screen Time Tracker**

# config.json
The `config.json` file is like a note that tells the computer what kind of project you're using. In this case, it says:

```json
{
  "template": "bolt-vite-react-ts"
}
```

This means the project is using a special setup called **"bolt-vite-react-ts"**, which includes tools to help build a website or app using **React** (a way to make websites), **TypeScript** (a kind of code that helps catch mistakes), and **Vite** (a tool that makes loading faster). It's just setting up the tools you’ll use to make your project.

# index.html
This `index.html` file is like the main page of your website — it tells the browser what to show first.

Put simply, here is what the index.html is doing:

* It sets up the **title** at the top of the tab: “AI-Powered Children's Screen Time Tracker”.
* It includes a small icon (the image on the tab).
* It makes sure the website looks good on phones and computers.
* It creates a blank area with `<div id="root"></div>` — that’s where your website content will go.
* It connects to the code file (`main.tsx`) that builds the actual app.

So this file is like the basic skeleton of your website — it gets things ready before showing the real content.

# eslint.config.js
This `eslint.config.js` file helps check your code for mistakes and keep it neat.

Here’s what it does in simple words:

* It **imports tools** to understand JavaScript, TypeScript, and React (which are used to build your app).
* It **tells the computer to ignore the `dist` folder**, which just holds built files we don’t need to check.
* It says: “Only check files that end in `.ts` or `.tsx`” — these are TypeScript files.
* It **adds rules** so your code follows good habits and works well with React.
* It **shows warnings** if you forget to do things the right way — like not exporting React parts properly.

Basically, this file helps you write clean, correct code and warns you if something looks off.


It adds rules so your code follows good habits and works well with React.

It shows warnings if you forget to do things the right way — like not exporting React parts properly.

Basically, this file helps you write clean, correct code and warns you if something looks off.
