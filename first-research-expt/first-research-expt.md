# Do your first research experiment

Create your own git repo wherever you want. Most people will choose to do it within their own GitHub account, but GitLab is another good option and there are plenty of other possible choices. Give your repo a name that includes `comp560` and your login/username e.g., `comp560-jmac`.

Create a `README.md`, a `.gitignore` suitable for Python projects, a Python virtual environment, and a `LICENSE` file. Update these whenever needed as your experiment progresses. Activate your virtual environment.

You probably have already cloned our fork of nanoGPT, [comp560-nanoGPT](https://github.com/dson-comp560-sp26/comp560-nanoGPT). If not clone it. Either way it should be installed at the same directory level as your new repo (e.g., if new repo is at `~/git/comp560-jmac` then nanoGPT should be at `~/git/comp560-nanoGPT`).

Decide on the stream of data you would like your LLM to learn. Think of something that is easy to learn based only on character-by-character information. Three examples are provided here, but you should think of your own example. Seek help if necessary.
* Example 1: Count by twos starting from a number under 100. A random stream might look like:
```
        43 45 47 49
        12 14 16 18
        96 98 100 102
        8 10 12 14
        37 39 41 43
        12 14 16 18
        ...
```
* Example 2: Translate a few words between languages. A random stream might look like:
```
        siete seven
        once eleven
        nueve nine
        uno one
        doce twelve
        nueve nine
        seis six
        diez ten
        cinco five
        diez ten
        ...
```
* Example 3: Insert spaces between characters. A random stream might look like:
```        
        cebe: c e b e
        abbacde: a b b a c d e
        dbca: d b c a
        ...
```

Create a subdirectory with the name of the experiment you would like to conduct, say `insert-spaces` for example 3 above. These instructions will continue to use example 3. Populate the new subdirectory with files and folders as in the following tree:
```
        insert-spaces
        ├── README.md
        ├── config
        ├── data
        └── out
```
Continue to update the README file in this directory with descriptions of your experiment as it evolves.

Copy the provided [`prepare.py`](prepare.py) and alter it so that it produces a sample from your chosen data stream. The version provided here produces data for the `insert-spaces` experiment in example 3 above. Run your program and make a reasonable attempt to verify that it is working correctly. Note that it produces some output files:  `meta.pkl`, `train.bin`, and `val.bin`. Move these and your Python script into a new subdirectory called `basic`, under `data`:
```
data
└── basic
    ├── meta.pkl
    ├── prepare.py
    ├── train.bin
    └── val.bin
```
Why do we put these in a new subdirectory called "basic"? Because this is our "basic" version the experiment. We may have more fancy ones later with different names and they will have their own subdirectories under `data`.

......  Under construction ......





