# Urban Visual Intelligence
This is code accompanying the publication: 
> Fan, Z., Zhang, F., Loo, B.P.Y., Ratti, C. (2023) [Urban Visual Intelligence: Uncovering Hidden City Profiles with Street View Images](https://www.pnas.org/).
*PNAS* **xxx** (under review)


## Data
To replicate the result, please 
* Fork the repo
```
gh repo clone brookefzy/urban-visual-intelligence
cd urban-visual-intelligence
```
* Create an environment (python=3.8)
* install packages
```
pip install -r requirements
```
* Create a folder `data` inside the repo folder, and download data from [here](https://drive.google.com/drive/folders/1MucBDnYFhRXD-B8XWMRF5fMKLfb-SS4J?usp=share_link) OR use the command line below:
```
mkdir data
cd data
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1s6xQlggQ6ZnXoMBtIt8gO4hhzRUDqg4t' -O allparameters_ct.csv
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1VtpHQOZxjz01KwGrdII_GedtzSfzI0w5' -O allparameters.csv

```
* Then download the data from [here](https://drive.google.com/drive/folders/1MucBDnYFhRXD-B8XWMRF5fMKLfb-SS4J?usp=share_link)

