
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

run backend app:
uvicorn main:app --reload

http://127.0.0.1:8000/docs


// create pdf db table
alembic init alembic
alembic revision -m "create pdfs table"
alembic upgrade head

// verify in terminal:
psql tutorial
\dt
select * from pdfs
\q

AWS S3:
 - jpawsbucket
 - amazon resource name (ARN): arn:aws:s3:::jpawsbucket


deploy to render.com:
 - make sure to add all env variables from .env file


```


