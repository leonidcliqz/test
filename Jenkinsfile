@NonCPS
def printParams() {
      env.getEnvironment().each { name, value -> echo "Name: $name -> Value $value" }
}

node {
    printParams()
    echo env.CHANGE_TITLE
    echo env.CHANGE_ID
    echo scm.dump()

}
