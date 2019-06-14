# kicks3
S3 bucket finder from html,js and bucket misconfiguration testing tool

pip install awscli

aws configure


# Installation


pip install kick-s3


# OR

git clone https://github.com/abuvanth/kicks3.git

cd kicks3

pip install -r requirements.txt

## Usage

# single target

python kicks3.py -u http://target

# list of target 

python kicks3.py -u http://target -l sitelist.txt

# authenticated page


python kicks3.py -u http://target -c 'cookievalues'



# subdomains

python kicks3.py -u target.com -s 1
