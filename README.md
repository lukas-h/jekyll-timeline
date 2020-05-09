# jekyll-timeline
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Visualize time structured data with this simple jekyll-template.  
This Jekyll site is perfect for your résumé or other timelines.
## you can find a demo [HERE](https://lukas-h.github.io/jekyll-timeline/)
## screenshots
![SCREENSHOT RÉSUMÉ](screenshot.png)
![SCREENSHOT COMPOSERS](screenshot2.png)

## how to use it?
1. Fork this repository
2. Configure Github-Pages in the Repo Settings
3. Edit the Markdown files in the collection `steps` in the `_steps` folder  
    
    Required data fields in the frontmatter:
    
    - `title: <TITLE>`
    - `date: 2016-09-31 00:00:00 -0700` (Only Year and Month are shown)

    Optional fields:

    - `enddate: 2017-1-1 00:00:00 -0700`
4. Change site configuration `_config.yml`

    - the Site title: `title`
    - background color `color`
    - url (***very important***) `url`
    - baseurl (***important***) `baseurl` (name it after the repo)
    - site's `description`
5. You're done! (Look at https://<*USERNAME*>.github.io/<*REPO*>)

Feel free to contribute, give feedback, a star, and share it!
