# 🌟 Social Media Scheduler 🌟

A comprehensive social media scheduler that allows users to manage and schedule posts for multiple social media platforms from a single dashboard. 🚀

With this app, you can easily integrate with popular platforms like **Twitter**, **Facebook**, **Instagram**, **LinkedIn**, **YouTube**, **Pinterest**, and more! 🔗

## 🛠️ Features

- **📱 Multiple Social Media Integrations**: Manage and post content on platforms like **Twitter**, **Facebook**, **Instagram**, **LinkedIn**, **YouTube**, **Pinterest**, and more.
- **⏰ Post Scheduling**: Schedule your posts for future dates and times on supported platforms.
- **🔐 OAuth Authentication**: Secure login and authentication for each platform via OAuth.
- **📊 Analytics**: Track engagement, likes, shares, and other metrics for your posts.
- **🌍 Multi-platform Support**: Post to multiple social media accounts simultaneously.
- **📋 User Dashboard**: Centralized dashboard to manage all your social media posts.

## 📌 Supported Platforms

- **🐦 Twitter**
- **📘 Facebook** (Pages, Groups)
- **📸 Instagram** (Business Accounts)
- **🔗 LinkedIn**
- **📺 YouTube**
- **📌 Pinterest**
- **💬 WhatsApp** (Business API)
- **📱 Telegram** (Bot API)
- **👾 Reddit**
- **💼 Slack**
- **🎵 Spotify**
- **🎮 Twitch**

## 📋 Prerequisites

Before you start using the Social Media Scheduler, make sure you have:

- **Node.js** (version 14 or higher)
- **npm** (Node package manager)
- **Social Media Developer Accounts** for OAuth authentication.
- API keys and credentials for each social media platform you wish to integrate.

## 🚀 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/rajansharmax/Social-Scheduler.git
cd Social-Scheduler
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the root directory and add the following environment variables for the API keys and OAuth credentials for each platform:

```bash
TWITTER_API_KEY=your_twitter_api_key
TWITTER_API_SECRET_KEY=your_twitter_api_secret
TWITTER_ACCESS_TOKEN=your_twitter_access_token
TWITTER_ACCESS_SECRET=your_twitter_access_secret

FB_APP_ID=your_facebook_app_id
FB_APP_SECRET=your_facebook_app_secret
FB_ACCESS_TOKEN=your_facebook_access_token

INSTAGRAM_ACCESS_TOKEN=your_instagram_access_token
INSTAGRAM_PAGE_ID=your_instagram_page_id

LINKEDIN_CLIENT_ID=your_linkedin_client_id
LINKEDIN_CLIENT_SECRET=your_linkedin_client_secret
LINKEDIN_USER_ID=your_linkedin_user_id

# Add more platform-specific variables as needed
```

### 4️⃣ Run the application

```bash
npm run dev
```

This will start the development server at `http://localhost:3000`. 🎉

## 📌 How to Use

### 1️⃣ **Authenticate with Social Media Platforms**
   - Click on **Login** to authenticate your social media accounts. OAuth will handle authentication, and you'll be able to grant necessary permissions for posting and managing content. 🔐

### 2️⃣ **Create a Post**
   - After logging in, you'll be redirected to the dashboard. Click on **Create Post** to compose your message, select the platform(s) where you want to post, and schedule your post. ✏️

### 3️⃣ **Schedule Posts**
   - Set the date and time for your post to go live.
   - You can post immediately or choose a future time. ⏳

### 4️⃣ **View Scheduled Posts**
   - All your scheduled posts will appear on the **Scheduled Posts** page. You can edit, reschedule, or delete them as needed. 🗓️

### 5️⃣ **Analytics**
   - Track the performance of your posts across platforms, including likes, shares, and comments. 📊

## 🤝 Contributing

We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request with your changes. 🚀

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to your branch (`git push origin feature-name`).
6. Create a new pull request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 🔓

## 💖 Acknowledgements

- **🐦 Twitter API**: [Twitter Developer](https://developer.twitter.com/en/docs)
- **📘 Facebook Graph API**: [Facebook Developer](https://developers.facebook.com/docs/graph-api)
- **📸 Instagram Graph API**: [Instagram Developer](https://developers.facebook.com/docs/instagram-api)
- **🔗 LinkedIn API**: [LinkedIn Developer](https://www.linkedin.com/developers/)
- **📺 YouTube Data API**: [YouTube Developer](https://developers.google.com/youtube/v3)
- **📌 Pinterest API**: [Pinterest Developer](https://developers.pinterest.com/docs/getting-started/)
- **📱 Telegram Bot API**: [Telegram Developer](https://core.telegram.org/bots/api)
- **💬 WhatsApp Business API**: [WhatsApp Developer](https://www.whatsapp.com/business/api)
- **💼 Slack API**: [Slack Developer](https://api.slack.com/)
- **🎵 Spotify API**: [Spotify Developer](https://developer.spotify.com/documentation/web-api/)
- **🎮 Twitch API**: [Twitch Developer](https://dev.twitch.tv/docs)

---

## 💻 Author

**Rajan Sharma**  
Founder & CEO at [BitBrew Labs](https://bitbrewlabs.com)  
📧 [Email](mailto:rajansharmaa46@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/rajansharmax/) | [Twitter](https://twitter.com/rajansharmax) | [GitHub](https://github.com/rajansharmax) | [Instagram](https://www.instagram.com/rajansharma.x) | [Portfolio](https://github.com/rajansharmax/Portfolio)  
