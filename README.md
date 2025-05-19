**website-chatbots** 🚀

> A showcase of two powerful Voiceflow chatbots for **customer service** and **lead generation**, **fitness motivation**—ready to import, customize and deploy.

---

<p align="center">
  <a href="#customer-service--lead-generation-bot">🛎️ Customer Service & Lead Generation Bot</a> •
  <a href="#fitness--motivation-bot">💪 Fitness & Motivation Bot</a> •
  <a href="#getting-started">⚙️ Getting Started</a> •
  <a href="#demo">🎬 Demo</a>
</p>

---

## 🛎️ Customer Service & Lead Generation Bot

**Description:**
- Automates the first touch: greets visitors, answers FAQs and provides business info.
- Captures visitor details and qualifies leads.
- Sends lead data via email using the Make API.

**Key Features:**
- 🤖 **Automated Greetings**: Warm welcome flows and guided menus.
- 📧 **Email Notification**: Seamless integration with Make (formerly Integromat) to dispatch lead intel.
- 🔍 **FAQ Handling**: Pre-built intents for common questions.

<kbd>![Customer Service Flow](images/customer_service_flow.png)</kbd>

```bash
# Import into Voiceflow
1. Clone the repo: git clone https://github.com/youruser/website-chatbots.git
2. Open Voiceflow and select "Import Project"
3. Upload `CustomerServiceLeadGen.vf` and begin customizing!
```

---

## 💪 Fitness & Motivation Bot

**Description:**
- Answers fitness-related queries and provides tailored protein intake recommendations.
- Captures lead info and stores it into Airtable via API integration.

**Key Features:**
- 🏋️ **Workout Guidance**: Pre-built flows covering workouts, nutrition and recovery.
- 🥤 **Protein Recommendations**: Fetches optimal protein intake based on BMI and user goals.
- 📊 **Airtable Integration**: Leads are saved automatically for follow-up.

<kbd>![Fitness Bot Flow](images/fitness_bot_flow.png)</kbd>

```bash
# Import into Voiceflow
1. Clone the repo: git clone https://github.com/youruser/website-chatbots.git
2. In Voiceflow, import `FitnessMotivation.vf` and connect your Airtable base!
```

---

## ⚙️ Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rayyan-shahid1/Website-Chatbots 
   ```

2. **Setup Integrations**
   - **Make API**: Create a scenario, grab the webhook URL and paste into the email step in the Customer Service flow.
   - **Airtable API**: Generate an API key, configure your base ID and table name in the Airtable block of the Fitness Bot.

3. **Customize Flows**
   - Modify intents, responses and variables in Voiceflow as needed.
   - Brand the bot with your own icons, colors and voice.

4. **Embed on Your Website**
   - Export Voiceflow project as web chat.
   - Copy-paste the provided script snippet into your site’s `<head>` section.

---

## 🎬 Demo

Try them live on our GitHub Pages demo: [https://creator.voiceflow.com/prototype/6788f526a009f3b7ee57acb7] (https://creator.voiceflow.com/prototype/68161f6d6675ec5c9d94416b))

<video src="videos/demo.mp4" controls poster="images/demo_poster.png" width="800">
Your browser does not support the video tag.
</video>

---

## 🏷️ Topics

<span><kbd>voiceflow</kbd> <kbd>chatbot</kbd> <kbd>customer-support</kbd> <kbd>lead-generation</kbd> <kbd>fitness</kbd> <kbd>airtable</kbd> <kbd>make-api</kbd></span>

---

## 🤝 Contributing

We welcome improvements, custom flows, and new templates!
1. Fork the repo.
2. Create a feature branch: `git checkout -b feature/YourFlow`.
3. Commit your changes and push.
4. Open a pull request.

---

## 📄 License

MIT © 2025 Rayyan Shahid

