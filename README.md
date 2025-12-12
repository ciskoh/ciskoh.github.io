to run on local :
``` 
sudo docker run --rm -it   --volume="$PWD:/srv/jekyll"   --publish 4000:4000   jekyll/jekyll:3.8   jekyll serve --watch --force_polling
```

2025.09.15 - about page is now the landing page and the content is in /home/matt/code/ciskoh.github.io/_includes/about-content.html§