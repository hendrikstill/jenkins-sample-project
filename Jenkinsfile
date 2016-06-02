support:

 node ('master'){
  stage 'Checkout'
  checkout scm
  stage 'Test'
  sh 'echo "Test"'
  error 'Something went wrong!'
  
  stage 'Performance Test'
  sh 'echo "Perfomance Test"'
  
  stage 'Deploy'
  sh 'echo "We deploy some code!"'
  
 }
