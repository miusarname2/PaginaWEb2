# PaginaWEb2
## English

This web project, created with HTML, CSS, and JavaScript, represents my foray into more dynamic projects. Although basic, it symbolizes my progress in integrating interactivity into web development. 🌐💻 #DynamicWebProject


### Features

- Multi-section page.
- Image gallery with light effect.
- Dropdown navigation menu.

### Installation

Clone the repository from GitHub

```bash
git clone https://github.com/miusarname/PaginaWEb2.git
cd PaginaWEb2
```

### Quick Start

Simply open the HTML files in your browser.

### Screenshots

![App Screenshot](https://github.com/miusarname/assets/blob/main/Screenshot%202024-01-20%20153300.png)

### Technologies

- HTML
- CSS
- JavaScript

### Featured Code

#### Dropdown Menu (JavaScript)

```javascript
const hamburger = document.querySelector('.hamburger');
const menu = document.querySelector('.menu-nav');

hamburger.addEventListener('click', () => {
    menu.classList.toggle("spread");
});

window.addEventListener('click', e => {
    if (menu.classList.contains('spread') && e.target != menu && e.target != hamburger) {
        menu.classList.toggle("spread");
    }
});
```

#### Image Gallery (JavaScript)

```javascript
const images = document.querySelectorAll('.img-gallery');
const lightboxImage = document.querySelector('.add-image');
const lightboxContainer = document.querySelector('.image-light');

images.forEach(image => {
    image.addEventListener("click", () => {
        showImage(image.getAttribute('src'));
    });
});

lightboxContainer.addEventListener('click', (e) => {
    if (e.target !== lightboxImage) {
        lightboxContainer.classList.toggle(`show`);
        lightboxImage.classList.toggle("showImage");
        hamburger1.style.opacity = "1";
    }
});

const showImage = (image) => {
    lightboxImage.src = image;
    lightboxContainer.classList.toggle(`show`);
    lightboxImage.classList.toggle("showImage");
    hamburger1.style.opacity = "0";
};
```

### About the Project

This web project, created with HTML, CSS, and JavaScript, represents my foray into more dynamic projects. Although basic, it symbolizes my progress in integrating interactivity into web development. 🌐💻 #DynamicWebProject

### License

[MIT](https://choosealicense.com/licenses/mit/)

### Author

- [@miusarname](https://www.github.com/miusarname)

### Feedback

If you have any comments or suggestions, feel free to contact me through my GitHub profile.


## 动态Web项目
## Chinese (Simplified)

这个使用HTML、CSS和JavaScript创建的Web项目代表了我对更动态项目的尝试。虽然基本，但它象征着我在将互动性整合到Web开发中的进展。 🌐💻 #动态Web项目


### 特点

- 多节页面。
- 具有光效的图库。
- 下拉导航菜单。

### 安装

从GitHub克隆存储库

```bash
git clone https://github.com/miusarname/PaginaWEb2.git
cd PaginaWEb2
```

### 快速入门

只需在浏览器中打开HTML文件。

### 截图

![App Screenshot](https://github.com/miusarname/assets/blob/main/Screenshot%202024-01-20%20153300.png)

### 技术

- HTML
- CSS
- JavaScript

### 精选代码

#### 下拉菜单 (JavaScript)

```javascript
const hamburger = document.querySelector('.hamburger');
const menu = document.querySelector('.menu-nav');

hamburger.addEventListener('click', () => {
    menu.classList.toggle("spread");
});

window.addEventListener('click', e => {
    if (menu.classList.contains('spread') && e.target != menu && e.target != hamburger) {
        menu.classList.toggle("spread");
    }
});
```

#### 图库 (JavaScript)

```javascript
const images = document.querySelectorAll('.img-gallery');
const lightboxImage = document.querySelector('.add-image');
const lightboxContainer = document.querySelector('.image-light');

images.forEach(image => {
    image.addEventListener("click", () => {
        showImage(image.getAttribute('src'));
    });
});

lightboxContainer.addEventListener('click', (e) => {
    if (e.target !== lightboxImage) {
        lightboxContainer.classList.toggle(`show`);
        lightboxImage.classList.toggle("showImage");
        hamburger1.style.opacity = "1";
    }
});

const showImage = (image) => {
    lightboxImage.src = image;
    lightboxContainer.classList.toggle(`show`);
    lightboxImage.classList.toggle("showImage");
    hamburger1.style.opacity = "0";
};
```

### 关于项目

这个使用HTML、CSS和JavaScript创建的Web项目代表了我对更动态项目的尝试。虽然基本，但它象征着我在将互动性整合到Web开发中的进展。 🌐💻 #动态Web项目

### 许可证

[MIT](https://choosealicense.com/licenses/mit/)

### 作者

- [@miusarname](https://www.github.com/miusarname)

### 反馈

如果您有任何意见或建议，请随时通过我的GitHub个人资料与我联系。


## ダイナミックWebプロジェクト
## Japanese

このHTML、CSS、およびJavaScriptで作成されたWebプロジェクトは、よりダイナミックなプロジェクトに初めて挑戦するものです。基本的ではありますが、Web開発に対するインタラクティビティの統合における私の進歩を象徴しています。 🌐💻 #ダイナミックWebプロジェクト


### 特徴

- 複数のセクションを持つページ。
- ライトエフェクトを備えた画像ギャラリー。
- ドロップダウンナビゲーションメニュー。

### インストール

GitHubからリポジトリをクローンします

```bash
git clone https://github.com/miusarname/PaginaWEb2.git
cd PaginaWEb2
```

### クイックスタート

単にHTMLファイルをブラウザで開きます。

### スクリーンショット

![App Screenshot](https://github.com/miusarname/assets/blob/main/Screenshot%202024-01-20%20153300.png)

### 技術

- HTML
- CSS
- JavaScript

### 注目のコード

#### ドロップダウンメニュー（JavaScript）

```javascript
const hamburger = document.querySelector('.hamburger');
const menu = document.querySelector('.menu-nav');

hamburger.addEventListener('click', () => {
    menu.classList.toggle("spread");
});

window.addEventListener

('click', e => {
    if (menu.classList.contains('spread') && e.target != menu && e.target != hamburger) {
        menu.classList.toggle("spread");
    }
});
```

#### 画像ギャラリー（JavaScript）

```javascript
const images = document.querySelectorAll('.img-gallery');
const lightboxImage = document.querySelector('.add-image');
const lightboxContainer = document.querySelector('.image-light');

images.forEach(image => {
    image.addEventListener("click", () => {
        showImage(image.getAttribute('src'));
    });
});

lightboxContainer.addEventListener('click', (e) => {
    if (e.target !== lightboxImage) {
        lightboxContainer.classList.toggle(`show`);
        lightboxImage.classList.toggle("showImage");
        hamburger1.style.opacity = "1";
    }
});

const showImage = (image) => {
    lightboxImage.src = image;
    lightboxContainer.classList.toggle(`show`);
    lightboxImage.classList.toggle("showImage");
    hamburger1.style.opacity = "0";
};
```

### プロジェクトについて

このHTML、CSS、およびJavaScriptで作成されたWebプロジェクトは、よりダイナミックなプロジェクトに初めて挑戦するものです。基本的ではありますが、Web開発に対するインタラクティビティの統合における私の進歩を象徴しています。 🌐💻 #ダイナミックWebプロジェクト

### ライセンス

[MIT](https://choosealicense.com/licenses/mit/)

### 作者

- [@miusarname](https://www.github.com/miusarname)

### フィードバック

何かコメントや提案があれば、私のGitHubプロフィールを通じてお気軽にお知らせください。
