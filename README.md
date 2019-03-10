# command
git init
ndenv install 10.15.3
ndenv local 10.15.3
npm install textlint textlint-rule-preset-ja-technical-writing textlint-rule-preset-ja-spacing textlint-rule-prh
git submodule add https://github.com/prh/rules.git prh-rules
brew install redpen

# use redpen
redpen -c redpen-conf.xml sample.md

# vscode extensions
vscode-textlint