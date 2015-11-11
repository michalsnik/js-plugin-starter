# js-plugin-starter
Simple JS plugin starter repository

With all necessary configuration to bootstrap your ideas and get rid of setting everything all over again.


## Instruction

1. Clone Repository
    
    ```bash
    git clone git@github.com:michalsnik/js-plugin-starter.git your-plugin-name
    ```

2. Go to your-plugin name folder and install npm packages
    
    ```bash
    cd your-plugin-name && npm install
    ```

3. If you change ```plugin.js``` or ```plugin.scss``` name remember to change it inside ```plugin.json``` file as well.
    Gulp tasks relies on those names in order to do its job correctly.

4. Run gulp

    ```bash
    gulp
    ```

5. Go to ```http://localhost:3000/demo/``` and now you're ready to roll

### Additional info


Starter uses browserify for bundling JS, so don't hesitate to require node modules and partition your code to make it more pleasant to work with.
