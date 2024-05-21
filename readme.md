<h1 align="center">Hugo + Tailwind CSS Starter and Boilerplate</h1>

<p align="center">pres-ber-blog is a personal blog built with Hugo and TailwindCSS.</p>

<p align="center">Made with ♥ by <a href="https://digitalmast.tech/"> DigitalMast</a></p>
<p align=center> If you like this project, please give it a ⭐ to show your support.</p>

<!-- <h2 align="center"> <a target="_blank" href="https://zeon.studio/preview?project=hugoplate" rel="nofollow">👀 Demo</a> | <a  target="_blank" href="https://pagespeed.web.dev/analysis/https-hugoplate-netlify-app/6lyxjw6t4r?form_factor=desktop">Page Speed (95+)🚀</a>
</h2> -->

<p align="center">
  <a href="https://github.com/gohugoio/hugo/releases/tag/v0.126.0" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=min-HUGO-version&message=0.126.0&color=f00&logo=hugo" />
  </a>

  <a href="https://github.com/DigitalMast/pres-ber-blog/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/DigitalMast/pres-ber-blog" alt="license">
  </a>

  <a href="https://github.com/DigitalMast/pres-ber-blog">
    <img src="https://img.shields.io/github/languages/code-size/DigitalMast/pres-ber-blog" alt="code size">
  </a>

  <a href="https://github.com/DigitalMast/pres-ber-blog/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/DigitalMast/pres-ber-blog" alt="contributors">
  </a>
</p>

## 🎁 What's Included

### 📌 Technical Features

- 👥 Multi-Authors
- 🎯 Similar Posts Suggestion
- 🔍 Search Functionality
- 🌑 Dark Mode
- 🏷️ Tags & Categories
- 🔗 Netlify
- 📞 Support contact form
- 📱 Fully responsive
- 📝 Write and update content in Markdown
- 💬 Disqus Comment
- 🔳 Syntax Highlighting

### 📄 15+ Pages

- 🏠 Homepage
- 👤 About
- 📞 Contact
- 👥 Authors
- 👤 Author Single
- 📝 Blog
- 📝 Blog Single
- 🚫 Custom 404
- 💡 Elements
- 📄 Privacy Policy
- 🏷️ Tags
- 🏷️ Tag Single
- 🗂️ Categories
- 🗂️ Category Single
- 🔍 Search

### 📦 Tech Stack

- [Hugo](https://gohugo.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PostCSS](https://postcss.org/)
- [PurgeCSS](https://purgecss.com/)
- [AutoPrefixer](https://autoprefixer.github.io/)
- [Hugo Modules](https://gohugo.io/hugo-modules/) by [Gethugothemes](https://gethugothemes.com/hugo-modules)
- [Markdown](https://markdownguide.org/)
- [Prettier](https://prettier.io/)
- [Jshint](https://jshint.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

---

## 🚀 Running Locally

First you need to [clone](https://github.com/preston-bernstein/pres-ber-blog) or [download](https://github.com/preston-bernstein/pres-ber-blog/archive/refs/heads/main.zip) the repository.

### ⚙️ Prerequisites

To start using this site locally, you need to have some prerequisites installed on your machine.

- [Hugo Extended v0.124+](https://gohugo.io/installation/)
- [Node v20+](https://nodejs.org/en/download/)
- [Go v1.22+](https://go.dev/doc/install)

### 👉 Project Setup

Please use this custom script to make the project setup easier. It will create a new Hugo theme folder, and clone the Hugoplate theme into it. Then move the exampleSite folder into the root directory. So that you can start your Hugo server without going into the exampleSite folder. Use the following command to setup your project.

```bash
npm run project-setup
```

### 👉 Install Dependencies

Install all the dependencies using the following command.

```bash
npm install
```

### 👉 Development Command

Start the development server using the following command.

```bash
npm run dev
```

---

## 📝 Customization

This template has been designed with a lot of customization options in mind. You can customize almost anything you want, including:

### 👉 Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### 👉 Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### 👉 Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

### 👉 Social Links

You can change the social links from the `data/social.json` file. Add your social links here, and they will automatically be displayed on the site.

---

## 🛠 Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### 👉 Update Theme

If you want to update the theme, then you can use the following command. It will update the theme to the latest version.

```bash
npm run update-theme
```

> **Note:** This command will work after running `project-setup` script.

### 👉 Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### 👉 Remove Dark Mode

If you want to remove dark mode from your project, you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

> **Note:** This command will work before running `project-setup` script. If you already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. afterward, you can run `npm run project-setup` again.

---

## 🚀 Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere. Let's see the process:

### 👉 Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### 👉 Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

---

## 🔒 Guide to Staying Compliant

### 🐞 Reporting Issues

We use GitHub Issues as the official bug tracker for this Template. Please Search [existing issues](https://github.com/DigitalMast/pres-ber-blog/issues). It’s possible someone has already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new issue](https://github.com/DigitalMast/pres-ber-blog/issues).

### 📝 License

Copyright (c) 2024 - Present, Designed, Developed, and Maintained by [DigitalMast](https://digitalmast.tech/)

**Code License:** Released under the [CC BY-NC-ND](https://github.com/DigitalMast/pres-ber-blog/blob/main/LICENSE) license.
