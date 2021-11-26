pipeline{
agent any

stages{
		
		stage('Build'){
			steps{
					bat 'npm install'
					//sh 'cordova plugin add plugin_src/iamsdkionic-capgemini_cordova_sdk/'
          //bat 'npm install -g @ionic/cli'
					bat 'ionic cordova platform add android' 
					bat 'ionic cordova build android' 
			}
		}
		
      }
}
