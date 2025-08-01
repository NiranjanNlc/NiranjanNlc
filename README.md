<h1 align="center">👋 Hi, I'm Niranjan Lamichhane</h1>
<h3 align="center">Crafting Native Android Experiences 🚀</h3>

| 📊 GitHub Activity | 📊 GitHub Stats | 📊 Languages Used | 
| --- | --- | --- | 
| ![GitHub Activity Graph](https://github-readme-streak-stats.herokuapp.com/?user=niranjannlc) | ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=niranjannlc&show_icons=true&count_private=true&include_all_commits=true) | ![Languages Used](./metrics.plugin.languages.svg) |

<!-- Alternative language stats with private repos -->
<details>
<summary>📊 Detailed Metrics (Including Private Repos)</summary>

![Metrics](./github-metrics.svg)

</details>

### 💼 Contributions

#### [Mifos Mobile](https://github.com/openMF/mifos-mobile/pulls?q=is%3Apr+author%3Aniranjannlc+is%3Aclosed) 
📱 Fixed the position of the title on the user profile screen.  
🛠 Modified the response handling for HTTP exceptions.   
🔄 Transfered the about us section into MVVM framework           
🔧 Fixed the bug of profile photo not visible after changing theme                                                                                             
🔄 Transfered the  set up UPI section from xml to jetpack compose 

#### [Mifos Mobile wallet](https://github.com/openMF/mobile-wallet/pulls?q=is%3Apr+author%3Aniranjannlc+is%3Aclosed+) 
📱  Migrated core module model from java to Kotilin data class 

#### [ODK_X Service](https://github.com/odk-x/services/pulls?q=is%3Apr+author%3Aniranjannlc+is%3Aclosed+) 
🚀 Improved test coverage for enhanced code reliability.

#### [ODK_X Android Library](https://github.com/odk-x/services/pulls?q=is%3Apr+author%3Aniranjannlc+is%3Aclosed) 
🔄 Upgraded the deprecated registry for compatibility with the latest standards and technologies.

### 🚀 Featured Projects

#### [Kotlin Quiz](https://github.com/NiranjanNlc/Kotilin-Quiz)
A quiz-taking application focused on Kotlin programming language. This project provides an interactive quiz experience to test and enhance Kotlin programming skills.

#### [Leadership Article Reader](https://github.com/NiranjanNlc/ArticleRedaer)
Utilized web view to read important articles on leadership. The Leadership Article Reader project uses a web view to allow users to read and explore insightful articles on leadership.

### 🛠 Skills

#### Programming Languages:
- 💻 Kotlin
- ☕ Java

#### Development Tools and Practices:
- 📱 Android App Development
- 🧹 Clean Code Architecture
- 🧪 Test-Driven Development (Espresso, Unit, and Integration Testing)
- 🗡 Dependency Injection (Hilt)
- 🏛 Architecture Patterns (MVVM)
- 🎨 Design Patterns (Builder, Strategy, Factory, etc.)
- 📝 Version Control (GitHub, Git, Bitbucket)

#### API and Database:
- 🚀 Restful API Architecture (Retrofit 2)
- 🚀 Firebase Integration
- 💾 Room and SQLite Database

#### Image Handling:
- 📸 Glide and Picasso Image Libraries

#### Asynchronous Programming:
- 🔄 Coroutines

### 📝 Latest Blog Post
<!-- BLOG-POST-LIST:START -->
- [Why I never returned back to windows after using linux ?](https://dev.to/niranjannlc/why-i-never-returned-back-to-windows-after-using-linux--8hh)
<!-- BLOG-POST-LIST:END --> 
### 🌐 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-niranjannlc-blue)](https://www.linkedin.com/in/niranjannlc/)
[![Twitter](https://img.shields.io/badge/Twitter-%40niranjanlc-blue)](https://twitter.com/niranjanlc)
[![Dev.to](https://img.shields.io/badge/Dev.to-niranjannlc-lightgrey)](https://dev.to/niranjannlc)

---

## 🔧 Private Repository Language Stats Setup

If you're not seeing language statistics from private repositories, here are the steps to enable them:

### Method 1: Deploy Your Own Vercel Instance

1. **Fork the repository**: Fork [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
2. **Deploy to Vercel**: 
   - Go to [Vercel](https://vercel.com/) and import your forked repository
   - Add your GitHub Personal Access Token as environment variable `PAT_1`
3. **Create PAT**:
   - Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
   - Generate new token with these scopes: `repo`, `user`, `read:user`
4. **Update URLs**: Replace `github-readme-stats.vercel.app` with your Vercel deployment URL

### Method 2: Use GitHub Actions (Recommended)

Create a workflow that generates language stats and commits them to your repo:

```yaml
# .github/workflows/update-stats.yml
name: Update GitHub Stats
on:
  schedule:
    - cron: '0 */6 * * *' # Every 6 hours
  workflow_dispatch:
jobs:
  update-stats:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Generate Language Stats
        uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: niranjannlc
          template: classic
          base: languages
          plugin_languages: yes
          plugin_languages_analysis_timeout: 15
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
```

### Current Setup
- ✅ Public repositories: Analyzed
- ⚠️ Private repositories: Requires PAT setup for full access

---

### 📬 Contact
Feel free to reach out via [email](mailto:niranjannlc@keemail.com).
