## Step 1: Open the Main Project Folder

1. Open **VS Code**.
2. Go to **File > Open Folder...** and select your main Resume Analyser folder (the one that contains both the `backend` and `frontend` folders).

---

## Step 2: Start the Backend Server

1. Open the VS Code integrated terminal by pressing `` Ctrl + ` `` (the key above Tab) or clicking **Terminal > New Terminal** in the top menu.
2. Type the following command to navigate into your backend folder:

```bash
   cd backend
```

3. _(Optional but recommended)_ Just to ensure all your packages are perfectly up to date with the new code, run:

```bash
   npm install
```

4. Start the server by running:

```bash
   node server.js
```

> **Note:** You should see the message: `Server running on port 5000`. Leave this terminal open and running!

---

## Step 3: Start the Frontend

There are two ways to do this in VS Code. The "Live Server" method is the most professional and will automatically refresh your page if you make changes to the CSS or HTML.

### Method A: Using Live Server (Recommended for Presentations)

1. In VS Code, click on the **Extensions** icon on the far left panel (or press `Ctrl + Shift + X`).
2. Search for **Live Server** (by Ritwick Dey) and click **Install**.
3. Once installed, open your `frontend/index.html` file in VS Code.
4. Right-click anywhere inside the HTML code and select **Open with Live Server** (or click the **"Go Live"** button at the bottom right of the VS Code window).
5. This will automatically open your browser to a local port (usually `http://127.0.0.1:5500/frontend/index.html`).

### Method B: The Simple Way

1. Simply open your computer's File Explorer.
2. Navigate to your `frontend` folder.
3. Double-click `index.html` to open it in Chrome or Edge.

---

## Step 4: Test the Connection

Now that your browser is open and your terminal says `Server running on port 5000`, go ahead and test it:

1. Upload a sample **Resume (PDF)**.
2. Paste in your **Job Description**.
3. Click **Analyze**.

_If you check your VS Code terminal while it analyzes, you will see the server processing the request in real-time. If it succeeds, your browser UI will update with the new pie chart, insights, and expanded skills breakdown!_
