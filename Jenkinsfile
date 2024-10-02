pipeline
{
agent any
stages
{
 stage ('code scm checkout')
 { steps {  git branch: 'master', url: 'https://github.com/TanviReddyy/gradle-calculator.git'   } }

 stage ('code build')

 {   steps {  sh './gradlew clean build'
              sh './gradlew build'
                }}


 
}

}
