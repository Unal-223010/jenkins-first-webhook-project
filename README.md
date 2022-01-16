# jenkins-first-webhook-project

 1.)Integrating Jenkins with GitHub using Webhook

-Jenkins dashboard and click on New Item to create a new job item.
-Put a checkmark on Git under Source Code Management section, enter URL of the project repository, and let others be default.
    "https://github.com/<your-github-account-name>/jenkins-first-webhook-project/"
-Put a checkmark on GitHub hook trigger for GITScm polling under Build Triggers section = Github repomda bulunan .py dosyasinda herhangi bir degsiklik oldugunda yani bir commit islemi gerceklestigind vs job/projet trigger olacak ve calisacak otomatik olarak.
-Check Branch Specifier. It must be same branch name with your jenkins-first-webhook-project Github repository. If your repository's default branch name is "main", then change "master" to "main".
-Go to Build section and choose "Execute Shell Command" step from Add build step dropdown menu.
  
 
