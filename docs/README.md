# 🧊 Frosti

[![license](https://badgen.net/github/license/EveSunMaple/Frosti)](https://github.com/EveSunMaple/Frosti/blob/main/LICENSE)&nbsp;&nbsp;&nbsp;[![release](https://badgen.net/github/release/EveSunMaple/Frosti)](https://github.com/EveSunMaple/Frosti/releases)&nbsp;&nbsp;&nbsp;[![stackblitz](https://developer.stackblitz.com/img/open_in_stackblitz_small.svg)](https://stackblitz.com/github/EveSunMaple/Frosti)

<pre align="center">
A simple, elegant, and fast static blog template! 🚀 Built with Astro
</pre>

[**🖥️ Frosti Demo**](https://frosti.saroprock.com/)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**🌏 Chinese README**](https://github.com/Aurora-Yinph/Frosti/blob/main/docs/README.zh-CN.md)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**❤️My Blog**](https://yinph-blog.netlify.app/)

> [!TIP]
> It is recommended to preview this theme first

## 🖥️ Preview

![view](https://pic.imgdb.cn/item/6725cbacd29ded1a8c6a9b4d.png)

## ✨ Features

- ✅ Ultra-fast access speed and excellent SEO
- ✅ View transition animations (using Swup)
- ✅ You can search your articles (using pagefind)
- ✅ **Day** / **Night** mode available
- ✅ Comment system built with [Waline](https://waline.js.org/)
- ✅ Responsive design built with [Tailwind CSS](https://tailwindcss.com/) and [daisyUI](https://daisyui.com/)
- 🛠️ Easy-to-use blog
  - Installation requires just one command
  - Customize your blog content in `consts.ts`

> [!IMPORTANT]
> You need to configure the comment system yourself, see [Waline](https://waline.js.org/) for details on modifying `src\components\CommentWaline.astro`

## ✒️ Article Information

|    Name     |      Meaning       | Required |
| :---------: | :----------------: | :------: |
|    title    |   Article title    |   Yes    |
| description |  Article summary   |   Yes    |
|   pubDate   |    Article date    |   Yes    |
|    image    |   Article cover    |    No    |
| categories  | Article categories |    No    |
|    tags     |    Article tags    |    No    |
|    badge    |   Article badge    |    No    |

> [!TIP]
> You can pin your article by setting the `badge` attribute to `Pin`

## ⬇️ Usage

> [!IMPORTANT]
> Frosti uses pnpm as the package manager. If you don’t have pnpm installed, please install it first.

Use Frosti by passing the `--template` parameter to the `create astro` command!

```sh
pnpm create astro@latest -- --template EveSunMaple/Frosti
```

<details>
  <summary><h3>Encountering Issues? Build by Cloning This Repository!</h3></summary>

1. Install the pnpm package manager

```sh
npm i -g pnpm
```

2. Clone the project

```sh
git clone --depth 1 https://github.com/EveSunMaple/Frosti.git Frosti
```

3. Enter the project folder

```sh
cd Frosti
```

4. Install dependencies

```sh
pnpm i
```

5. Debug and run the project

```sh
pnpm run dev # Start the debug server

pnpm run build # Build the project as static files
```

</details>

> [!NOTE]
> Frosti is built using pnpm by default. If you encounter any errors, please run `pnpm update`.

> [!TIP]
> You can also deploy Frosti using other methods such as Vercel, Netlify, etc. However, you need to be familiar with the basic usage of these services.
> [Astro-supported deployment methods](https://docs.astro.build/zh-cn/guides/deploy/)

## 🎯 Roadmap

- [ ] Attempt to integrate a headless CMS
- [ ] Fix known style bugs
- [ ] More...

## 👀 Issues

If you have any questions or suggestions, feel free to submit an issue or communicate with the developers!

## 🎉 Thanks

@[Saicaca](https://github.com/saicaca) His inspiration was the main reason I created this theme

@[WRXinYue](https://github.com/WRXinYue) Helped me a lot during my early days
