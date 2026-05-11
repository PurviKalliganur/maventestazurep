git init
git add .
git commit -m "azure pipeline example"
git branch -M main
git remote add origin https://github.com/repo
git push -u origin main



mkdir maventest1 
cd maventest1 
STEP3: to create simple hellow world maven project type command as in below 
mvn archetype:generate -DgroupId=com.dineshonjava -DartifactId=Javateam -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
