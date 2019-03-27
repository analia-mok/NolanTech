# NolanTech

A fake company's website.

## Technologies

- [Contenta CMS](https://www.contentacms.org/)
- [NuxtJS](https://nuxtjs.org)
- [Lando](https://docs.devwithlando.io/) This project was created using version v3.0.0-rc.13

## Local Setup

1. Make sure to have Lando installed
2. Clone this repo
3. Run: `chmod u+x startup` from the root of the directory (Still working on)
4. Then simply run `lando start` from within each the contenta and gridsome folders.
    - __For the first time you set up this site__, navigate to the contenta folder from a command line and run `lando drush si --db-url=mysql://drupal8:drupal8@database/drupal8`
      - This will install the drupal site using lando's default credentials. Once completed, it will output your admin credentials to the console.

### Available URLS
Contenta Backend: [https://nolan-tech.lndo.site](https://nolan-tech.lndo.site)

