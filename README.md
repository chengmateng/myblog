# My person blog
This is my person blog.



## Workflow for editing the blog

checkout a new branch such as `myfeature` and edit new changes

Then,

``` 
Hexo clean

Hexo generate

Hexo server
```
After everything is ok

```
Hexo deploy
```
And get back to `develop` branch to merge  in the `myfeature`  branch.

If everything is good, you can also let `master` branch merge in `myfeature` branch.


# Issues

### issue #1 

`_config.yml` in the root folder

* Url: https://chengmatengblog.netlify.app

  **Note: `url` is the name of my `Netlify` permlink

* Deploy: 

  ​	repo: https://github.com/chengmateng/myblog.git

  **Note**: **`repo`  here is the link for the repository**
