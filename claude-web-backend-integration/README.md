# 🌐 Claude Website

Welcome! This website was built with the help of **Claude**, an AI assistant, and uses **Smartformify** to handle and save form responses — like contact forms or signup forms — without needing any complicated setup.

You don't need to know any technical terms to use or maintain this project. This guide will walk you through everything in plain, simple language.

---

## 📖 Overview

This website was generated using **Claude (an AI assistant)**, which created the design and layout for you.

To handle forms — such as a "Contact Us" form or a "Sign Up" form — the website uses a tool called **Smartformify**. Smartformify's job is simple: whenever someone fills out a form on your website, it collects that information and saves it for you to view later.

You don't need to set up a database, write server code, or manage anything technical. Smartformify takes care of all of that behind the scenes.

---

## 🧩 How It Works (In Simple Terms)

Normally, handling form submissions requires building a whole system to store and manage messages — which can be complex and technical.

Instead, this website skips all that complexity. Here's the simple version:

- Your website has a form (for example, a contact form).
- When someone submits that form, it sends the information straight to Smartformify.
- It does this using a special link called an **Endpoint URL** — think of it as a "delivery address" that tells the form where to send the responses.
- Smartformify receives the submission and stores it safely for you to check anytime.

That's it — no complicated setup needed!

---

## 🛠️ Step-by-Step Setup Guide

Follow these simple steps to get your forms working:

### Step 1: Create a Free Smartformify Account
Go to the Smartformify website and sign up for a free account. This only takes a minute.

### Step 2: Create a New Form (Endpoint)
- Log in to your Smartformify dashboard.
- Create a new form/endpoint.
- Smartformify will give you a **unique Endpoint URL**. This is the "delivery address" mentioned earlier.

### Step 3: Connect the Endpoint URL to Your Website
- Open your website's form code.
- Paste your Endpoint URL into the form's `action` attribute, like this:

```html
<form action="YOUR_ENDPOINT_URL" method="POST">
```

- Replace `YOUR_ENDPOINT_URL` with the actual link Smartformify gave you.
- Save your changes.

✅ That's it! Your form is now connected and ready to collect responses.

---

## 📬 Viewing Responses

Once your form is connected, here's what happens:

- Whenever a visitor fills out and submits a form on your website, their response is sent directly to Smartformify.
- You can log in to your **Smartformify dashboard** at any time to see all the submissions.
- No extra tools, downloads, or technical steps are needed — everything is organized for you automatically.

---

## 🙏 License / Credits

- 🎨 **Website Design & Layout** — Created with the help of **Claude**, an AI assistant by Anthropic.
- 📮 **Form Handling & Storage** — Powered by **Smartformify**, which securely collects and stores all form submissions.

Thank you for using this project! If you have any questions about updating the website or managing your forms, feel free to revisit this guide anytime.
