# Chatbot
This guide walks through the steps to create, configure, and deploy a chatbot using Botpress Cloud with final integration into a static HTML page using Visual Studio Code.
<br>
✅ **Step 1: Create and Configure the Bot in Botpress**
<br>
- Go to Botpress Cloud and sign in using GitHub or another method.
  <br>
- Click on **“Create Bot”**.
  <br>
- Name your bot and choose a blank or starter template.
  <br>
- Use the **Botpress Studio** to design your bot:
  <br>
  - Add flows, nodes, Q&A, and actions as needed.
    <br>
  - Test it using the in-browser emulator.
<br>
<br>
✅ **Step 2: Enable Webchat Channel**
<br>
- In the Botpress Cloud dashboard, open your bot.
  <br>
- Go to **Channels** → Select **Webchat**.
  <br>
- Toggle **Enable Webchat**.
  <br>
- Copy the <script> tags shown under **Installation** — you’ll embed these in your HTML file.
<br><br>
✅ **Step 3: Create an HTML File to Embed the Bot**
<br>
- Open **Visual Studio Code (VSC)**.
  <br>
- Create a file named "bot.html".<br>
- Paste the Webchat embed code inside the <body> tag.<br>
- Use the **Live Server** extension in VSC to preview the bot:<br>
  - Right-click the HTML file → Click **“Go Live”**.<br>
  - Your bot will appear on the page.<br>
