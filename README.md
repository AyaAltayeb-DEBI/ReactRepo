# ReactRepo
- The purpose of this repository is to help me keep the learnt features in one pool.
- Feel free to explore the repo and use the features.
- The steps to create a deployed app are:
  - First, I have created new repository over github.
  - Then, cloned it locally.
  - After that, a react app is created using `npx create-react-app  react-repo` as I installed it previously in my machine.
  - Then, use the command `npm i gh-pages --save-dev`  to install github pages module.
  - In the json.package:
    - "homepage": "http://AyaAltayeb-DEBI.github.io/ReactRepo"
    - In the same file under the scripts
      - `"predeploy":"npm run build"`
      - `"deploy":"gh-pages -d build"`
- Other guides in this link and this video
- https://github.com/gitname/react-gh-pages
- https://www.youtube.com/watch?v=4G6O0BIoq6M
- https://dev.to/collegewap/how-to-deploy-react-application-to-github-pages-41f7
- Do not forget to sign in:
  `git config --global user.email "you@example.com"
  git config --global user.name "Your Name"`
