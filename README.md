### 고려대학교 컴퓨터정보통신대학원 빅데이터융합학과 - 빅데이터와 정보검색
#### Elasticsearch 기반의 문서 검색 시스템 구축

##### 실행환경
- Amazon Linux 2 AMI (HVM), SSD Volume Type / t2.medium
- Elasticsearch 7.12.1 / Kibana 7.12.1
- Python 3.x

###### 구현
1) 데이터 셋
- 한글 뉴스 위키 덤프 파일(http://dumps.wikimedia.org/kowiki) 다운로드
- http://dumps.wikimedia.org/kowiki/latest/kowiki-latest-pages-articles.xml.bz2


2) WikiExtractor
- https://github.com/attardi/wikiextractor


3) Elasticsearch 구축
- AWS EC2 Instance(t2.medium)
- Elasticsearch 7.12.1 (3.36.67.129:9200)
- Kibana 7.12.1 (3.36.67.129:5601)
 
 
4) Elasticsearch ↔ Python(Jupyter)
- pip install elasticsearch
 
 
5) 데이터 적재/인덱싱(색인) 및 확인
- Python code 참조
- 데이터 확인(Python 및 Kibana Discover, Dev Tools)


6) 데이터 검색(BM25)
- 데이터 검색(Python 및 Kibana Discover, Dev Tools)

