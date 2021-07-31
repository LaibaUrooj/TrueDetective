# TrueDetective
Disguised Face Recognition w.r.t CCTV View


For FYP-2021-TrueDetective17Batch

True Detective is an intelligent system that recognizes a person from a cctv point of view. The person may disguise themselves using face mask, fake beard, hasts, glasses or just their bare face. 

[Breif Description]

     (1) TrueDetective is an intelligent system that finds a person through their face.

     (2) The face of the person may be bare face or disguised.

  (3) Their are 4 disguises in the data ( face mask, glasses, fake beard, hats )

(4) The recognition is done on CCTV images and videos.

(5) The data is self collected images from cctv point of view. (full info on datasetinfo file)

The DisguisedTrueDetective_1.py file contains the entire code for Disguise Face Recognition. on CCTV Images

You need to upload it on colab and convert it into an .ipynb notebook and run (Because the files size is very big it was uploaded .py extention)


--------------
>> DATASET USED: TrueDetectiveDataset-1
--------------

It contains pictures of 11 different individuals each comprisig of atleast 250 pictures.
The train and test data are disjoint. Download The dataset via the link provided and use the password given for it.

The Disguised Appearances Contain:
1) Bare Face Images
2) Glasses
3) Hats
4) Fake Beard
5) Face Masks

The images comprises of:

> various backgrounds

> complex background

> simple background

> side views

> light and dark conditions

> occlusion

> cctv view

With respect to fyp-1, we did recognition on BareFace, Glasses and Hat Recognition. 
With respect to fyp-2  we did recognition on Fake Baerd, Face Mask. 
The Test Train Data distribution is as below.


*******************************************************************************************************************************************************************************
**************************************************************************************************************************************************
								INFO

Total GB: 10.08
Password For Dataset: #FYP17Trudetective1!

https://drive.google.com/drive/folders/1Yo1DerbK6ziiCmWEPTX7wViSQbCywfQX?usp=sharing

IMAGES = [ BARE FACE, GLASSES, HATS, FAKE BEARD, FACE MASK ]
Total Individuals = 11
Total Images =  2201

> P1 - LAIBA
	Total BareFace = 51
	Total Glasses = 35
	Total Hats = 44
	Total FakeBeard = 45
	Total FACEMASK = 38
	Total images of p1 = 213

> P2 - RUHMA
	Total BareFace = 36
	Total Glasses = 32
	Total Hats = 27
	Total FakeBeard = 34
	Total FACEMASK = 31
	Total images of p2 = 160

> P3 - ABDUL SAAD
	Total BareFace = 61
	Total Glasses = 42
	Total Hats = 31
	Total FakeBeard = 38
	Total FACEMASK = 45
	Total images of p3 = 217

> P4 - ABDUR RAFAY
	Total BareFace = 39
	Total Glasses = 71
	Total Hats = 89
	Total FakeBeard = 46
	Total FACEMASK = 62
	Total images of p4 = 307

> P5 - HURAIRA
	Total BareFace = 90
	Total Glasses = 53
	Total Hats = 51
	Total FakeBeard = 40
	Total FACEMASK = 48
	Total images of p5 = 282

> P6 - HASSAN
	Total BareFace = 21
	Total Glasses = 32
	Total Hats = 27
	Total FakeBeard = 45
	Total FACEMASK = 38
	Total images of p6 = 162

> P7 - ZARYAB
	Total BareFace = 21
	Total Glasses = 45
	Total Hats = 26
	Total FakeBeard = 32
	Total FACEMASK = 53
	Total images of p7 = 177

> P8 - IBRAHIM
	Total BareFace = 19
	Total Glasses = 87
	Total Hats = 40
	Total FakeBeard = 31
	Total FACEMASK = 24
	Total images of p8 = 201

> P9 - ANAS
	Total BareFace = 18
	Total Glasses = 09
	Total Hats = 20
	Total FakeBeard = 48
	Total FACEMASK = 39
	Total images of p9 = 134

> P10 - MUSAAB
	Total BareFace = 28
	Total Glasses = 23
	Total Hats = 25
	Total FakeBeard = 48
	Total FACEMASK = 26
	Total images of p10 = 150
	
