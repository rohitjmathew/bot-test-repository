# bot-test-repository
Repository where I add bots and test them to enhnance the github workflow

## Bots Added
1) [Templater](https://github.com/marketplace/templater):
    
    This is bot is added to ensure that pull request templates or issue templates are followed. This bot checks that the either the PR Template is not empty or that the PR body does not match the PR Template
    
2) [Traffico](https://github.com/marketplace/trafico-pull-request-labeler/):

    Labels are an easy way to quickly look and see the status of the PR. Labels are a common practice followed by most OSS. Labels are used in Google OSS (Firebase, tensorflow) & Microsoft OSS (VS Code) to name a few. 

3) [Pull Request Size](https://github.com/marketplace/pull-request-size):

    Ideally the best way to do code reviews is by means of smaller simple PRs. To help enforce this and to encourage smaller PRs being created this bot will enable us to add a label describing the size of the PR. 
    
4) [Mergeable](https://github.com/mergeability/mergeable):

    To enforce standards are followed stringently you can use rules in mergeable to block pull request merges. Multiple OSS organisations like airflow, grpc and fossasia. In this scenario we use mergeable to block the PR if the body isn't updated with useful data. 
    
    
4) [WIP](https://github.com/wip/app):

    To ensure we do not merge PRs with WIP in them we are using the WIP bot to block PR merges with WIP in the title

Test
