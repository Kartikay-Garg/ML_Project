## End to End Machine Learning Project 



![Screenshot (31)](https://user-images.githubusercontent.com/117899107/236662915-b1bbd1db-3cbc-444a-a9b8-d4f7b1443dfd.png)

For Deployment: (AWS Elastic Beanstalk) (step by step)
1. open aws then sign in
2. Search for Elastic Beanstalk open application icon
3. create application
4. application name: , platform = python
5. click on sample application then create application
6. search on aws, "codepipeline", click on CodePipeline, create pipeline, pipeline name: , click next
7. source provider: Github (version 1), click connect to the Github, confirm it
8. select repository name, branch: main, Github webhooks, click next
9. Build Provider: Skip
10. Deploy provider: AWS Elastic Beanstalk, region, application name, environment name, next
11. Review: create pipeline
12. if error occurs: delete app.py file
13. Deployment Success.
