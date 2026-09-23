# Lazarev ✨

A front-end rebuild of the Lazarev agency website, made to practice scroll-driven animation and layout work. Plain HTML, CSS and JavaScript on the base, with GSAP handling the motion and Locomotive Scroll handling the smooth scrolling.

Live site: [lazarev-replica.vercel.app](https://lazarev-replica.vercel.app)

This is a learning project. The design belongs to the original Lazarev team, and I rebuilt it to see how that kind of polish is put together.

## Preview

<img width="1920" height="1080" alt="Screenshot 2026-09-24 012153" src="https://github.com/user-attachments/assets/d0370c3a-902e-47d9-8419-e579ae11b73c" />
<hr>
<img width="1920" height="1080" alt="Screenshot 2026-09-24 012206" src="https://github.com/user-attachments/assets/c24a8ff1-8f4d-40d2-94c5-c94100f5a0b5" />
<hr>
<img width="1920" height="1080" alt="Screenshot 2026-09-24 012246" src="https://github.com/user-attachments/assets/e4f84d46-cbe4-4d3d-8aed-aa02ef874b2d" />
<hr>
<img width="1920" height="1080" alt="Screenshot 2026-09-24 012302" src="https://github.com/user-attachments/assets/6aaee9ba-1d98-416a-9d8d-4a4a1b59cca3" />


## Used technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![Locomotive Scroll](https://img.shields.io/badge/Locomotive_Scroll-000000?style=for-the-badge)

## How the pieces fit

```mermaid
flowchart LR
    A["index.html"] --> B["style.css<br/>layout and styling"]
    A --> C["script.js<br/>interactions"]
    A --> D["Assets<br/>SVG icon, play button"]
    C --> E["Locomotive Scroll<br/>smooth scrolling"]
    C --> F["GSAP<br/>animations"]
    B --> G["Rendered page"]
    E --> G
    F --> G
    D --> G
```

## Project files

```
Lazarev-Replica/
├── index.html                       # page markup
├── style.css                        # all styling
├── script.js                        # GSAP and Locomotive Scroll setup
├── arrow-up-right-svgrepo-com.svg   # arrow icon
└── play-button.png                  # play button image
```

## Running it locally

There's no build step. Clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/Bikram-sGit00/Lazarev-Replica.git
cd Lazarev-Replica
```

Smooth scrolling libraries can act up when a page is opened straight from disk, so if something looks off, serve the folder instead. The Live Server extension in VS Code works, or from the terminal:

```bash
# starts a local server at http://localhost:8000
python -m http.server 8000
```


