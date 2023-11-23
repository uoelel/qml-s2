# Details: Kirby and Misnadin (2020)

## Abstract

From [Kirby and Misnadin (2020)](https://doi.org/10.1121/10.0000992).

Madurese, a Malayo-Polynesian language of Indonesia, is of interest both areally and typologically: it is described as having a three-way laryngeal contrast between voiced, voiceless unaspirated, and voiceless aspirated plosives, along with a strict phonotactic restriction on consonant voicing-vowel height sequences. An acoustic analysis of Madurese consonants and vowels obtained from the recordings of 15 speakers is presented to assess whether its voiced and aspirated plosives might share acoustic properties indicative of a shared articulatory gesture. Although voiced and voiceless aspirated plosives in word-initial position pattern together in terms of several spectral balance measures, these are most likely due to the following vowel quality, rather than aspects of a shared laryngeal configuration. Conversely, the voiceless (aspirated and unaspirated) plosives share multiple acoustic properties, including F0 trajectories and overlapping voicing lag time distributions, suggesting that they share a glottal aperture target. The implications of these findings for the typology of laryngeal contrasts and the historical evolution of the Madurese consonant-vowel co-occurrence restriction are discussed.

The file `KirbyMisnadin2020.csv` contains duration and f0 measurements taken from the target vowel, across 11 equidistant time points.

## Variables

- `Filename`: Name of the audio recording file.
- `Speaker`: ID of the speaker.
- `Sex`: Speaker's gender.
- `Item`: Word.
- `Repetition`: Repetition number.
- `Voice`: Voicing of the target consonant.
- `Place`: Place of articulation of the target consonant.
- `Onset`: Consonant of the onset.
- `Pair`: Vowel pair in the `Item`.
- `Vowel`: Target vowel.
- `Vowel.Height`: Height of the target vowel.
- `VOT`: Voice Onset Time (ms).
- `seg_Start`: Time of closure onset (s).
- `seg_End`: Time of closure offset (s).
- `t`: Time point within consonant closure the measures are extracted from.
- `Vowel.Length`: Target vowel duration (ms).
- `v`: Time of voicing onset.
- `t_ms`: Time in seconds of `t`.
- `f0`: F0 measurement at time point `t`.


## Source

<https://datashare.ed.ac.uk/handle/10283/3600>
