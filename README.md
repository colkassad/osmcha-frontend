# Built front end

This repository contains the built code from https://github.com/mapbox/osmcha-frontend

* Clone that repository
* If you are going to do local development with localhost, then you must navigate to `src/config/index.js` and update the URL on line 9 to `https://localhost/api/v1`

* Follow the instructions on that repositories README file to eventually get to `yarn build`
* The contents of this present repository are the files that are built from `yarn build`
* This repository is then pulled from the Backend Django app by running the `python manage.py update_frontend` task. That repository has been modified to pull from this repository here.


