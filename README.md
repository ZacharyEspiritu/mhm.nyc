# Mental Health Matters ![alt text](https://img.shields.io/badge/build-passing-brightgreen.svg "Build Status")

Mental Health Matters is a blog dedicated to raising awareness of mental health issues in New York City. In late August, two of my friends began the blog and asked me to design their website. 

You can find the website at [mhm.nyc][mhm-website].

It's built on the [Chameleon CMS][chameleon-cms] for Ruby on Rails.

<img src="https://github.com/ZacharyEspiritu/mental-health-matters/blob/master/app/apps/themes/default/assets/images/image.png?raw=true">

## Installation

```
git clone https://github.com/ZacharyEspiritu/mhm.nyc.git
cd mental-health-matters
bundle install
rake db:migrate
rails server
```

Upon being prompted to setup up your Chameleon build, choose the `default` theme.

Each of the custom pages (`home`, `about`, `learn`, `help`, `contact`) are served directly from Chameleon, and you'll need to manually create those as well in the Chameleon admin dashboard.

On production, I'm serving assets from an Amazon S3 bucket. If you wish to do the same, you can configure your AWS keys in the Chameleon admin dashboard as well—see the [Chameleon documentation][chameleon-cms] for more details.

## More Information

For more documentation on how to use Chameleon, please see the [chameleon-cms][chameleon-cms] Github repo.

[chameleon-cms]: https://github.com/owen2345/camaleon-cms
[mhm-website]: http://www.mhm.nyc
