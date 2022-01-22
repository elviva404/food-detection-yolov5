# Food-detection-yolov5 Technical Documentation

**Last updated:** 2022-01-22\
_Document generation aided by **Documatic**_

Automatic Documentation

* [Introduction](#introduction)
* [Code Overview](#code-overview)

## Introduction

This is a technical document detailing
        at a high-level
        what Food-detection-yolov5 does, how it operates,
        and how it is built.

The outline of this document was generated
        by **Documatic**.
<!---Documatic-section-group: arch-start--->


## Project Architecture


<!---Documatic-section-group: arch-end--->

<!---Documatic-section-group: helloworld-start--->


## Code Overview

The codebase has a 4-deep folder structure, with 47 in total.
<!---Documatic-section-helloworld: setup-start--->
The codebase is compatible with Python 3.6 and above, because of f-string 3.6 in /Users/elikemOZE/Codelab/Documatic/OS_projects/food-detection-yolov5/export.py.
Install requirements with `pip install -r requirements.txt`.
Install from pypi with `pip install main`.



<!---Documatic-section-helloworld: setup-end--->
`food-detection-yolov5.export` has a `__main__` entrypoint, which calls:

* `food-detection-yolov5.export.parse_opt`
* `food-detection-yolov5.export.main`

`food-detection-yolov5.app`` has a `__main__` entrypoint.

`food-detection-yolov5.utils.yolo2coco` has a `__main__` entrypoint, which calls:

* `food-detection-yolov5.utils.yolo2coco.convert`

`food-detection-yolov5.utils.split_image`` has a `__main__` entrypoint.

`food-detection-yolov5.utils.cocosplit` has a `__main__` entrypoint, which calls:

* `food-detection-yolov5.utils.cocosplit.main`

`food-detection-yolov5.api.api` has a `__main__` entrypoint, which calls:

* `food-detection-yolov5.api.api.update_db`


<!---Documatic-section-helloworld: entrypoints-start--->


## Entrypoints

There are 0 source code entrypoints in top-level `__main__`/`__init__` files.


<!---Documatic-section-helloworld: entrypoints-end--->

<!---Documatic-section-group: concept-start--->
## Concepts
<!---Documatic-section-group: concept-end--->

<!---Documatic-section-group: helloworld-end--->

<!---Documatic-section-group: dev-start--->


## Developers
<!---Documatic-section-dev: setup-start--->





<!---Documatic-section-dev: setup-end--->

<!---Documatic-section-dev: ci-start--->
The project uses GitHub Actions for CI/CD.

| CI File | Purpose |
|:----|:----|
| codeql-analysis |  |


<!---Documatic-section-dev: ci-end--->

<!---Documatic-section-group: dev-end--->

### **food-detection-yolov5/**

#### utils/

No files in `utils/` import local package files.

<!---Documatic-section-file: utils/yolo2coco.py--->

### yolo2coco.py


File has 92 lines added and 0 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.


<!---Documatic-section-file: utils/split_image.py--->

### split_image.py


File has 67 lines added and 0 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.


<!---Documatic-section-file: utils/xml2txt.py--->

### xml2txt.py


File has 74 lines added and 0 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.


<!---Documatic-section-file: utils/cocosplit.py--->

### cocosplit.py


File has 56 lines added and 0 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.


#### model/

`model/` relies most on `utils/` (imports 12 times).

###### utils/

No files in `utils/` import local package files.

###### models/

###### yolo/

###### utils/

No files in `utils/` import local package files.

<!---Documatic-section-file: model/detect.py--->

###### detect.py


File has 48 lines added and 39 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.


#### api/

`api/` is isolated (no imports from other subdirectories).

<!---Documatic-section-file: modules.py--->

#### modules.py


File has 123 lines added and 107 lines removed
                in the past 4 weeks. lannguyen <18120051@student.hcmus.edu.vn> is the inferred code owner.
