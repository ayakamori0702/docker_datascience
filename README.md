# dockerの立ち上げ方  

### **1.Githubから必要なものをPULLしてくる**  
 
必要なスクリプトやデータがあれば、追加して入れる
### **2.dockerfileをbuildする**  
```$ docker build -t jupyter-datascience:0.0 docker```  

確かめるとき
```& docker images```

### **3.docker runする**  
```$ ./run.sh```  
このとき、run.shの **リポジトリ名:タグ名 またはイメージID** が合っているか確認する.
(最後の行がイメージIDでないとだめな場合もあり)




