@NonCPS
def printParams() {
      env.getEnvironment().each { name, value -> echo "Name: $name -> Value $value" }
}

@NonCPS
def printGit() {
    scm.userRemoteConfigs.each { name, value -> echo "Name: $name -> Value $value" }
}

node {
    printParams()
    echo scm.dump()
    printGit()
}
