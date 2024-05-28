git fetch --tags https://github.com/jenkinsci/workflow-cps-plugin
mvn package -DskipTests "-Dplugin.version.description=tag: "