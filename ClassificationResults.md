# Content
[IMDb dataset](./IMDB.md)

[Rijksmuseum dataset](./Rijks.md)

[CycleGANN Monet2Photo results](./Monet2PhotoResults.md)

[CycleGANN Nightwatch results](./NightwatchResults.md)

[CycleGANN IMDB to Rijksmuseum full painting](./IMDB2RijksFullResults.md)

[CycleGANN IMDB to Rijksmuseum face only](./README.md)

[Perceived sex classification performance](./ClassificationResults.md) (this file)

# Perceived sex classification performance
## Rijksmuseum original faces
![Real](./FaceCropResults/0001755_SK-A-284.jpg)
![Real](./FaceCropResults/0001756_SK-A-285.jpg)
![Real](./FaceCropResults/0001811_SK-A-648.jpg)
![Real](./FaceCropResults/0001841_SK-A-275.jpg)
![Real](./FaceCropResults/0003706_SK-A-953.jpg)
![Real](./FaceCropResults/0003707_SK-A-957.jpg)
![Real](./FaceCropResults/0004270_SK-A-611.jpg)
![Real](./FaceCropResults/0004480_SK-A-2072.jpg)
![Real](./FaceCropResults/0004720_SK-A-179.jpg)

| | Classified female | Classified male | Total count| Performance |
 --- | --- | --- | --- | --- 
Actual female|281|218|499|56.31%
Actual male|77|929|1,006|92.35%
Total|358|1,147|1,505|**80.40%**
## Style transferred faces
![Style](./FaceCropResults/0001755_SK-A-284_10.jpg)
![Style](./FaceCropResults/0001756_SK-A-285_10.jpg)
![Style](./FaceCropResults/0001811_SK-A-648_10.jpg)
![Style](./FaceCropResults/0001841_SK-A-275_10.jpg)
![Style](./FaceCropResults/0003706_SK-A-953_10.jpg)
![Style](./FaceCropResults/0003707_SK-A-957_10.jpg)
![Style](./FaceCropResults/0004270_SK-A-611_10.jpg)
![Style](./FaceCropResults/0004480_SK-A-2072_10.jpg)
![Style](./FaceCropResults/0004720_SK-A-179_10.jpg)

| | Classified female | Classified male | Total count| Performance |
 --- | --- | --- | --- | --- 
Actual female|280|219|499|56.11%
Actual male|74|932|1,006|92.64%
Total|354|1,151|1,505|**80.53%**

## Gann transformed paintings
![Fake](./FaceCropResults/0001755_SK-A-284_fake_B.jpg)
![Fake](./FaceCropResults/0001756_SK-A-285_fake_B.jpg)
![Fake](./FaceCropResults/0001811_SK-A-648_fake_B.jpg)
![Fake](./FaceCropResults/0001841_SK-A-275_fake_B.jpg)
![Fake](./FaceCropResults/0003706_SK-A-953_fake_B.jpg)
![Fake](./FaceCropResults/0003707_SK-A-957_fake_B.jpg)
![Fake](./FaceCropResults/0004270_SK-A-611_fake_B.jpg)
![Fake](./FaceCropResults/0004480_SK-A-2072_fake_B.jpg)
![Fake](./FaceCropResults/0004720_SK-A-179_fake_B.jpg)

| | Classified female | Classified male | Total count| Performance |
 --- | --- | --- | --- | --- 
Actual female|309|190|499|61.92%
Actual male|148|858|1,006|85.29%
Total|457|1,048|1,505|**77.54%**

## Gann transformed faces
![Fake](./FaceCropResults/0001755_SK-A-284_fake_B-face.jpg)
![Fake](./FaceCropResults/0001756_SK-A-285_fake_B-face.jpg)
![Fake](./FaceCropResults/0001811_SK-A-648_fake_B-face.jpg)
![Fake](./FaceCropResults/0001841_SK-A-275_fake_B-face.jpg)
![Fake](./FaceCropResults/0003706_SK-A-953_fake_B-face.jpg)
![Fake](./FaceCropResults/0003707_SK-A-957_fake_B-face.jpg)
![Fake](./FaceCropResults/0004270_SK-A-611_fake_B-face.jpg)
![Fake](./FaceCropResults/0004480_SK-A-2072_fake_B-face.jpg)
![Fake](./FaceCropResults/0004720_SK-A-179_fake_B-face.jpg)

| | Classified female | Classified male | Total count| Performance |
 --- | --- | --- | --- | --- 
Actual female|366|133|499|73.35%
Actual male|228|779|1,006|77.43%
Total|594|912|1,505|**76.08%**
