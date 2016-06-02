support:

 node ('master'){
  stage 'Checkout'
  checkout scm
  
  parallel {
   stage 'Test'
   sh 'echo "Test"'
  },
  {
   stage 'Performance Test'
   sh 'echo "Perfomance Test"'
  }
  
  stage 'Manual Check Stage'
  input message: "Does http://localhost:8888/staging/ look good?"
  
  stage 'Deploy'
  sh 'echo "We deploy some code!"'
  
 }
