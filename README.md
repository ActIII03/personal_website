# Armant Touche's personal-website

Website serves as a Resume CV/Portfolio for employers.

## Theme

[Bolierplate on https://github.com/jekyll/minima

## Features

- Ruby On Rails promotes a modular approach
- PWA (desktop & mobile)
- Easy to customize
- Nice project structure
- SASS CSS allowing variable encapsulation
- Tablet & mobile friendly
- Can locally deploy for development with docker
- Able to be hosted on Github Pages


## Structure

```bash
.
├── 404.html
├── about.md   				
├── assets
├── CNAME					# Custom domain
├── CODE_OF_CONDUCT.md
├── _config.yml
├── docker-compose.yml
├── Gemfile					# Ruby on Rail preprocessors
├── Gemfile.lock
├── _includes
├── index.md
├── _layouts				
│   ├── about.html
│   ├── default.html
│   ├── home.html
│   ├── page.html
│   └── post.html
├── LICENSE.txt				# MIT licence
├── minima.gemspec
├── README.md 				# The file being currently on github
├── robots.txt				# Enforce no webscrappers
├── _sass
├── _site
```

## Prerequisites

### Online

1. Create an account at [Formik](https://formik.com/?utm_source=smakosh) and grab your form endpoint url
2. Grab a Google recaptcha key from [Google Recaptcha](https://www.google.com/recaptcha/admin)
3. Grab your Github token from [GitHub](https://github.com/settings/tokens/new?scopes=repo&description=portfolio-dev)
4. Click [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/settings?s=https%3A%2F%2Fgithub.com%2Fsmakosh%2Fgatsby-portfolio-dev&c=1&env=GATSBY_PORTFOLIO_GITHUB_TOKEN%2CGATSBY_PORTFOLIO_FORMIK_ENDPOINT%2CGATSBY_PORTFOLIO_RECAPTCHA_KEY&envDescription=Required%20to%20fetch%20your%20repositories%20from%20GitHub&envLink=https://github.com/smakosh/gatsby-portfolio-dev&framework=nextjs) and pass in your:
  
  - Formik form endpoint
  - Google recaptcha public key
  - Github token

To Env variables section.

### Locally

1. Need: (i) docker (ii) docker-compose (iii) git
2. git clone https://github.com/ActIII03/personal_website
3. $ sudo docker-compose build -t dev-website .
4. $ sudo docker-compose up
5. Copy url to browser and there you go!

## Built with

- Jekyll Boilerplate
- Docker 


## License

This project is licensed under the MIT License - see the (LICENSE.txt) file for more details

## Contributors

None

## Support

If you love this Minima template then go checkout Jekyll's themes and if you want to contact me, try my email: a.touche03@mail.com

# Thank you for visiting!
