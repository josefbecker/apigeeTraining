# Deploy Proxy "mock-target" using Maven
# 1. Unpack Zip-file  Mock-Target-API.zip
# 2. Open terminal and go to folder "Mock-Target-API" which contains 
	- pom.xml
	- apiproxy dir containing the unpacked proxy bundle
# 3. run the following command to deploy proxy

	mvn clean install -Ptest -Dorg={org} -Dusername={}user -Dpassword={password}
