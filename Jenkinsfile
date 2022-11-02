pipeline {
agent any
stages {
stage("Checkout") {
steps {
git url: 'https://github.com/kcheng806/calculator.git', branch: 'master'
}
}
stage("Compile") {
steps {
sh "./gradlew compileJava"
}
}
    
}
}
