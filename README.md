# Collaborative Song Dataset (CoSoD)
CoSoD consists of metadata and analytical data of a 331-song corpus comprising all multi-artist collaborations on the _Billboard_ “Hot 100” year-end charts published between 2010 and 2019. Each song in the dataset is associated with two CSV files: one for metadata and one for analytical data. 

# Annotation Data Overview 

For more details on the annotation process and data, refer to our ISMIR 2023 paper. Please cite the paper if you plan on publishing results using the dataset. 

**Metadata CSV Files**

The columns correspond to the following data:
1.	Index number: From 1 to 331
2.	Year of first appearance on _Billboard_ “Hot 100” year-end charts
3.	Chart position: As it appears on the _Billboard_ “Hot 100” year-end charts 
4.	Song title: As it appears on the _Billboard_ “Hot 100” year-end charts 
5.	Name of artists: As it appears on the _Billboard_ “Hot 100” year-end charts 
6.	Collaboration type:
    
>_Lead/featured:_ Collab. with lead artist(s) and featured artist(s)
>
>_No lead/featured:_ Collab. with no determined lead
>
>_DJ/vocals:_ Collab. between a DJ and vocalist(s) 

7.	Gender of artists:
   
>_Men:_ Collab. between two or more men
>
>_Women:_ Collab. between two or more women
>
>_Mixed:_ Collab. between two or more artists of different genders 

8.	Collaboration type + gender:
    
>_Collab M:_ Collab. between men, no determined lead
>
>_Collab M and W:_ Collab. between men and women, no determined lead
>
>_Collab NB and W:_ Collab. betwen women and non-binary artists, no determined lead
>
>_Collab W:_ Collab. between women, no determined lead
>
>_DJ with M:_ Collab. between male DJ and male vocalist
>
>_DJ with Mix:_ Collab. between male DJ and mixed-gender vocalists
>
>_DJ with NB:_ Collab. between male DJ and non- binary vocalist
>
>_DJ with W:_ Collab. between male DJ and female vocalist
>
>_M ft. M:_ Men featuring men
>
>_M ft. W:_ Men featuring non-binary artist(s)
>
>_W ft. M:_ Women featuring men
>
>_W ft. W:_ Women featuring women 

9.	MusicBrainz URL: Link to the song on open music encyclopedia MusicBrainz 




**Analysis CSV files**

The columns correspond to the following data:

1.	Index Number: 1 to 331
2.	Time Stamps: In seconds (start of new section)
3.	Formal section label: _Introduction, Verse, Pre-chorus, Chorus, Hook, Dance Chorus, Link, Post-chorus, Bridge, Outro, Refrain_ or _Other_
4.	Name of artist(s): Full name of the artist performing in each section. If all artists credited on the _Billboard_ listing perform in a section, the label both or all is used.

For each formal section performed by one artist only,  the following analytical data on the voice is provided:
1.	Gender of artist: _M_ (Man), _W_ (Woman), _NB_ (Non- binary) 
2.	Function of artist: _Feat_ (Featured artist), _Main_ (Main artist), _Neither, Uncredited_ 
3.	Style of vocal delivery: _R_ (Rapped vocals), _S_ (Sung vocals), _Spoken_ 
4.	Minimum pitch value: in Hz
5.	First quartile pitch value: in Hz
6.	Median pitch value: in Hz
7.	Third quartile pitch value: in Hz
8.	Maximum pitch value: in Hz
9.	Environment value: On a scale of E1 to E5
10.	Layering value: On a scale of L1 to L5
11.	Width (panning) value: On a scale of W1 to W5





