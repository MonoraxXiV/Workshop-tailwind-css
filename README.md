# Workshop-tailwind-css


## Learning objectives

- knowing what tailwind css is and having a first experience with it.
- being able to make a user friendly experience with tailwind.
- creating a visually appealing lay out.

## The mission

In the current times, we are all seeing a rise in online shopping.  
Some shops however could use a bit of help.  
You can choose if you want to rework an existing online shop, or create one from scratch.  
 
The main goal of this workshop is to create a visually appealing store page.

## Installing tailwind.css

The first step to installing tailwind.css is to make sure you have node npm installed.
> use `npm --version` to verify that you have npm installed on your pc  
>

To instal tailwind.css fully you will need to go through a few steps.  
You can link a stylesheet as we tend to do with bootstrap, this comes at a loss of some functionalities, an example of this is setting up custom colors.   
In today's workshop we will go over the full set up, with instructions so you can look it up again should you want to try it in the future.  
  
#### Installation steps:
  
  1. Make your repository/folder
  2. Set up your basic files, index.html and your css file, this can be done later as well.  
  3. In your root folder, open your terminal and type the following code: `npm init -y` this should create a package.json.
  4. Once the package.json is made we instal tailwind using `npm instal tailwindcss`.
  5. In your css paste the following code at the top of of your file:  
  ```
  @tailwind base  
  @tailwind components  
  @tailwind utilities
  ```

  6. In your terminal you use `npx tailwindcss init` to create your tailwind.config.js file, in this file you can define and customize your tailwind.  
   e.g. adding custom colours to your choices.    
  7. Next we will set up an autoprefixer using `npm instal postccs-cli autoprefixer`.  
  This should instal Postcss, which we will need to configure.
  8. `touch postcss.config.js` In this config file paste the following code:  
  ```
  module.exports = {
       plugins: [
           require('tailwindcss'),
           require('autoprefixer'),
       ]
   }
   ```
For those that prefer guides with practical examples I suggest to check out [tailwind css for beginners](https://codingthesmartway.com/tailwind-css-for-absolute-beginners/).  

possible errors
### Useful tools
Looking for inspiration? Maybe give the following links a try. 
   
**color palettes:**  
[colorsinspo](https://colorsinspo.com/)  
[colorspace](https://mycolor.space/)  
[visme colorschemes](https://visme.co/blog/website-color-schemes/)  