> P11 - MUNZAR
	Total BareFace = 45
	Total Glasses = 41
	Total Hats = 43
	Total FakeBeard = 44
	Total FACEMASK = 25
	Total images of p10 = 198

--------------
>> TRAIN SET:
--------------
P1
BARE FACE= 19  , GLASSES= 17    ,HATS= 17, FAKEBEARD= 18, FACEMASK= 17   [Sub-Total =  88]
P2
BARE FACE= 15  , GLASSES= 12    ,HATS= 11, FAKEBEARD= 15, FACEMASK= 15   [Sub-Total =  68]
P3
BARE FACE= 20  , GLASSES= 12    ,HATS= 11, FAKEBEARD= 17, FACEMASK= 19   [Sub-Total =  79]
P4
BARE FACE= 15  , GLASSES= 18    ,HATS= 27, FAKEBEARD= 16, FACEMASK= 27   [Sub-Total =  103]
P5
BARE FACE= 14   , GLASSES= 14   ,HATS= 14, FAKEBEARD= 18, FACEMASK= 21   [Sub-Total =  42]
P6
BARE FACE= 10   , GLASSES= 12   ,HATS= 14, FAKEBEARD= 18, FACEMASK= 16   [Sub-Total =  70]
P7
BARE FACE= 09   , GLASSES= 12   ,HATS= 08, FAKEBEARD= 10, FACEMASK= 22   [Sub-Total =  61]
P8 
BARE FACE= 09   , GLASSES= 21   ,HATS= 10, FAKEBEARD= 14, FACEMASK= 11   [Sub-Total =  65]
P9
BARE FACE= 08   , GLASSES= 05   ,HATS= 07, FAKEBEARD= 21, FACEMASK= 17   [Sub-Total =  58]
P10 
BARE FACE= 12   , GLASSES= 09   ,HATS= 06, FAKEBEARD= 22, FACEMASK= 11   [Sub-Total =  60]
P11
BARE FACE= 19   , GLASSES= 15   ,HATS= 17, FAKEBEARD= 18, FACEMASK= 11   [Sub-Total =  80]

			Total Images in Train Set = [774]

--------------
>> TEST SET:
--------------

P1
BARE FACE= 32,  GLASSES= 18    ,HATS= 27,  FAKEBEARD=27 ,  FACEMASK= 21     [Sub-Total = 125]
P2
BARE FACE= 21  , GLASSES= 20   ,HATS= 16,  FAKEBEARD=19 ,  FACEMASK= 16     [Sub-Total = 92]
P3
BARE FACE= 41  , GLASSES= 30   ,HATS= 20,  FAKEBEARD=21 ,  FACEMASK= 26     [Sub-Total = 138]
P4
BARE FACE= 24  , GLASSES= 53   ,HATS= 62,  FAKEBEARD=30 ,  FACEMASK= 35     [Sub-Total = 204]
P5
BARE FACE= 76  , GLASSES= 39   ,HATS= 37,  FAKEBEARD=22 ,  FACEMASK= 27     [Sub-Total = 152]
P6
BARE FACE= 11  , GLASSES= 19   ,HATS= 13,  FAKEBEARD=27 ,  FACEMASK= 22     [Sub-Total = 92]
P7
BARE FACE= 12  , GLASSES= 33   ,HATS= 18,  FAKEBEARD=19 ,  FACEMASK= 31     [Sub-Total = 113]
P8
BARE FACE= 10  , GLASSES= 66   ,HATS= 30,  FAKEBEARD=17 ,  FACEMASK= 14     [Sub-Total = 137]
P9
BARE FACE= 10  , GLASSES= 04   ,HATS= 13,  FAKEBEARD= 27,  FACEMASK= 22      [Sub-Total = 76]
P10
BARE FACE= 16  , GLASSES= 14   ,HATS= 19,  FAKEBEARD= 26,  FACEMASK= 15      [Sub-Total = 90]
P11
BARE FACE= 26  , GLASSES= 26   ,HATS= 26,  FAKEBEARD= 26,  FACEMASK= 14     [Sub-Total =  118]

			Total Images in Train Set = [1337]

