# Crontab

###  Thanks , [alseambusher/crontab-ui](https://github.com/alseambusher/crontab-ui)
<hr>

## 환경 설정에 따른 launch script
환경 변수 process.env.PORT를 지정하기 위해서는
<pre>
- windows
\>set PORT=3000
- Linux
$export PORT=3000
</pre>
과 같이 하여줌

package.json에서는
<pre>
  "scripts": {
    "start": "node app.js",
    "start:dev": "port=3000 nodemon node app.js",
    "wstart:dev": "set port=3000 && nodemon node app.js",
    "test": "node tests/test.js"
  },
</pre>
와 같이 윈도우와 리눅스에서 환경 변수를 지정하는 방법을 각각 적용한 스크립트를 생성한다

### 참고사이트
- 리눅스 크론탭(Linux Crontab) 사용법 (https://jdm.kr/blog/2)
- 리눅스 작업스케줄러 crontab 사용법 (https://server-talk.tistory.com/10)
- NPM Crontab-ui (https://www.npmjs.com/package/crontab-ui)
- reactjs-crontab (https://www.npmjs.com/package/reactjs-crontab, https://github.com/shawnscoding/reactjs-crontab)