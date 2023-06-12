# 실행

![image](https://github.com/jaejae87/React_basic.md/assets/129706762/e956c32a-516b-480a-a290-07258dbc5319)
    
    npm i json-server
   
   
# db.json 파일 만들기  

![image](https://github.com/jaejae87/React_basic.md/assets/129706762/80009105-5969-42d1-b602-ab22905c92a6)

# db.json파일은 root에 만들어야한다.
![image](https://github.com/jaejae87/React_basic.md/assets/129706762/2039a66b-38ac-44b8-b90c-4756cc091807)

#import 
![image](https://github.com/jaejae87/React_basic.md/assets/129706762/ff92e877-f567-40e9-a8ed-ec9f8543dc85)

# db.json 실행하기  
 ![image](https://github.com/jaejae87/React_basic.md/assets/129706762/556976ca-6827-4fdd-9bf4-4ce1835da6f7)
 
 # 위와 같이 실행하면  port를 3000번 사용하기 때문에 react와 중복이 되어버린다.
 # 그래서 port를 변경해 주어야 한다.
   json-server --watch db.json --port 3004

#  실행이 안되면 아래를 적용한다.
 npx json-server --watch db.json --port 3004

# 서버와 통신하기
![image](https://github.com/jaejae87/React_basic.md/assets/129706762/fc359fdf-5612-4049-97ed-fea726b42f54)
  
  npm i axios

   import axios from 'axios';
