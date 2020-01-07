# Backend

Configure nginx to route /api to `http://127.0.0.1:5000`

To run the backend:

`nohup gunicorn app:app -b 127.0.0.1:5000 &`