node('Arnold_Notebook') {
   stage 'Stage 1'
   bat 'chdir'
   bat 'echo \'Hello World 1\' > E:\\software\\1.txt'
   stage 'Stage 2'
   bat 'chdir'
   bat 'echo \'Hello World 2\' > E:\\software\\2.txt'
   stage 'Stage 3' 
   bat 'echo \'Hello World 3\' > E:\\software\\3.txt'
   dir("t24Java") {
       bat 'chdir'
       bat 'git pull'
   }
   
   dir("E:\\software") {
       bat 'dir'
   }
   bat 'chdir'
}
