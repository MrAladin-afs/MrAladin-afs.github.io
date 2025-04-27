# Aladin's Portfolio

A personal portfolio website for Aladin, a FiveM Developer.

## About

This portfolio showcases Aladin's skills and experience as a FiveM Developer, including:
- Server development
- Vehicle liveries
- Peds
- EUP (Emergency Uniform Pack)
- Maps and buildings

## Development

This site is built with:
- Astro
- Tailwind CSS
- TypeScript

## Setup Instructions

1. Clone the repository
2. Install dependencies with `npm install` or `pnpm install`
3. Run the development server with `npm run dev` or `pnpm dev`
4. Build for production with `npm run build` or `pnpm build`

## Contact

For more information, contact Aladin on Discord.

## Made with ❤️ by Aladin

<p align = "center">
    <img src="public/astro-vim.png" alt="logo" width="200"/>
</p>

## 〔ℹ〕 About

This project is refactored from the original [**dev-portfolio**](https://github.com/Smilesharks/dev-portfolio) project, thanks for his work.

I also implemented and improved this neovim mode [**neovim-porfolio**](https://github.com/albertoperdomo2/astro-vim)
![](public/demo.gif)

## 🛠️ Stack

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.
- [**TailwindCSS**](https://tailwindcss.com/) - Utility-first CSS framework.
- [**Iconify**](https://iconify.design/) - Icon library.
- [**FancyBox**](https://fancyapps.com/fancybox/3/) - Image viewer.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Dropdown menu with keyboard shortcuts made in pure JavaScript.

## 🚀 Getting Started

### 0. One-click to deploy on Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ArielFalcon/portfolio&project-name=portfolio&repository-name=portfolio)

Modify the `cv.json` file to update your portfolio information.

### 1. Use this Repo as an Astro Project Template 

- I use [pnpm](https://pnpm.io/installation) as my package manager.

# Initialize the project
```bash
pnpm create astro@latest --template ArielFalcon/portfolio
```

### 1-1. Clone the repo
If you don't want to use the template command, you can clone this repo and install the dependencies.

```bash
git clone https://github.com/ArielFalcon/portfolio.git
cd portfolio
pnpm install
```

### 2. Add Your Content:

Edit the `cv.json` file to customize your portfolio content.

### 3. Launch the Development Server:

```bash
# Enjoy the results
pnpm dev
```
1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result 🚀

### 4. Customisable colours:
Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber, pink and default, with its variants in dark mode, or create your own.

## 🧞 Commands

|     | Command         | Action                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` or `start` | Launches a local development server at `localhost:4321`.                   |
| ⚙️  | `build`         | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`       | Local preview at `localhost:4321`                                       |
| 📦  | `deploy:vercel`         | Deploy on Vercel.                           |
| 📦 | `deploy:cloudflare`       | Deploy on Cloudflare, please run `wrangler login` first.                                           |
