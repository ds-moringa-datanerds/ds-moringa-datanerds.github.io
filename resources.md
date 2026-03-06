---
layout: default
title: Resources
---

<h1>Resources & Setup</h1>
<p>Everything you need to get started and stay on track.</p>

<div class="card-grid">
  <div class="card">
    <h3>Canvas LMS</h3>
    <p>Your source of truth for all course content, assignments, grades, and announcements.</p>
    <a href="#">Access Canvas →</a>
  </div>
  <div class="card">
    <h3>Mattermost</h3>
    <p>Our primary communication channel. Ask questions, share wins, get help from peers and instructors.</p>
    <a href="https://baraza.moringaschool.com/login">Open Mattermost →</a>
  </div>
</div>

<details>
  <summary>How to connect to Mattermost</summary>
  <div class="details-content">
    <ol>
      <li>Go to <a href="https://baraza.moringaschool.com/login">baraza.moringaschool.com/login</a> and create your account</li>
      <li>Download the desktop or mobile app</li>
      <li>Set the server URL to: <code>https://baraza.moringaschool.com</code></li>
      <li>Set display name to: <code>moringa-classroom</code></li>
      <li>Follow <a href="#">this link (to be updated)</a> to join the class channel after signing in</li>
    </ol>
    <p>Here is a <a href="#">video guide (to be updated)</a> to walk you through the process.</p>
    <p><strong>Your active engagement matters!</strong></p>
  </div>
</details>

<h2>Environment Setup</h2>

<div class="callout callout-warning">
  <strong>Do this before your first class.</strong> Having your environment ready means you can focus on learning, not troubleshooting installations.
</div>

<h3>1. Python Installation</h3>

We recommend installing Python through **Anaconda**, which bundles Python with essential data science libraries.

1. Download Anaconda from [anaconda.com/download](https://www.anaconda.com/download)
2. Install using the default settings
3. Open **Anaconda Navigator** to verify installation
4. Launch **Jupyter Notebook** from Navigator to test

<div class="callout callout-info">
  <strong>Minimum laptop specs:</strong> Core i5 or above, 8GB RAM, 500GB storage, stable internet connection.
</div>

<h3>2. Jupyter Notebook</h3>

Jupyter comes with Anaconda. To launch it:

```
jupyter notebook
```

This opens Jupyter in your browser. Create a new Python 3 notebook to start coding.

<h3>3. Git & GitHub</h3>

1. Install Git from [git-scm.com](https://git-scm.com/)
2. Create a free account on [GitHub](https://github.com/)
3. Configure:

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

<h3>4. VS Code</h3>

1. Download from [code.visualstudio.com](https://code.visualstudio.com/)
2. Install the **Python extension**
3. Install the **Jupyter extension** for notebook support

<h2>Useful References</h2>

<div class="card-grid">
  <div class="card">
    <h3>W3Schools</h3>
    <p>Tutorials and references for Python, SQL, and web technologies.</p>
    <a href="https://www.w3schools.com/">Visit W3Schools →</a>
  </div>
  <div class="card">
    <h3>Python Documentation</h3>
    <p>The official Python reference.</p>
    <a href="https://docs.python.org/3/">docs.python.org →</a>
  </div>
  <div class="card">
    <h3>Pandas Documentation</h3>
    <p>Essential reference for data analysis with Python.</p>
    <a href="https://pandas.pydata.org/docs/">pandas.pydata.org →</a>
  </div>
</div>

<!-- <h2>Getting Help</h2>

<p>Before reaching out to an instructor, please check the <a href="{{ '/faq/' | relative_url }}">FAQ page</a> — your question may already be answered there.</p>

<p>If you're still stuck:</p>

1. Post your question on **Mattermost #module-help** with details about what you tried
2. For private or personal matters, use **Canvas Inbox**
3. For 1:1 support, check office hours announcements on Mattermost -->
<h2>Getting Help</h2>

<p>Before reaching out to an instructor, check the <a href="{{ '/faq/' | relative_url }}">FAQ page</a> — your question may already be answered there.</p>

<p>If you're still stuck:</p>

<ol>
  <li><strong>Post on the Mattermost class channel</strong> — include what you tried and any error messages. Peers and instructors respond within 24 hours on weekdays.</li>
  <li><strong>Book a session</strong> — if you need focused 1:1 help, book directly with an instructor:</li>
</ol>

<div class="card-grid">
  <div class="card">
    <h3>Bonface</h3>
    <a href="#">Book a session →{coming soon}</a>
  </div>
  <div class="card">
    <h3>Samwel</h3>
    <a href="#">Book a session →{coming soon}</a>
  </div>
  <div class="card">
    <h3>Diana</h3>
    <a href="#">Book a session →{coming soon}</a>
  </div>
</div>

<!-- <p>Replace the <code>#</code> in each link above with the actual Calendly URL for each instructor.</p> -->

<div class="callout callout-success">
  <strong>When asking for help with code:</strong> always include what you're trying to do, the code you've written, and the error message you're getting. This helps us help you faster.
</div>
