# Import Content Plugin

Import content using CSV files or RSS source

## Getting Started

Please follow along to have this plugin up and running.

### Prerequisites

Install headless CMS [Strapi](https://strapi.io/) 


### Installing


```
cd my-strapi-project/plugins
git clone https://github.com/richardblondet/strapi-import-content-plugin.git import-content
cd import-content && npm install
```

Go to your strapi root folder, [build and run your installation](https://strapi.io/documentation/3.0.0-beta.x/cli/CLI.html#strapi-develop-dev)


_\* the last step takes a notoriously long time..._

### Configuration

When plugin has been installed, you need to allow access to the endpoints.

1.  Navigate to Users & Permissions.
2.  Pick the role you would like to give permission.
3.  Scroll down and expand the section **Import Content**.
4.  Check "Select All" for the endpoints under "Importconfig".
5.  Scroll up and press "Save"


## Deployment

Add additional notes about how to deploy this on a live system

## Built With
```
- ReactJS 
- Strapi Headless CMS
```

## Authors

* **Joe Beuckman** - *Initial work* - [Github Project](https://github.com/jbeuckm/strapi-plugin-import-content)
* **Pouya Miralayi** - *Improvements* - [Tutorial](https://strapi.io/blog/how-to-create-your-own-plugin-part-1-4)
* **Richard Blondet** - *Implementation* - [Project](https://github.com/richardblondet/candidatord)

## License

This project is licensed under the MIT License.
