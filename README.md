# webpack
A project using webpack with different variations to practice.


Branches:
 - Simple: Webpack is used to compile JavaScript modules. This is a basic build. https://webpack.js.org/guides/getting-started/
 - Asset-management: One of the coolest webpack features is that you can also include any other type of file, besides JavaScript, for which there is a loader or built-in Asset Modules support. https://webpack.js.org/guides/asset-management/
 - Output-management: So far we've manually included all our assets in our index.html file, but as your application grows and once you start using hashes in filenames and outputting multiple bundles, it will be difficult to keep managing your index.html file manually. However, a few plugins exist that will make this process much easier to manage. https://webpack.js.org/guides/output-management/
 - Development: setting up a development environment. https://webpack.js.org/guides/development/
 

Quick tip: the node_modules folder can get really big. It is customary to add a .gitignore file to your project so that you don’t have to sync the contents of node_modules to github. The dependencies that are stored there can be installed from your package.json by running npm install, so you don’t need to sync them.
