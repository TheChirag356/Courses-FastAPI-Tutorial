This is a project that I built while trying to learn how to build API's. The URL to the original blog post is from [FreeCodeCamp.org](https://www.freecodecamp.org/news/fastapi-quickstart/). 

Thank you Atharv Shah for this amazing blog tutorial. It helped me alot. 

I am learning this to build a project for myself.

## Steps
1. Install some python modules
```
pip install fastapi pymongo uvicorn starlette pydantic
```
2. Start mongoDB server. Then add a database named `courses` using mongodb compass.
3. Run the script.py which contains the courses.
4. Run the api from [main.py](main.py) file by running this command in the terminal
```
uvicorn main:app --reload
```