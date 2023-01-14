# Writing an OS in RUST

---

Rust 프로그래밍 언어로 작은 OS 구현하기

내용 및 소스코드는 해당 [블로그](https://os.phil-opp.com/ko/)를 참고합니다.

---

qemu-system-x86_64.exe 파일 실행시 path 에러로 ```export PATH="$PATH:/c/Program Files/qemu"``` 로 직업 path 명령 후 아래 명령어 사용

```
qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin
```