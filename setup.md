## SSH

* generate a new key pair
```bash
ssh-keygen -t rsa -f ~/.ssh/filename
```

* if the settings for the key are too open change the access rights for public and private keys
```bash
chmod 600 ~/.ssh/filename
```

## GCP

### new instance
* [Deep Learning VM Image](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/deeplearning?_ga=2.256620619.1335297341.1659455742-1798543970.1646400737&pli=1&project=lyrical-chassis-333813)
* Select compute center location and resources according to the computational needs



### add ssh access
* go to vm-instances
* select the instance
* edit instance
* add public ssh key
* save changes


## Conda

* get a yml file from github
```bash
wget url
```

* make env from yml
```bash
conda env create -f file
```

* activate env
```bash
conda activate name
```

* get env directory
```bash
which python3
```


## PyCharm

* add ssh configuration in PyCharm
* add path mappings from local to remote
*
