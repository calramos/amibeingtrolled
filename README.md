# spamcake

### bake your own spamcake
```
$ git clone https://github.com/calramos/spamcake.git
$ cd spamcake
$ virtualenv -p python3 venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
(venv) $ python bake <handle>
(venv) $ cd ready/<handle>
(venv) $ open .
```

Results aren't guaranteed to be completely accurate but provide good heuristics for determining if
the supplied handle exhibits common spamcake traits.
