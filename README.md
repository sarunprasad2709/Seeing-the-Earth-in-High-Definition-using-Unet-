Do the following steps in google colab:
1.pip install torchgeo
Description:Torchgeo is a python library designed for processing geospatial data
2.!wget https://landcover.ai.linuxpolska.com/download/landcover.ai.v1.zip
Description:This command is to download the landcover.ai dataset from the given url
3.!unzip landcover.ai.v1.zip
Description:This command is used to extract the contents of the landcover.ai dataset zip file and open the files folder in the colab.you will see the content folder,click the content folder you will get all the images,masks subfolder.from this subfolder we are using high generated satellite images and their corresponding masks
4.final code
Description:Accuracy:87.22 and high resolution land cover maps are generated
