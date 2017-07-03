# Hello CloudFoundry Tile

This is a sample CloudFoundry Tile to get started with CloudFoundry Tile development.

# Getting Started

1. Create a Python virtual environment with the following command:
   
   ```bash
   virtualenv -p python2 tile-generator-env
   ```

2. Activate the virtual environment with the following command:

   ```bash
   source tile-generator-env/bin/activate
   ```

3. Install the tile-generator package inside the virtualenv with the following command:

   ```bash
   pip install tile-generator
   ```

4. Install BOSH CLI by following the steps in the following link:
   https://bosh.io/docs/cli-v2.html#install

5. Now, build the tile using the following command:

   ```bash
   tile build
   ```

# Hello Service

The hello world service in this tile has been taken from the following location:
https://github.com/wso2/msf4j/tree/v2.2.1/samples/helloworld

# References

- Tile Generator Documentation: http://docs.pivotal.io/tiledev/tile-generator.html

# License

Content in this repository is licensed under Apache 2.0.
