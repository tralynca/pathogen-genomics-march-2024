# An open-source project for creating online courses, built by P2PU
Course-in-a-Box is a free tool for building and publishing online courses — no prior coding experience required. 

To create your own course, simply fork this repository and delete the CNAME file. Detailed documentation is available at [course-in-a-box.p2pu.org](https://course-in-a-box.p2pu.org).

To make changes to the template itself, a good place to start is the [`_layouts`](/_layouts), [`_includes`](/_includes) and [`css`](/css) directories. These directories contain all the layout and style files used.

Questions? Ask on P2PU's [Community Forum](https://community.p2pu.org/c/tech/course-in-a-box/78).

# Running locally
- [install docker](https://docs.docker.com/engine/install/)
- Run `./serve.sh`

# Adding figures

The [jekyll-figure](https://github.com/paulrobertlloyd/jekyll-figure) module has been added to this repository. To make figures, enclose images in `{% figure %}` markdown
and use the class "caption", i.e.

```
{% figure [caption: "The Figure Caption"] [class: "caption"] %}

![The Alt Text for the Image](../img/the_image.jpg)

{% endfigure %}
```

As a convention, images can be placed in an `img/` folder created within the module directory and linked as per the above example.

---
Course-in-a-Box is built by [Peer 2 Peer University](https://www.p2pu.org) and shared under an MIT License.

Course content ("Modules") are shared under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).