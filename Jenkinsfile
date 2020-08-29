


    

















pipeline
{
    agent   { label 'Demo' }
    options { buildDiscarder(logRotator(numToKeepStr: '5'))  }
    stages
    {
        stage('stage1')
        {
            steps { echo "First Stage" }       }
    }
}