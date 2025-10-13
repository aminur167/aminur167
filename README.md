# Hi there 👋, I'm Aminur Islam

<div align="center">
  
![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Aminur%20Islam&fontSize=60&fontAlignY=35&animation=fadeIn&desc=Full%20Stack%20Developer%20%7C%20Student%20%7C%20Tech%20Enthusiast&descAlignY=55)

</div>

## 🌟 About Me

<div align="center">

```javascript
const aminur = {
  pronouns: "He" | "Him",
  code: ["HTML", "CSS", "JavaScript", "C", "C++", "Java", "Python"],
  tools: ["React", "Node.js", "Git", "GitHub", "VS Code"],
  architecture: ["MERN Stack", "Responsive Design"],
  challenge: "I'm currently working on becoming a Full Stack Developer",
  funFact: "I love turning coffee into code ☕"
};

**Instructions:**
1. Copy this entire code
2. Go to your GitHub profile
3. Create/edit `README.md` file
4. Paste this code
5. Commit changes

**Note:** Some features like Spotify, Snake animation require additional setup. But basic animations and stats will work immediately! 🚀

**For Snake Animation:** Create `.github/workflows/snake.yml` file with this content:
```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@master
        with:
          github_user_name: aminur167
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
