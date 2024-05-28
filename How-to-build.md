git fetch --tags https://github.com/jenkinsci/workflow-cps-plugin   
git rebase on tag   
mvn clean package -DskipTests "-Dplugin.version.description=tag: "