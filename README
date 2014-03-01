#Making a Personal Site
This is a simple demo on how to make your very own personal site for free with Github Pages.

#Tools
For this project we're going to use 2 FOSS tools. You'll need to install them.
- [NodeJS](nodejs.org)
- [HarpJS](harpjs.com)
- [Bootstap](getbootstrap.com)

#Installing
Follow the instructions on both site to install Node and Harp. Do note that Harp is built on Node so you have to install them in order

#Languages
We're going to use a few different languages for this
- [Jade](jade-lang.com): Is a HTML templating language that makes writing HTML easier
- [Markdown](daringfireball.net/projects/markdown/): Is a templating language that make writing for websites easier
- [Less](http://lesscss.org/): Is a CSS templating language for easy CSS development

#Setting Up Our Environment
```
#Create a directory for the source branch of our site
mkdir my_site
cd my_site
git init
git branch -b source
git remote add origin github-url
#Now we need a deploy directory
git clone github-url
#Make the source branch ignore our deploy directory
echo "deploy/" > .gitignore
mkdir source
#Add the source branch to our github
git push origin source
```
This will give us a working directory for the site (`source`) and a 'compiled' directory (`deploy`)

#Developing
Development takes place on the `source` branch/folder. It is important that development is not done on the `master` directory, the reasoning will be explained later. You can see your changes live in real time using Harp's local server. From the `my_site` directory just run `harp server source` and Harp will server any files in there @ localhost:9000.

#Deploying
Deploying is really simple. Just compile your site with `harp compile source deploy`. This will take all your templates in source and spit out HTML, CSS, etc in deploy. Then just commit the changes to your master branch and upload to Github.