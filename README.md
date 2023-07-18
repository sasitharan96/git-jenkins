This is a test repo to trigger jenkins via WebHooks
Jenkins received build commit from GitHub successfully!
Create two jenkin job with webhook option. Let's check wheter github trigger both the jobs.
Now, I deleted the WebHook Setting with ec2 instance weblink http://32.45.564.235:8080/webhook/. Without Webhook option auto trigger won't work. Lets  add webhooks http://52.90.152.114:8080/github-webhook/
Now I stopped and Start EC2  instance and connect with new IP address with jenkin. Lets check webhook works.
