#!groovy
node ('slave1'){
   stage 'Checkout'
   checkout scm
   def gradle = tool 'gradle4'

   stage 'Build'
   sh "${gradle}/bin/gradle build"
}
