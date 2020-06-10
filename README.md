# it is just Rest Api with Flask frame work.

### it is just for understanding the basic work flow of Rest API in Flask FrameWork

## Usage
````
1. First create your virtual environment
			python3 -m venv yourvenv

2. then activate yourvenv
	On Windows, run:  	yourvenv\Scripts\activate.bat
	On Unix or MacOS, run: 	source yourvenv/bin/activate

4. then install needed packages
			pip install -r requirements.txt

5. run the app.py file in order to run telegram bot
	python app.py

6. fetch api on http://127.0.0.1:5000/product

    1. http://127.0.0.1:5000/product GET method:
            fetch all the products
    2. http://127.0.0.1:5000/product/<id> GET method:
            <id> some number id of the particular product fetchs the particular product
    3. http://127.0.0.1:5000/product/ POST method:
            {
                "description": "Product description",
                "name": "Product name",
                "price": 250,  
                "qty": 300
            }
            we need to submit this data with post request in order to add product 
    4. http://127.0.0.1:5000/product/<id> PUT method:
            <id> some number id of the particular product we will update this product
            {
                "description": "Product description",
                "name": "Product name",
                "price": 250,  
                "qty": 300
            }
            we need to submit this data with put request in order to update a product


````

