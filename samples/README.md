# DICOM Studio sample studies

These archives contain real, multi-instance DICOM studies used by DICOM
Studio's free **Sample studies** feature. They are public, de-identified
teaching and software-validation datasets. They must not be used for diagnosis
or treatment.

The MiniPACS studies are derived from the Orthanc project's public demo data
and published as de-identified teaching cases by
[MiniPACS](https://minipacs.net/free-dicom-viewer/). DICOM Studio removed
patient-identifying fields and private tags again, then converted the JPEG-LS
pixel data to uncompressed Explicit VR Little Endian DICOM so the samples work
offline with the app's standard decoder.

The head CT comes from Chris Rorden's
[`dcm_qa_ct`](https://github.com/neurolabusc/dcm_qa_ct) validation dataset and
is redistributed under the BSD 2-Clause License. See
`LICENSE-dcm-qa-ct.txt`.

| File | Modality | Images / series | SHA-256 |
| --- | --- | --- | --- |
| `brain-mri.zip` | MR | 144 / 3 | `3665a232153e61d19a3737fb5d3ecf0112dce9ff2a6da418c8f79de79585b374` |
| `petct-neck.zip` | PT + CT | 166 / 2 | `912fa9ab48a99b07dcfd4589fa81af8e4b6e06e45118237c46244660cdda91a0` |
| `ct-ankle.zip` | CT | 250 / 1 | `c45d8862410eb688215b990460b6c04b867f694c85af8b74eeb432e792178fb8` |
| `head-ct.zip` | CT | 28 / 1 | `56e13cb4fa14a2028414771c4b9f677ff00312decacd9a15fa86ae9dc4283fb3` |

Each archive was imported by DICOM Studio's production import pipeline and
indexed as a multi-image DICOM study before publication.
