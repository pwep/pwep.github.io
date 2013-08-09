---
layout: post
title:  "Welcome to Jekyll!"
date:   2013-08-09 13:52:39
categories: jekyll update
---

You'll find hopefully this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com

## Some Extras ##

| Property                 | Value              |  
| ------------------------ | ------------------ |  
| Name                     | Samsung SyncMaster 971P    |
| Brightness               | 250 cd/m^2         |  
| Horizontal viewing angle | 178 deg            |  
| Diagonal size            | 19 inches          |  
| Pitch                    | 0.29 mm            |  
| Vertical viewing angle   | 178 deg            |  
| Response time            | 6                  |  
| Native resolution        | 1280 x 1024 pixels |  
| Display refresh rate     | 60Hz               |  
| Contrast ratio           | 1500:1             |  
[this is my table caption][tbl]

I am  [linking][tbl] to the table above. Here is cheese[^1] in a dish. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eget nulla justo. Fusce sit amet lacus justo. Nam ut neque augue. Suspendisse tincidunt consectetur adipiscing. Aliquam at pretium ante. Mauris nec interdum nisl. Sed eget felis dui[^2]. Nunc vel sem quis dolor egestas laoreet at in massa. Nam imperdiet congue libero, sit amet rhoncus erat fringilla nec. Morbi justo mi, aliquet in dapibus lobortis, eleifend tincidunt 123 sapien. Integer non metus id risus porta eleifend. Etia m vitae augue tellus. Phasellus faucibus elementum cursus. Mauris tristique accumsan orci et auctor. 

```
export PATH=$PATH:~/Dropbox/mmd/tables:~/Dropbox/EyeCode/bin
awk -F\t 'BEGIN{OFS="\t";}{print }'
```

[^1]: Phasellus tincidunt, dolor quis rhoncus auctor, urna orci imperdiet odio. 

[^2]: Yes. Dave. Chess.m

### R Code for Click Data ###

**Update**: (20130807) Include the prevalence condition from a trial in the output.


```r
# Rscript Eye09Clicks.r "8/Rec 01/Rec 01-Combined-Data_.tsv"

library(zoo,warn.conflicts=FALSE)
d <- ","

#off <- getOffsetFile(f)
#if(length(off)>0)
#{
#}

observer <- as.character(props$Participant.[1])
rec.date <- as.character(props$Recording.date.[1])
rec.time <- as.character(props$Recording.time.[1])
prevalence.condition <- as.character(props$Prevalence.condition.[1])
```
