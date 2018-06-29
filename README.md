npm install -g @dojo/cli
npm install -g @dojo/cli-create-app

dojo create app --name testDojo

1. Init Repo (VSCode)

2. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"testDojo"}'

3. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/testDojo.git

4. Push Origin Master
-> git push -u origin master

dojo build --mode dev --watch --serve
