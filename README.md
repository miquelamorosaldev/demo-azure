# demo-azure

Projecte Flask desplegat a Azure.

## Instruccions

```bash
python3 -m venv venv
source venv/bin/activate
(venv)$ pip install flask
```


from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "<html><body><h1>Hello Best Bike App!</h1></body></html>\n"
