# Connect Your Claude AI-Built Website Forms to Smartformify

> Turn a contact or inquiry form into a working form in just a few minutes.

## Overview

This website was created with the help of an AI assistant, such as Claude or Codex. Its design and pages are ready, but its contact form still needs a destination for visitor messages.

**Smartformify** provides that destination. Once connected, form submissions are received and stored in your Smartformify dashboard, where you can review and manage them.

## Before and After

### Before setup: form error

Before the form is connected, clicking **Submit** may show an error, do nothing, or fail to send the visitor's message.

[![Form submission error](./assets/form-error.jpg)](./assets/form-error.jpg)

### After setup: successful submission

Once connected to Smartformify, visitors can submit messages and see a confirmation. Each submission is saved in your Smartformify dashboard.

[![Form submission success](./assets/form-success.png)](./assets/form-success.png)

## Step-by-Step Setup Guide

### Step 1: Create a free Smartformify account

[Create your Smartformify account](https://www.smartformify.com/signup)

After signing up, you will have access to your dashboard, where your endpoints and responses are managed.

[![Smartformify signup page](./assets/signup.png)](./assets/signup.png)

### Step 2: Create an endpoint and copy its URL

After logging in:

1. Open your **Smartformify Dashboard**.
2. Select **Create an Endpoint**.
3. Give the endpoint a name.
4. Save it.
5. Copy the **Endpoint URL**.

The Endpoint URL is the address your website uses to send visitor messages.

#### Dashboard

[![Smartformify dashboard](./assets/dashboard.png)](./assets/dashboard.png)

#### Endpoint URL

[![Endpoint URL section](./assets/endpoint-url.png)](./assets/endpoint-url.png)

### Step 3: Connect your website form

Choose the option that feels most comfortable for you.

#### Option A: Connect manually

Replace your form's `action` value with the Smartformify Endpoint URL you copied:

```html
<form action="YOUR_SMARTFORMIFY_ENDPOINT_URL" method="POST">
```

Save your website after making the change.

#### Option B: Connect using AI

If you would rather not edit the code yourself, open your AI assistant and use the instructions shown below.

##### AI prompt

[![Instructions for connecting with an AI assistant](./assets/ai-prompt.png)](./assets/ai-prompt.png)

Your AI assistant can then update the form connection for you.

## View Your Form Responses

Whenever someone submits your website form, Smartformify saves the message in your dashboard. You can use it to:

- View contact form submissions
- Read visitor messages
- Organize responses
- Track new inquiries
- Manage your website forms in one place

[![Responses dashboard](./assets/response-dashboard.png)](./assets/response-dashboard.png)

## You're All Set

Your website is ready to receive visitor messages. Each form submission will be sent to Smartformify, where you can view and manage responses from your dashboard.

Happy building!
