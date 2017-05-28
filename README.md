# PyData Chicago June 2017 Meeting

## Set up
```
git clone git@github.com:parsing-science/pydata_chicago_june_2017.git
cd pydata_chicago_june_2017
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Present slides
```
jupyter-nbconvert --to slides Talk.ipynb --post serve
```

## Create and present slides
```
jupyter-nbconvert --to slides Talk.ipynb
python -m SimpleHTTPServer
```

Edit the slides to make the slides bigger
```
   Reveal.initialize({
        width: '100%',
        height: '100%',
        transition: 'concave',
```

Go to http://127.0.0.1:8000/Talk.slides.html in browser.