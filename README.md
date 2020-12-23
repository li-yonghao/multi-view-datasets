# multi-view-datasets

###How to use

Download from google drive using the browser.

https://drive.google.com/drive/folders/1O_3YmthAZGiq1ZPSdE74R7Nwos2PmnHH
Note: The whole dataset is about 300MB to 400MB.

###About the data format

All the data is stored in MatLab ".mat" file format. Each ".mat" file contains at least two variables: X and Y. "X" is a cell array of feature matrix (dimension N by d) and "Y" is the label vector (dimension N by 1), where N is the number of data points and d is the dimension of features. The specification of the data is listed below

No.	Handwritten	Caltech-7/20	Reuters	NUS-WIDE	AWA
1	Pix(240)	Gabor(48)	English(21531)	CH(65)	CQ(2688)
2	Fou(76)	WM(40)	France(24892)	CM(226)	LSS(2000)
3	Fac(216)	CENTRIST(254)	German(34251)	CORR(145)	PHOG(252)
4	ZER(47)	HOG(1984)	Italian(15506)	EDH(74)	SIFT(2000)
5	KAR(64)	GIST(512)	Spanish(11547)	WT(129)	RGSIFT(2000)
6	MOR(6)	LBP(928)	-	-	SURF(2000)
num of data	2000	1474/2386	18758	26315	4000
num of classes	10	7/20	6	31	50
Note: Caltech-7 and Caltech-20 are two subsets of Caltech-101, which contains only 7 and 20 classes respectively. The creation of these subsets is due to the unbalance of the number of data in each classes of Caltech-101.

List of features:

Fourier coefficients of the character shapes (FOU)
Profile correlations (FAC)
Pixel averages in 2 × 3 windows (Pix),
Zernike moment (ZER)
Morphological (MOR) features.
Gabor feature
Wavelet moments (WM)
CENTRIST feature
Histogram of oriented gradients (HOG) feature
GIST feature
Local binary patterns (LBP) feature
Color Histogram (CH)
Color moments (CM)
Color correlation (CORR)
Edge distribution (EDH)
Wavelet texture (WT)
##Source

The source of the data are downloaded from the following links:

Handwritten
Caltech-101
Reuters
NUS-WIDE-Object
Animal with attributes (AWA)
