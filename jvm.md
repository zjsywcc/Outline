catalina.sh 
把

JAVA_OPTS="-server -Xmx20g -Xms20g -Xmn2560m -XX:PermSize=128m -XX:MaxPermSize=196m -Xss256k -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+CMSParallelRemarkEnabled -XX:+UseCMSCompactAtFullCollection -XX:+UseCompressedOops"
改成
JAVA_OPTS="-Xmx20g -Xms20g -Xmn2560m -XX:PermSize=128m -XX:MaxPermSize=128m -Xss256k  -verbose:gc -XX:+UseParNewGC -XX:ParallelGCThreads=16 -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+CMSPermGenSweepingEnabled  -XX:+CMSClassUnloadingEnabled -XX:+CMSParallelRemarkEnabled -XX:+UseCMSCompactAtFullCollection -XX:+UseCompressedOops  -XX:+PrintGCDateStamps -XX:+PrintGCDetails -XX:+PrintGCApplicationConcurrentTime -XX:+PrintGCApplicationStoppedTime"

