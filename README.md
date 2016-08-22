# Mental Health Matters ![alt text](https://img.shields.io/badge/build-passing-brightgreen.svg "Build Status")

Mental Health Matters is a blog dedicated to raising awareness of mental health issues in New York City. In late August, two of my friends began the blog and asked me to design their website. 

You can find the website at [mhm.nyc](http://www.mhm.nyc).

It's built on the [Chameleon CMS](https://github.com/owen2345/camaleon-cms) for Ruby on Rails.

<img src="https://github.com/ZacharyEspiritu/mental-health-matters/blob/master/app/apps/themes/default/assets/images/image.png?raw=true">

## Installation

```
git clone https://github.com/ZacharyEspiritu/mental-health-matters.git
cd mental-health-matters
bundle install
rake db:migrate
rails server
```

Upon being prompted to setup up your Chameleon build, choose the `default` theme.

Each of the custom pages (`home`, `about`, `learn`, `help`, `contact`) are served directly from Chameleon, and you'll need to manually create those as well in the Chameleon admin dashboard

## More Information

For more documentation on how to use Chameleon, please see the [chameleon-cms](https://github.com/owen2345/camaleon-cms) Github repo.
