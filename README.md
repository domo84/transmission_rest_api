# transmission_rest_api

For Transmission. A REST layer on top of RPC. In `Python`.

There's nothing fancy about this. Just something I made in order to be able to use a RESTful approach when creating a new GUI.

You'll need to run it in parallel with `transmission` becuase it uses RPC as a data source. It's very much like a proxy.

### Install

```pip install -r requirements.txt```

### Configuration

Copy `config.template.json` to `config.json` and edit settings accordingly

### Running

```python main.py```
