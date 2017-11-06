# ww-parallel-coordinates
Web-Component that embeds and reuses D3 parallel coordinates.

## How to install the web component
In order to install the web component you need to have bower installed and already the bower.json for your project, then run the following command in the project directory:

    > npm install --save https://github.com/webwidgets/ww-parallel-coordinates.git
    
Great, you have successfully installed the web component.

## How to use the web component
TODO: In order to use the web component you need to import the html in the ... 

## How to extend the web component
There are many ways to setup the environment in order to make changes to the web component. Here I describe one that uses the bower link command. 

1. Clone the project from github

    > git clone https://github.com/polywc/polywc-parallel-coordinates.git
  
2. Link the project 

    > cd polywc-parallel-coordinates
    > bower link
    
    Bower link will create a link to the project directory.
    
3. Create a new directory everywhere on your computer

    > mkdir polywc-develop
    
4. Create a new bower.json file as follows:

    ```json
    { 
        "name": "polywc-develop",
        "version": "1.0.0",
        "dependencies": {
            "polywc-parallel-coordinates": "^0"
        }
    }
    ```
    
5. Link back the polywc-parallel-coordinates library

    > cd polywc-develop
    > bower link polywc-parallel-coordinates
   
   Bower will link the project and update all the dependencies. In this way you will not rely on the remote git repository to receive the developing updates, but instead every change made to the library will be immediately available in polywc-develop project. Furthermore, you can open the polywc-develop directory directly from the editor (e.g., PHPStorm) and work at same time on the polywc-develop and bower-components/polywc-parallel-coordinates component.
   
6. You are ready to work on the project, enter in the working directory

    > cd bower_components\polywc-parallel-coordinates
    
7. Check that everything works as expected by running the file demo\index.html in a web server container (or from PHPStorm) editor.

## Bugs, support and other issues

For any bug or enhancement suggestion please create a new issue using the GitHub [Isses tool](https://github.com/webwidgets/ww-parallel-coordinates/issues).

## License 

The library has released with the LGPL 3.0[link here](https://github.com/webwidgets/ww-parallel-coordinates/blob/master/LICENSE).

