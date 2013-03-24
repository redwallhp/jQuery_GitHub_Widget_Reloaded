#jQuery GitHub Widget Reloaded

Based on [JoelSutherland's](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget) popular widget for displaying GitHub repositories on arbitrary web pages, this script adds the ability to list repos by user.

![Screenshot](http://i.imgur.com/qQ7gfHy.png)


## How to Use it

First, include the script sometime after jQuery.

    <script type="text/javascript" src="jquery.min.js"></script>
    <script type="text/javascript" src="githubRepoWidgetReloaded.min.js"></script>

Display a single repo by name:

    <div class="github-repo-widget" data-repo="woothemes/woocommerce"></div>
    
List repos by username:

    <div class="github-user-repos-widget" data-user="twitter"></div>