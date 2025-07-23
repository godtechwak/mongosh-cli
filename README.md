# Setup
홈 디렉터리에 .mongosh 디렉터리를 만들고, commands.js  파일을 생성한다.
```bash
$ vi .mongosh/commands.js
```
홈 디렉터리에 .mongoshrc.js 를 만들고 다음과 같이 load 한다.
```bash
$ vi .mongoshrc.js
load("<home dir>/.mongosh/commands.js")
```
