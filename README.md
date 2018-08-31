### 콤퓨타를 항해하는 히치하이커 가이드


#### 작성방법

1. 이 레포를 fork 합니다.

2. [hugo installation](https://gohugo.io/getting-started/installing) 을 참고하여 hugo를 설치합니다.

3. fork 한 레포를 clone 합니다.

4. clone한 레포로 이동하여 다음 과정을 진행합니다.

```bash
hugo new <챕터로 쓸 폴더명>/<문서명>
# 챕터로 쓸 폴더명/문서명.md 으로 파일이 만들어집니다.
hugo server
# localhost:1313에서 확인할 수 있습니다.
git add content
git push origin master
cd _scripts
./publish.sh
```

5. 원본에 pull request 를 날립니다.
