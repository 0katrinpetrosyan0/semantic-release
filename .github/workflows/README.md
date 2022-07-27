need have NPM TOKEN in secrets 
need have GH_TOKEN / GITHUB_TOKEN in secrets
at list you need have one Release published like v0.0.1
need have package.json
1. npm install @commitlint/cli @commitlint/config-conventional --save-dev
2.npm install husky --save-dev
3.  npx husky install
4.sudo npm pkg set script.scriptname="husky install"
5.npx husky add .husky/commit-msg "npx --no -- commitlint --edit $1"
