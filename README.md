# Armant Touche's personal-website

Website serves as a Resume CV/Portfolio for employers.

site: https://touche-hub.com

## Theme

Bolierplate on https://github.com/jekyll/minima

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
├── assets		# Contains static assets (i.e. images and custom-css)
│   ├── css
│   └── img
├── _includes		# There are partials used by _layout when using liquid tags.
├── _layouts		# Where liquid tags are declared to be used, allowing html modularity/encapsulation 
├── _sass		# These are sass partials 
│   └── minima		# Jekyll bolierplate
│       └── skins
└── script		
```

## Prerequisites

1. docker
2. docker-compose
3. Anytyppe of terminal application
3. An internet browser (I used Firefox)

### Locally

1. <code>git clone https://github.com/ActIII03/personal_website</code>
2. <code>$ sudo docker-compose build -t dev-website .</code>
3. <code>$ sudo docker-compose up</code>
4. Copy url to browser and there you go! You should be able to view my website.

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
