
```shell
mkdir -p ~/temp/bytedeco
cd ~/temp/bytedeco
git clone https://github.com/bytedeco/javacpp.git
cd javacpp
mvn clean install -Djavacpp.platform=linux-x86_64 -Dmaven.test.skip=true -Dmaven.javadoc.skip=true -Dmaven.test.failure.ignore=true
# Check /home/devtest/.m2/repository/org/bytedeco/javacpp
```