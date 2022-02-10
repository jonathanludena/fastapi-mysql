## CREATE NEW ENV WITH CONDA
```
conda create --name name_project_env python=3
```

## ACTIVATE ENV PROJECT WITH CONDA
```
conda activate name_project_env
```

## DEACTIVATE ENV PROJECT WITH CONDA
```
conda deactivate
```

## INSTALL DEPENDENCIES WITH PIP
```
python3 -m pip install name_library
```
- fastapi
- uvicorn
- sqlalchemy
- pymysql

## RUN APP WITH UVICORN
```
uvicorn app:app => whitout file watcher
uvicorn app:app --reload => with file watcher
```
## SAVE PACKAGES PIP INSTALLED IN PROJECT ENVIROMENT TO REQUERIMENTS.TXT
```
pip freeze > requeriments.txt
```

## INSTALL PACKAGES PIP FROM REQUERIMENT.TXT
1. create project env with conda
2. exec command on project path 
```
pip install -r requeriments.txt
```