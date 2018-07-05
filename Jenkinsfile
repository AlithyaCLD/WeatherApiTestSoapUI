pipeline{
    agent any
   /* tools {
    maven 'M3'
    } 5*/
    stages{

        stage('Test'){
            steps{
                //bat 'mvn -Dit.test=cucumber_runner.** verify'
                //bat 'testrunner -s WeatherSuite c:/AutomationProjects/Temp/RESTWeather.xml'
                echo 'Hello World'
                bat 'testrunner -s WeatherSuite RESTWeather.xml'

            }
        }


    }
 }