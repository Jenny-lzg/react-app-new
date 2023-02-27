# react-app-new


npx create-react-app my-app --template typescript

<!-- npm add --dev --exact prettier -->
npm install --save-dev --save-exact prettier

# 新建配置文件
echo {}> .prettierrc.json

npx mrm lint-staged

yarn add eslint-config-prettier -D



##　commitlint
yarn add @commitlint/config-conventional @commitlint/cli -D



echo "module.exports = {extends: ['@commitlint/config-conventional']}" > commitlint.config.js

npx husky add .husky/commit-msg "yarn commitlint --edit $"