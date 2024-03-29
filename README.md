# Urban Visual Intelligence
This is code accompanying the publication: 
> Fan, Z., Zhang, F.*, Loo, B. P., & Ratti, C. (2023). Urban visual intelligence: Uncovering hidden city profiles with street view images. Proceedings of the National Academy of Sciences, 120(27), e2220417120.


## Instructions
To replicate the result, please 
* Fork the repo
```
gh repo clone brookefzy/urban-visual-intelligence
cd urban-visual-intelligence
```
* Create an environment (python=3.8)
* Install packages with pip
```
pip install -r requirements.txt
```
* Create a folder `data` inside the repo folder, and download data from [here](https://drive.google.com/drive/folders/1MucBDnYFhRXD-B8XWMRF5fMKLfb-SS4J?usp=share_link) OR use the command line below:
```
mkdir data
cd data
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1s6xQlggQ6ZnXoMBtIt8gO4hhzRUDqg4t' -O allparameters_ct.csv
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1VtpHQOZxjz01KwGrdII_GedtzSfzI0w5' -O allparameters.csv
```

