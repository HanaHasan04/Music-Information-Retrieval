# Music Information Retrieval (MIR)  

- With my **amateurish** interest in the field of Music Information Retrieval (MIR), I've taken on the task of analyzing the structure of songs using their waveforms/spectrograms.  
  
- I found this site https://musicinformationretrieval.com/ to be very helpful in understanding the fundamentals. In addition, I suggest taking a look at the [librosa](https://librosa.org/doc/latest/index.html) documentation.  
      
- I used the laplacian segmentation method of [McFee and Ellis](McFee_and_Ellis_2014.pdf) for analyzing song structure with spectral clustering.  
  
- I applied the algorithm to the song [Viva La Vida by Coldplay](https://www.youtube.com/watch?v=dvgZkm1xWPE) and I was able to detect the chorus and the intro in the song.  
  
- To view the displayed videos and audio, please open the [notebook](ANALYZING_SONG_STRUCTURE.ipynb) in Colab.
  
- Feel free to try this method on other songs as well and suggest ways to generalize it to work on all kinds of songs!  
(**Note:** all you need to do is change the `song_url`).     
   
