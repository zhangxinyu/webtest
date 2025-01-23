用于测试java 代码覆盖率
1 启动命令:java -javaagent:"/Users/zhangxinyu/opt/org.jacoco.agent-0.8.5-runtime.jar=includes=,output=tcpserver,port=18513,address=,append=true" -jar target/webtest-0.0.1-SNAPSHOT.jar 
2 部署testting-super-jacoco (fork super-jacoco) git clone https://github.com/zhangxinyu/testting-super-jacoco java -DgitLabToken={配置token 用户下载webtest} -jar testting-super-jacoco.jar 
3 测试结果： 
<img width="1484" alt="image" src="https://github.com/user-attachments/assets/c757a74a-039e-4876-af30-1f1f2467383d" />
