pipeline
{
    agent {label 'Demo'}
    triggers
        {
            upstream ( upstreamProjects: 'Test-job1', threshold: hudson.model.Result.SUCCESS )
        }

        stages
            {
                stage('stage1')
                    {
                        steps { echo "test" }
                    }
            }
}