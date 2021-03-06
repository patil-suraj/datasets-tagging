# datasets-tagging
A Streamlit app to add structured tags to the datasets


To run it, first install Streamlit (e.g. `pip install streamlit --upgrade`), then clone the repo and:

```
streamlit run tagging_app.py
```

This will give you a `localhost` link you can click to open in your browser.

The app initialization on the first run takes a few minutes, subsequent runs are faster.

Make sure to hit the `Done? Save to File!` button in the right column when you're done tagging a config!

By default the app only load the local datasets. To load and tag all the remote datasets, use:
```
streamlit run tagging_app.py -- --load_remote_datasets
```
