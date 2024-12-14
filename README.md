#### Dentify AI Project Setup
`Requirements:`<br>
- `8 GB RAM`<br>
- `Code Editor VSCode / Pycharm`<br>
- `Git CLI`<br>
- `Docker Desktop`<br>
- `Web Browser Chrome / Edge`<br>
- `python 3.12.4`<br>
  
#### Clone the Project
```
git clone https://github.com/Vishal7415/Rescue-riders.git rescue1
```

#### Go to Project Directory
```
cd rescue1\rescue\myworld\rescue_rider
```

#### Create virtual environment and install dependencies
- `Create environment`<br>
```
python -m virtualenv myworld -p python312
```

- `Activate environment`<br>
```
.\myworld\Scripts\activate
```

- `Install Dependencies`<br>
```
pip install -r requirements.txt
```

`You Are all Set to use the Project`<br>


##### Run the Project
```
cd .\rescue1\rescue\myworld\rescue_rider
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

##### View the Running Website
```
http://localhost:8000/
```

#### Update the Code
- `Reach the dentify-ai directory first`<br>

```
git pull
.\myworld\Scripts\activate
pip install -r requirements.txt
cd .\myworld\rescue_rider
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
