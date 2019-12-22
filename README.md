# Flask/Pytorch/Docker starter app

This project is aimed to help machine learning developers to quickly build a Flask web app in a Docker container ready to be deployed. 

## Getting Started

You need to have Python installed in your computer.

1. Install `virtualenv`: 
    ```console
    pip install virtualenv
    ```
2. Create a Python virtual environment:
    ```console
    virtualenv venv
    ```
3. Activate virtual environment:
    1. Windows:
    ```console
    cd venv\Scripts
    activate
    cd ..\..
    ```
    2. Lunix / Mac:
    ```console
    source venv/bin/activate
    ```
4. Install libraries:
   
   ```console
   pip install -r requirements.txt
   ```

## Run the code

* Run the app:
    ```console
    Flask run
    ```
* Run on a specific port:
    ```console
    python character_level_text_generation.py
    ```

## Built With

* [Pytorch](https://pytorch.org/) - The Machine Learning framework used
* [Flask](http://flask.palletsprojects.com/en/1.1.x/) - The web server library

## Authors

* **Imad Eddine Toubal** - *Initial work* - [imadtoubal](https://github.com/imadtoubal)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


 Happy coding!