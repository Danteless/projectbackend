pipeline {

agent any

stages ( 'Compile Stage') {

steps {

withMaven(maven : '3.8.1') {
   sh 'mvn cle compile'


}
}
}

stages ( 'Testing Stage') {

steps {

withMaven(maven : '3.8.1') {
   sh 'mvn test'


}
}
}

stages ( 'Deployement Stage') {

steps {

withMaven(maven : '3.8.1') {
   sh 'deployement test'


}
}
}
}