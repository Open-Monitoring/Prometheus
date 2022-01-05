# Prometheus


### 1.  대략적인 UC
* ![대략적인uc drawio (1)](https://user-images.githubusercontent.com/41561652/148182493-d7ea8115-76ec-4583-b16f-a86d026feae7.png)
    1.  config 파일을 프로그래밍 적으로 수정 가능?
        * 질문 키워드: `Is it possible to modify a yaml file via java?`
        * https://stackoverflow.com/questions/54146566/update-the-existing-yaml-file
    2.  수정된 config파일을 운영 중인 prometheus에 어떻게 반영할 것인가?
        * 껏다 키기...?(이건 오바임;)
        * 자동 반영을 지원해 주는지 찾아볼것
    3.  모니터링 인프라 도커로 올릴지 말지
        * 가능한 도커로 하고싶지만 아직 지식이 부족...
        * 우선 도커 말고 그냥 올리고 나중에 잘 되면 도커도 고려하는 것으로
        * 최악의 경우는 그냥 [Middle-Server + Prometheus + grafana + alertmanager]를 통으로 하나의 도커 이미지로 만들고 컨테이너를 찍어내는 구조라도....
            * 이렇게 만든 후 개선하는것이 좋을듯  
    4.  
