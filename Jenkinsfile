pipeline{
agent any

stages{
		
		stage(Build){
			steps{
					sh 'npm install'
					//sh 'cordova plugin add plugin_src/iamsdkionic-capgemini_cordova_sdk/'
					sh 'ionic cordova platform add android' 
					sh 'ionic cordova build android' 
			}
		}
		
      }
}
