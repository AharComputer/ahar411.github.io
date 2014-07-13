---
layout: post
title:  "how to post on a jekyll site"
date:   2014-06-17 11:26:29
---

2. make a new file following this format yyyy-mm-dd-post name.markdown under _posts

3. start it with 
    
        ---
        layout: post
        title:  "Welcome to Jekyll!"
        date:   2014-06-16 11:11:29
        categories: jekyll update
        ---

        my new post

        {% raw %}
        {% highlight ruby %}
        write code like this
        {% endhighlight %}
        {% endraw %}

4. turn the server on using `jekyll serve`

5. check your results at <http://localhost:4000/>


6. if you like publish it on gitusing the following steps

        $ git status
        $ git add .
        $ git commit
        $ git push

7. make sure it got published correctly on <http://ahar.sa/>
