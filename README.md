## Code Documentation of GeoNode Cloud Core

## Contribution Documentation

For contribution of the proyect you need follower step: 


1. Clone for project

`git clone --recursive https://github.com/Kan-T-IT/geonode-cloud-core-documentation.git`

2. Create virtual environment

`python3 -m venv env`

3. Activate virtual environment

`source env/bin/activate`


4. Update pip

`python -m pip install --upgrade pip`

5. Install dependencies

`pip install -r docs/requirements.txt`

6. Clearing of old file 

`cd docs`      
`make clean`

7. Build the documentation

`make html`

8. Open the documentation

`python -m http.server 8080 -d build/html`
