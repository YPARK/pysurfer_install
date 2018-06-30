---
title: note for `pysurfer`
---

# Installation

First, let's use `bash` not `tsch`.  Type `bash`

Let's create a virtual environment for conda to use `python 2.7`
satisfying decency.  We name it `work`.

```
bash-4.2$ conda create --name work python=2.7 scipy numpy ipython babel mayavi matplotlib
```

Activate the environment `work` and install `Mayavi`

```
bash-4.2$ source activate work
(work)bash-4.2$ pip install --upgrade pip
(work)bash-4.2$ conda install mayavi
```

Now let's install `pysurfer`
```
(work)bash-4.2$ pip install pysurfer
(work)bash-4.2$ pip install -U pysurfer[save_movie]
```

# Usage

```
kveragalab:heeyeon[86] bash
bash-4.2$ source activate work
discarding /usr/pubsw/packages/python/anaconda/bin from PATH
prepending /homes/1/heeyeon/.conda/envs/work/bin to PATH
(work)bash-4.2$ 
```

Do your work within this environment.

```
(work)bash-4.2$ source deactivate
```

