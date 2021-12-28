# Cocktail-Party-Audio-Processing-Python
Google Colab Link to View:
https://colab.research.google.com/drive/1UAxk0NQBS_uoItruo89zZkerRQxBGVtB

Sebastian Ouslis

Paper Name:
THE COCKTAIL FORK PROBLEM: THREE-STEM AUDIO SEPARATION FOR REAL-WORLD SOUNDTRACKS

Problem Formulation:

The Cocktail Party problem is a challenge for computers to be able to isolate any source of interest within a complex acoustic scene. It is called the cocktail party problem because it is similar to if you were at a party where multiple conversations or sounds were occuring at the same time and you wanted to listen to one. This is very easy for humans to do but it is more difficult for computers.

This paper theorises a new problem where three audio sources are combined together: music, speech, and sound fx (ambient noise and natural sounds).

The paper is a report explaining how to make a dataset for this problem using the following datasets: LibriVox (speech), FSD50K (SFX), and FMA (music)

Proposed Solution:

Step 1: Grab the Datasets

Step 2: Convert datasets to the same file type (WAV)

Step 3: Normalize loudness based on audio type

Step 4: Resample audio to same sampling rate

Step 5 (Optional): Append short audio clips to themselves to take up more time in the audio

Step 6: Combine audio clips

Datasets (Warning they are very big) :

FSD50K -- https://zenodo.org/record/4060432#.YTkaoN8pBPY

FMA-Medium Set -- https://github.com/mdeff/fma

LibriSpeech/LibriVox -- https://www.openslr.org/12

Read the HTML document or the Google Colab to see more.

https://colab.research.google.com/drive/1UAxk0NQBS_uoItruo89zZkerRQxBGVtB

