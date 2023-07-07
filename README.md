# Collaborative Song Dataset (CoSoD)
CoSoD consists of metadata and analytical data of a 331-song corpus comprising all multi-artist collaborations on the Billboard “Hot 100” year-end charts published between 2010 and 2019. Each song in the dataset is associated with two CSV files: one for metadata and one for analytical data. 

# Annotation Data Overview 

For more details on the annotation process and data, refer to our ISMIR 2023 paper. Please cite this paper if you plan on publishing results using the dataset. 

**Metadata CSV Files**
The columns correspond to the following data:
1.	Index number: From 1 to 331
2.	Year of first appearance on Billboard “Hot 100” year-end charts
3.	Chart position: As it appears on the Billboard “Hot 100” year-end charts 
4.	Song title: As it appears on the Billboard “Hot 100” year-end charts 
5.	Name of artists: As it appears on the Billboard “Hot 100” year-end charts 
6.	Collaboration type: 
•	Lead/featured: Collab. with lead artist(s) and featured artist(s) 
•	No lead/featured: Collab. with no determined lead 
•	DJ/vocals: Collab. between a DJ and vocalist(s) 
7.	Gender of artists: 
•	Men: Collab. between two or more men 
•	Women: Collab. between two or more women 
•	Mixed: Collab. between two or more artists of different genders 
8.	Collaboration type + gender: 
•	Collab M: Collab. between men, no determined lead 
•	Collab M and W: Collab. between men and women, no determined lead 
•	Collab NB and W: Collab. betwen women and non-binary artists, no determined lead 
•	CollabW:Collab.betweenwomen,nodetermined lead 
•	DJ with M: Collab. between male DJ and male vocalist 
•	DJ with Mix: Collab. between male DJ and mixed-gender vocalists 
•	DJ with NB: Collab. between male DJ and non- binary vocalist 
•	DJ with W: Collab. between male DJ and female vocalist 
•	M ft. M: Men featuring men 
•	M ft. W: Men featuring non-binary artist(s) 
•	W ft. M: Women featuring men 
•	W ft. W: Women featuring women 
9.	MusicBrainz URL: Link to the song on open music encyclopedia MusicBrainz 

**Analysis CSV files**
The columns correspond to the following data:

1.	Index Number: 1 to 331
2.	Time Stamps: In seconds (start of new section)
3.	Formal section label: Introduction, Verse, Pre-chorus, Chorus, Hook, Dance Chorus, Link, Post-chorus, Bridge, Outro, Refrain or Other
4.	Name of artist(s): Full name of the artist performing in each section. If all artists credited on the Billboard listing perform in a section, the label both or all is used.

For each formal section performed by one artist only,  the following analytical data on the voice is provided:
1.	Gender of artist: M (Man), W (Woman), NB (Non- binary) 2
2.	Function of artist: Feat (Featured artist), Main (Main artist), Neither, Uncredited 
3.	Style of vocal delivery: R (Rapped vocals), S (Sung vocals), Spoken 
4.	Minimum pitch value: in Hz
5.	First quartile pitch value: in Hz
6.	Median pitch value: in Hz
7.	Third quartile pitch value: in Hz
8.	Maximum pitch value: in Hz
9.	Environment value: On a scale of E1 to E5
10.	Layering value: On a scale of L1 to L5
11.	Width (panning) value: On a scale of W1 to W5





