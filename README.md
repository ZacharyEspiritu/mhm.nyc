# Mental Health Matters ![alt text](https://img.shields.io/badge/build-passing-brightgreen.svg "Build Status")

Mental Health Matters is a blog dedicated to raising awareness of mental health issues in New York City.

It's built on the [Chameleon CMS](https://github.com/owen2345/camaleon-cms) for Ruby on Rails.

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
