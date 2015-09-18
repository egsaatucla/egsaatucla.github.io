#eGSA @ UCLA Website
This is the 2015 revamp of the eGSA website by [Jon Van Lew](http://jon.vanlew.net) so blame him if anything goes wrong. It is based on the hugely popular [clean-blog-jekyll](https://github.com/IronSummitMedia/startbootstrap-clean-blog-jekyll) theme. 

## Adding New Officers
I tried to make it easier for future adding and removing of current officers -- but it's a little hacked because of Jekyll on GitHub being primarily targeted at blogs. So each officer is a "post" in the `_posts` directory. These are the steps to adding a new officer:

* Add a file to the `_posts` directory with a format like `2015-01-01-officer_name.md`
* Add the appropriate keywords to the file, such as this:

```	
---
layout:     post
title:      "Jon Van Lew"
description: "Athletic Director"
header-img: "img/officers/vanlew_profile.jpg"
email: "ims@bruinegsa.org"
active: true
---
```
* Add any other info you want under the last `---` line. e.g. a bio or whatever other info you want.
* Put the profile image that you reference in the post into the `img/offiers/` folder in the GitHub repository.

Then the officer page will automatically display the new officer and a page will be generated for that officer.

## Marking Old Officers as Inactive
To move officers out of the active display, you only need to go into the officer's post page and change `active` to `false` and they will automatically only be displayed in the "Past Officers" section. Using the above demo as an example, the preamble of the officer page would now look like this:
```	
---
layout:     post
title:      "Jon Van Lew"
description: "Athletic Director"
header-img: "img/officers/vanlew_profile.jpg"
email: "ims@bruinegsa.org"
active: false
---
```