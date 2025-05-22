# Monitoring Attention in Self and Others

This repository contains code and links to data from the manuscript: Monitoring Attention in Self and Others

## Description

The ability of the brain to monitor its own attention is important for controlling attention. The ability to reconstruct and monitor the attention of others is important for behavioral prediction and therefore interaction with others. Do the same cortical net- works participate in constructing a metacognitive representation of attention, whether one’s own or someone else’s attention? We studied the brain activity of human participants in an fMRI scanner. The participants performed two attention-monitoring tasks. One involved focusing attention on their own breathing and pressing a button when they realized their attention had wandered. In the other, participants watched a video of an actor per- forming the same focused-attention task, and participants pressed the button if the actor’s attention appeared to have wandered. In both cases, we analyzed brain activity just before the button presses, when participants were engaged in metacognition with respect to attention. In the Self condition, activity was obtained in a distinctive set of areas including the TPJ, precuneus, dorsomedial pFC, anterior cingulate, and anterior insula. The activity partly overlapped the default mode network, social cognition network, and salience network. In the Other condition, activity was found in a similar set of areas including the TPJ, precuneus, dorsomedial pFC, anterior cingulate, and anterior insula. These results suggest that there may be a common set of cortical areas that provide an overarching mechanism for metacognition concerning attention, although Self and Other processing are also clearly not identical.

## Navigation


### Analysis code:
- GLM analysis (`./code/analysis/GLM`)
- Preprocessing after fMRI prep (`./code/analysis/preproc`)
- Behavioral data (`./code/analysis/behavioral`)
- 3dttest (`./code/analysis/3dttest`)
- Head Motion (`./code/analysis/head_mot`)

### fMRI prep preprocessing code
- preprocessing: (`/code/preprocessing`)

### fMRI Data
- fMRI data is available here: https://www.dropbox.com/sh/q51dsflo1riw9rf/AABcle7SHyfWi04KIAdcF-n-a?dl=0
- and here: https://doi.org/10.34770/xa5e-q930

### Getting Started
* Clone the Repo
* install environement dependencies
```
cd code
pip install environment.yml
```

* Download fMRI data via dropbox
```
cd data
wget https://www.dropbox.com/sh/q51dsflo1riw9rf/AABcle7SHyfWi04KIAdcF-n-a?dl=0
```


## Authors
Isaac R. Christian <br>
Samuel A. Nastase <br>
Mindy Yu  <br>
Michael S. A. Graziano



## License

This project is licensed under the GNU License - see the LICENSE.md file for details


