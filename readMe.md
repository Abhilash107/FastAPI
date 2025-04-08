# create an environment:
- python -m venv venv

# activate:
- .\venv\Scripts\activate

# install: 
- pip install uvicorn fastapi
# save req files
- pip freeze > req.txt

# run: 
- uvicorn main:app --reload