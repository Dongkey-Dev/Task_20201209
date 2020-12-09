### Task_20201209

Task1.ipynb, Task2.ipynb 두개의 스크립트로 나뉘어져 있습니다.

Task1.ipynb 스크립트가, postgreSql에 제공된 데이터를 입력하는 스크립트이며, 

Task2.ipynb 스크립트는 Task2 과제에 사용된 스크립트 입니다.

#### Task1.ipynb

Task1.ipynb에서 사용되는 라이브러리는 다음과 같습니다.

pprint, tqdm, psycopg2, pandas, numpy, json 

[https://user-images.githubusercontent.com/57933815/101634539-354c3d80-3a6c-11eb-9475-7ce686879493.png]

위의 라이브러리 설치를 진행한 후, 코드내 첫번째 셀의 data_path를 csv 데이터 파일이 있는 디렉터리 경로로 설정하시면 됩니다.

2번쨰 셀에서 postgreSql에 연결하기위한 옵션값 (user, password, dbname) 를 로컬 pg에 맞게끔 설정하시면 됩니다.

psql 연결이 되었다면, 코드를 실행할 모든 준비가 마쳤습니다.

#### Task2.ipynb
Task1.ipynb 실행을 위해 위의 라이브러리 설치를 진행했다면, 해당 스크립트에서는 별도의 라이브러리 설치를 안해도 됩니다.

Task1.ipynb와 마찬가지로 첫번째 셀의 data_path를 데이터셋이 존재하는 디렉터리 경로로 설정하시면, 해당 코드 실행 준비가 되었습니다.

각 코드의 설명 문서는 스크립트 내의 주석과 Markdown으로 옮겼습니다.

고맙습니다.

