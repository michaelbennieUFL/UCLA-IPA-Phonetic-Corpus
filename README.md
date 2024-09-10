# UCLA-IPA-Phonetic-Corpus
Dataset of ICASSP 2021 MULTILINGUAL PHONETIC DATASET Standarized to used IPA


## Instructions


It is a cleaned version of the dataset in the orignal Github repository [UCLA Phonetic Corpus](https://github.com/xinjli/ucla-phonetic-corpus). ***All entries are now IPA formatted and standarized***. Each directory on the top level is corresponding to a language name identified by its 3 character ISO id. There are currently 97 languages in this dataset.

Inside each directory, there will be 3 files and 1 directory

- `raw.old`: it contains the original narrow phone annotations of each utterance. The first field is the utterance id.
- `raw.new`: it contains the IPA formatted narrow phone annotations of each utterance. The first field is the utterance id.
- `text.txt`: it contains the segmented and normalized transcription from the raw utterance.
- `inventory`: it is directory contains the unique phoneme/phone inventory for this language. It is derived from `text.txt`
- `audio`: it contains all the wav format audios of each utterance. Its name is the corresponding utterance id.

## Acknowledgements

This dataset is derived from the [UCLA Phonetics Lab Archive](http://archive.phonetics.ucla.edu/) and [UCLA Phonetic Corpus](https://github.com/xinjli/ucla-phonetic-corpus).

## License

Contents of this dataset and the original website are licensed under a [Creative Commons license](https://creativecommons.org/licenses/by-nc/2.0/). You are free to copy, distribute, or adapt these materials for noncommercial purposes, under the following conditions:

- For any reuse or distribution, you must make clear to others the license terms of this work.
- Any derivative work may be distributed only under a license identical to this one. That is, you cannot claim exclusive right to any creation based on these materials, nor can anyone who further adapts your creation.
- Please attribute the material to the UCLA Phonetics Lab Archive (and this paper). See below for suggested citation format.

For any  script written outside of the "Data" directory, would be licensed under a [LGPL 2.1 or later](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html). Note, this does not apply to the data itself.

Copyright (C) 2024  Michael Bennie

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA


## Reference

If you find this work helpful, please cite the following works

```

@misc{bennie2024ipacorpus,
  author       = {Bennie, Michael},
  title        = {UCLA IPA Phonetic Corpus},
  howpublished = {\url{[https://github.com/用戶名/存儲庫名](https://github.com/michaelbennieUFL/UCLA-IPA-Phonetic-Corpus)}},
  year         = {2024},
  note         = {訪問日期：yyyy-mm-dd}
}

@inproceedings{li2021multilingual,
  title={Multilingual phonetic dataset for low resource speech recognition},
  author={Li, Xinjian and Mortensen, David R and Metze, Florian and Black, Alan W},
  booktitle={ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={6958--6962},
  year={2021},
  organization={IEEE}
}

2007. The UCLA Phonetics Lab Archive. Los Angeles, CA: UCLA Department of Linguistics. http://archive.phonetics.ucla.edu/.

```
